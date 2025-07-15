---
title: "Authors data"
description: "For mantainers"
groupByYear: false
showBreadcrumbs: true
authors:
 - "rafael"
date: 2025-01-01
enableEmoji: true
---

Authors are handled a bit differently than a normal page. While each researcher can have (and I would encourage them to have) a separate page for themselves under the /about/ page, the actual author header, image, socials, and description is kept under the /data/authors/ **folder** in separate .jsons.

You can modify any part of your own entry to your liking, though I'd encourage keeping things relatively uniform to the others. You can upload your image to the /assets/img/team/ folder. After that, you can modify or create a .json for yourself:

```json
{
    "name": "Prof. George Azzopardi",
    "image" : "img/team/george_headshot.png",
    "bio": "🇲🇹 Leader of PRISMA. As the academic lead of PRISMA, I guide our research team in advancing the robustness of vision models, developing innovative approaches to machine learning, and transforming complex data into actionable insights.",
    "social": [
        { "graduation-cap": "https://scholar.google.com/citations?user=6QnooDkAAAAJ&hl=en&oi=ao"},
        { "researchgate": "https://www.researchgate.net/profile/George-Azzopardi"},
        { "twitter": "https://twitter.com/azzopardi_g"},
        { "linkedin": "http://www.linkedin.com/in/georgeazzopardi"},
        { "github": "https://github.com/geazzo" },
        { "orcid": "https://orcid.org/0000-0001-6552-2596" }
    ]
}
```

Note that you can use emojis! There are many more social sites available, consult which icons we have installed [here.](https://blowfish.page/samples/icons/) Add them to your liking! Make an effort to maintain the order used here, for uniformity.

Once you have this added, you can add your author badge at any *non-landing* page (so not _index.md pages, but yes index.md pages or any other .md page) by making sure the following frontmatter is present in your .md file:

```markdown
showAuthor: true
authors:
  - "peter"
  - "george"
  
showAuthorsBadges: true
```

This page has an author badge, for example. In some subpages, the 'showAuthors' and 'showAuthorsBadges' is on by default, so they may be redundant, but it's never wrong to include them if you want the author to show up.

