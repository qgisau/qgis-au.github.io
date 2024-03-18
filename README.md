# QGIS-AU website

https://qgis-australia.org/

Built using hugo

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
