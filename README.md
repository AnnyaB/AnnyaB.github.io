# Riya Basak — Academic Homepage

A minimal academic research homepage built with the public
[`yaoyao-liu/minimal-light`](https://github.com/yaoyao-liu/minimal-light) Jekyll theme.

The structure is intentionally sparse: identity, short research statement,
one-line research interests, research output, education, and experience.

## Publish this as a GitHub Pages site

1. On GitHub, create a **public** repository named exactly:

   `AnnyaB.github.io`

2. Upload all files from this folder to the repository root.

3. Open **Settings → Pages**.

4. Under **Build and deployment**, choose **Deploy from a branch**.

5. Select:
   - Branch: `main`
   - Folder: `/ (root)`

6. Save. GitHub Pages will publish the site at:

   `https://annyab.github.io/`

## Main files

- `_config.yml` — name, academic title, affiliation, email, CV/GitHub/LinkedIn links.
- `index.md` — About, research interests, education, and experience.
- `_includes/research.md` — preprint/manuscript and selected research projects.

## Before publishing

For the cleanest academic presentation, replace the GitHub-avatar URL in
`_config.yml` with a professional square headshot placed at:

`assets/img/profile.jpg`

Then set:

```yml
avatar: ./assets/img/profile.jpg
```

Do not describe Riya as a KAIST student before enrolment. The page is designed
to present a strong research trajectory without implying an affiliation that
does not yet exist.
