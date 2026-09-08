# jiarui-liu.github.io

Personal academic website of Jiarui Liu, built with [Hugo](https://gohugo.io/) and the [Hugo Blox Academic CV](https://github.com/HugoBlox/theme-academic-cv) theme, deployed to GitHub Pages via the workflow in `.github/workflows/publish.yaml`.

## Layout

- `content/authors/admin/` – biography, education, interests, and social links (`_index.md`) plus the avatar.
- `content/_index.md` – homepage sections (biography, news, publications).
- `content/publication/` – one folder per paper; entries are sorted by `lastmod`, newest first.
- `content/docs/JiaruiLiu_CV.pdf` – the CV linked from the profile and navbar.
- `config/_default/` – site configuration.

## Local preview

```bash
hugo server
```
