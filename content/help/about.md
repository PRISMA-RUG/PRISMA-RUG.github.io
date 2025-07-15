---
title: "About page"
description: "For mantainers"
groupByYear: false
showBreadcrumbs: true
date: 2025-01-01
enableEmoji: true
---

About contains general information about PRISMA, and links to the involved authors and author pages. You can create your own author page by adding a folder with your name, a picture with the name "featured_your_name" inside it, and a index.md page of your liking. Tag it with the 'authors' tag so it appears in searches correctly.

Once you do, you can edit the 'hugo.toml' configuration in the main folder to add navigation from the About Us submenu to your page. Use the same format as the one for George:

```toml
  [[menus.main]]
    name = "George Azzopardi"
    parent = "About Us"
    pageRef = "/about/george"
    weight = 2
```

Here you would change "/about/george" to "/about/your_folder_name" and "George Azzopardi" to your own name. Weight is what order the menu is presented at. To ensure that George's name stays at the beginning of the list, use weights >10! Other than that, use whatever order you like.
