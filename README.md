# vme999.github.io

Personal portfolio and public project showcase for [vme999](https://github.com/vme999), published at [vme999.github.io](https://vme999.github.io/).

The site is a responsive, single-page portfolio built with plain HTML, CSS, and JavaScript. It displays a profile introduction and loads public, non-fork repositories from the GitHub API. Project cards link to their repositories and show a short description and primary language.

## Run locally

No build step or dependencies are required. From the repository root, start a local server:

```bash
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in a browser. The project list requires access to the GitHub API; the profile image is loaded from GitHub.

## Deployment

GitHub Pages serves `index.html` from the root of the `main` branch. Changes pushed to `main` are published automatically.
