# Japan — Personal site

This repository contains a small static site about Japan (HTML + CSS). The site is intended to be served via GitHub Pages.

Files of interest:

- `japan.html` — main landing page (linked from `index.html`),
- `styles.css` — styles,
- other content pages: `landmarks.html`, `history.html`, `folklore.html`, `myths-legends.html`, `yokia.html`.

Deployment
- This repository includes a GitHub Actions workflow (`.github/workflows/pages.yml`) that publishes the repo to GitHub Pages on pushes to `main`.

If you want the site to use `japan.html` as the visible root page, the included `index.html` redirects to it automatically.
