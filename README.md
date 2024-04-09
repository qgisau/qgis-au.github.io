# QGIS-AU website

https://qgis-australia.org/

Built using hugo

## Add a Post
Add a new md file under content/posts/  
  e.g. `content/posts/post-009.md`  
Copy this to the top  
```
+++
title = '008 - 9th April 2024'
date = 2024-04-09T07:07:07+01:00
draft = false
+++
```
- Amend the title
- Enter the date, if you want to create it prior to the publish date, you can set this date to a future date.
- Draft = false means it will be publised live. change to true to keep it from publishing
- Add in the Content
- Commit to a new branch
- Check the website

### Images
- Add the images to `static/images`
- Reference the image in the post
   ` ![alt name](/images/imagename.png)`
  
*Don't worry if they don't appear in GitHub, they will appear in the webpage.*

### Troubleshooting
Check the:
- names
- forward slashes
- dates must be yyyy-mm-dd

## Adding a new page

Any `.md` files found under `content/posts` will be render as pages on the site under The Happenings and Recent Updates

Use `hugo new content posts/{nameofpage}.md` to create a new page

OR MANUALLY

Create a page under `content/posts/` `mypage.md` with the following content as the page header:

```
+++
title = 'My First Post'
date = 2024-01-14T07:07:07+01:00
draft = false
+++
```

Set `draft = true` if you don't wish the page to show up on the site yet

## Adding a new section

Add a new `[[main]]` block in `menus.en.toml` like so 

```
[[main]]
  name = "About"
  pageRef = "about"
  weight = 10
```

Update `name` and `pageRef`. Create a new folder in content with the same name as `pageRef` and add a `_index.md` file as the main page for that `pageRef`
