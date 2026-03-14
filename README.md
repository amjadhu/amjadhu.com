# amjadhu.com

Personal website for Amjad Hussain. A minimal, modern landing page with an animated background.

**Status:** Work in progress

## Tech Stack

- Pure HTML, CSS, and vanilla JavaScript (no frameworks or dependencies)
- Deployed to [GitHub Pages](https://pages.github.com/) via GitHub Actions
- Custom domain: [amjadhu.com](https://amjadhu.com)

## Local Development

Open `index.html` in a browser. No build step required.

For a local server (optional):

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project Structure

```
.
├── index.html          # Main page
├── css/style.css       # Styles and animations
├── CNAME               # Custom domain config for GitHub Pages
└── .github/workflows/
    └── deploy.yml      # GitHub Pages deployment workflow
```

## Deployment

Pushes to `main` automatically deploy to GitHub Pages via the workflow in `.github/workflows/deploy.yml`.
