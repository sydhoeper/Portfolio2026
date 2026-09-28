# Syd Hoeper Portfolio 2026

A fast, responsive portfolio site for senior product designer Syd Hoeper.

## Run locally

No build step or package installation is required.

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## Structure

- `index.html` — page content and semantic structure
- `styles.css` — responsive layout and visual design
- `script.js` — reveal animation and current year
- `assets/` — downloadable resume and future project images

## Publish with GitHub Pages

The included workflow deploys the site whenever a commit is pushed to `main`.
In the repository settings, set **Pages → Source** to **GitHub Actions** if it is
not already selected.
