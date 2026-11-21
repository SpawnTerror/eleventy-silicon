---
title: "Getting started with Eleventy Silicon"
date: 2026-05-01
permalink: "/getting-started-with-eleventy-silicon/"
layout: layouts/post.njk
tags: ["Coding", "Linux"]
description: "Quick walkthrough of writing posts, choosing topics, and deploying the Eleventy Silicon starter theme."
---

Welcome to **Eleventy Silicon**, a lightweight monospace Eleventy 3 starter theme built for technical notes, hardware write-ups, and personal engineering blogs.

## Writing your first note

Create a new Markdown file inside `src/posts/` using the `YYYY-MM-DD-slug.md` naming convention:

```yaml
---
title: "My technical note"
date: 2026-05-01
permalink: "/my-technical-note/"
layout: layouts/post.njk
tags: ["Hardware", "Linux"]
description: "A concise summary for search engines."
---
```

::: tip
Run `npm start` for live reload while writing, and `npm run build` to generate the static production output in `_site/`.
:::

## Customising your site identity

Open `src/_data/site.json` to change the site name, terminal prompt, domain, email, GitHub link, and DIP-chip silkscreen label in one place. Edit `src/_data/featured.json` to pick which posts appear under **Most Read** on the homepage.
