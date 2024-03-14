# QGIS-AU website

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
