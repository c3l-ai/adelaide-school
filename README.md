# The Adelaide School
### Learning Sciences, Data & AI

A Quarto website for **The Adelaide School** — a two-day intensive forum hosted by the [Centre for Change and Complexity in Learning (C3L)](https://c3l.edu.au) at Adelaide University.

## About

The Adelaide School brings together researchers, educators, and practitioners working at the intersection of learning sciences, data, and artificial intelligence. It is designed around participation — structured sessions where attendees bring their work, their questions, and their half-formed ideas, and leave with something concrete.

## Site Structure

| File | Description |
|------|-------------|
| `index.qmd` | Home page — event overview and audience framing |
| `program.qmd` | Full two-day program with session descriptions |
| `sessions.qmd` | Twelve parallel sessions across two tracks |
| `speakers.qmd` | Speaker profiles (to be populated) |
| `about.qmd` | Event rationale, format, and C3L context |
| `custom.scss` | Branding — C3L colour palette and typography |
| `.github/workflows/publish.yml` | GitHub Actions: renders and deploys to GitHub Pages on push to `main` |

## Local Development

Requires [Quarto](https://quarto.org/docs/get-started/).

```bash
# Preview locally
quarto preview

# Render to docs/
quarto render
```

## Deployment

The site deploys automatically to GitHub Pages via GitHub Actions on every push to `main`.

To enable: go to **Settings → Pages → Source** and select **GitHub Actions**.

The site will be available at: `https://c3l-ai.github.io/adelaide-school`

## Maintained by

[C3L — Centre for Change and Complexity in Learning](https://c3l.edu.au), Adelaide University.
