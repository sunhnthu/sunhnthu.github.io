# Haoning Sun — Academic Website

A Quarto academic website designed for local preview and later deployment with GitHub Pages.

## Site structure

- `index.qmd` — Home page and Job Market Paper
- `research.qmd` — Published and accepted papers
- `research.qmd` — Job Market Paper, R&Rs, working papers, and research in progress
- `teaching.qmd` — Teaching assistant experience
- `cv.qmd` — Web CV and downloadable PDF CV
- `research.qmd` — Compatibility/landing page for Research
- `_quarto.yml` — Site navigation and global settings
- `styles.css` — Custom styles

## Preview locally

Open this folder in VS Code and run:

```bash
quarto preview
```

The website will open at a local address such as `http://localhost:4200`. It is not public until you deploy it.

## Add publication / SSRN links

Markdown links use this syntax:

```markdown
[**Paper Title**](https://your-paper-url)
```

You can also add compact links after a citation:

```markdown
[Journal](https://doi.org/...) · [SSRN](https://ssrn.com/abstract=...) · [PDF](files/paper.pdf)
```

Comments inside `research.qmd` and `research.qmd` mark the recommended locations for these links.

## Navigation

The top navigation is defined in `_quarto.yml` and currently appears as:

`Home | Research ▾ | Teaching | CV`

The Research dropdown contains Publications and Working Papers.
