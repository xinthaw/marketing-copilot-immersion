# M365 Copilot Marketing Immersion

A hands-on training site for the Marketing team. Built with [Just the Docs](https://just-the-docs.com).

🌐 **Live site:** https://xinthaw.github.io/marketing-copilot-immersion

## How to update content

1. Edit any `.md` file in this repo (in the GitHub web editor or locally)
2. Commit your change
3. Wait ~30 seconds — GitHub Pages rebuilds automatically

## Adding pages

Create a new `.md` file at the repo root with this front matter:

```yaml
---
title: Your page title
layout: default
parent: Core sessions          # which sidebar group it lives under
nav_order: 4                   # position within that group
---
```

## Adding files to download

1. Upload to the `assets/` folder
2. Link from a page: `[Download brief]({{ site.baseurl }}/assets/brief.docx){: .btn .btn-primary }`

## Customizing colors

Edit `_sass/color_schemes/marketing.scss`.
