# Péter Horváth — personal website

Quarto website for Péter Horváth, Research Economist at the Ministry of Finance of Hungary and PhD Candidate in Economics at Corvinus University of Budapest.

## Structure

- `index.qmd` — homepage
- `papers.qmd` — research and publications
- `cv.qmd` — web CV
- `codes.qmd` — landing page for future public data and code
- `code/` — reusable research code
- `data/` — redistributable data and/or data-construction documentation
- `replication/` — project-level replication packages
- `assets/` — CV PDF and site images
- `docs/` — rendered GitHub Pages output

## Rendering

The site is configured to render into `docs/`:

```bash
quarto render
```

## Sharing research materials

When a project is ready for public release, add its materials under `replication/` and/or `code/` and add a corresponding card to `codes.qmd`. Do not commit confidential data, licensed data that cannot be redistributed, credentials, or other restricted material.
