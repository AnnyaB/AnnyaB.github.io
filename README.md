# Academic Homepage

[![Minimal Light](https://img.shields.io/badge/theme-Minimal%20Light-2f6f9f?style=flat-square)](https://github.com/yaoyao-liu/minimal-light)
[![GitHub Pages](https://img.shields.io/badge/deployment-GitHub%20Pages-222?style=flat-square&logo=github)](https://annyab.github.io/)

\[[Live Homepage](https://annyab.github.io/)\]  \[[日本語](./README_ja.md)\]

This repository contains the source code for my **academic homepage**.

The site uses the open-source [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll theme and is deployed with GitHub Pages.

## Features

- Minimal academic homepage layout
- Jekyll-based GitHub Pages deployment
- Responsive desktop and mobile presentation
- Light and dark mode support
- Markdown-based page content
- Search-engine metadata through `_config.yml`
- Local CV asset linked directly from the homepage
- Modular research content through `_includes`

## Project Architecture

```text
.
├── _includes/
│   └── research.md              # research outputs and ongoing projects
├── assets/
│   └── files/
│       └── riya-basak-cv.pdf    # curriculum vitae linked from the homepage
├── .gitignore
├── Gemfile                      # Ruby/Jekyll dependencies
├── README.md                    # repository documentation (English)
├── README_ja.md                 # repository documentation (Japanese)
├── _config.yml                  # identity, links, SEO metadata, theme settings
└── index.md                     # main academic homepage content
```

## Deployment

The repository is published as a GitHub Pages user site:

```text
https://annyab.github.io/
```

The site is built from the `main` branch using the repository root.

## Theme Configuration

The homepage uses Minimal Light as a remote Jekyll theme:

```yaml
remote_theme: yaoyao-liu/minimal-light
```

Core site metadata and links are configured in `_config.yml`, including:

```yaml
title: Riya Basak
position: Prospective Integrated MS–PhD Student in Artificial Intelligence
affiliation: University of Hertfordshire
email: riyabasak639 (at) gmail.com

cv_link: /assets/files/riya-basak-cv.pdf
github_link: https://github.com/AnnyaB
linkedin: https://www.linkedin.com/in/riya-b-506346315/
```

## Editing the Homepage

The principal content files are:

- `index.md` — biography, research interests, research direction, education, and recent experience.
- `_includes/research.md` — preprint, manuscript, completed research, and ongoing world-model projects.
- `_config.yml` — site identity, academic links, profile image, SEO metadata, and theme settings.
- `assets/files/riya-basak-cv.pdf` — the CV opened by the homepage CV icon.

Because the site uses a remote theme, the upstream Minimal Light layout and styling are inherited without duplicating the complete theme source in this repository.

## Local Preview

With Ruby and Bundler installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open:

```text
http://localhost:4000
```

## Acknowledgements

This homepage is built with [Yaoyao Liu's Minimal Light](https://github.com/yaoyao-liu/minimal-light) academic Jekyll theme.

The sparse academic-homepage organization was also informed by [Dongkeun Yoon's public homepage repository](https://github.com/MattYoon/mattyoon.github.io), which uses the same Minimal Light theme. No personal, academic, publication, or biographical content from that repository is used here.

Minimal Light itself acknowledges and draws from the following open-source projects:

- [pages-themes/minimal](https://github.com/pages-themes/minimal)
- [orderedlist/minimal](https://github.com/orderedlist/minimal)
- [al-folio](https://github.com/alshedivat/al-folio)

## License and Theme Attribution

Theme code remains subject to the licensing terms of the upstream [Minimal Light repository](https://github.com/yaoyao-liu/minimal-light). Content and repository-specific assets in this site remain attributable to their respective owners.
