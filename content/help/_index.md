---
title: "How to add to this site"
description: "For mantainers"
layout: "list"
groupByYear: false
showBreadcrumbs: true
enableEmoji: true
---
We use Hugo + Blowfish to make this site easy to edit. New content is added as a markdown file or folder under the 'content/' folder. 

This is an example page for a list, which is used for the /projects/ , /about/ , and /posts/ sections. You can use all markdown commands as usual.

The folder layout dictates the structure of the site:
- Root is content (/)
- Any folders or .md files in content become accessible from root (such as /help/ , or /projects/)
- Any .md file with the name _index.md is the landing page to a list, while any page with index.md is the destination page of that folder, good for the end-level domain (see /about/george/ for an example).
- Any extra .md files become subdomains of the folder. See other files in /help/ for an example.
- To add thumbnail previews, add an image with the name feature*. For example 'featureimage.png', 'featuredmodel.jpg' are valid.
- And that's it! 

Below you'll find some more articles specifically for managing each section of the site. Some other tricks you may want to know are [shortcodes,](https://blowfish.page/docs/shortcodes/) or the documentation for our [theme.](https://blowfish.page) 

As for this section, this is an orphaned page -- nothing links to it! That's by design. It's publicly accessible since this page's code is hosted publicly anyway, and can be accessed from the search function or by going to the /help/ page. If you're not part of the mantainence team, hi! This information is probably not relevant to you! If you found something that looks wrong, we'd appreciate you filing an issue in our github so we can take a look. Since you seem interested, may I suggest taking a look at our [projects](https://www.youtube.com/watch?v=dQw4w9WgXcQ) instead of this page?
