# Vipul Kumar Portfolio

A responsive single-page portfolio site built with plain HTML/CSS.

## Run locally

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment options

### 1) GitHub Pages (recommended)

This repository includes a workflow at `.github/workflows/deploy-pages.yml` that deploys automatically to GitHub Pages whenever changes are pushed to `main`.

1. Push this repo to GitHub.
2. In **Settings → Pages**, set Source to **GitHub Actions**.
3. Push to `main`; deployment will be published automatically.

### 2) Netlify (drag-and-drop or Git)

A `netlify.toml` file is included. You can:
- Connect the repo in Netlify and deploy, or
- Drag and drop this folder in Netlify Drop.

Since this is a static site, no build command is required.

### 3) Vercel

Connect the repository in Vercel and deploy as a static site.
No framework preset is required.
