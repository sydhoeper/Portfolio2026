# Syd Hoeper — Portfolio 2026

A senior product design portfolio built from the visual system and case-study structure of [sydhoeper.com](https://sydhoeper.com).

## Included

- A responsive main page with Syd's positioning, background, working style, and contact details
- Five complete product-design case studies with their original imagery and media
- Sarah Doody-inspired case-study architecture: overview, problem, users, role, constraints, process, outcomes, and lessons
- Three evidence-led featured projects on the homepage, with the remaining work available in navigation
- A living local design-system page
- Fraunces and Avenir typography, cream surfaces, pastel spectrum details, and the original spacing system
- Accessible navigation, galleries, carousels, focus states, and reduced-motion support
- A downloadable PDF resume
- Automatic GitHub Pages deployment

## Run locally

There is no build step or package installation.

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/#home`.

## Structure

- `index.html` — application shell and portfolio navigation
- `style.css` — shared design system and responsive layouts
- `script.js` — page routing and interactive behaviors
- `pages/home.html` — main portfolio page
- `pages/User Experience Design/` — product case studies
- `images/` — case-study and homepage media

## Publish with GitHub Pages

The included workflow deploys the site whenever a commit is pushed to `main`.
