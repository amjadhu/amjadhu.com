# CLAUDE.md

## Project Overview

Personal website for Amjad Hussain hosted at amjadhu.com. Static site deployed to GitHub Pages.

## Architecture

- **No build tools or frameworks** - pure HTML/CSS/JS
- Single page site: `index.html` is the only page
- Styles in `css/style.css`
- Animated canvas background rendered with vanilla JS (inline in index.html)
- GitHub Actions deploys the repo root directly to GitHub Pages on push to `main`

## Key Files

- `index.html` - All content, structured data, and inline JS for background animation
- `css/style.css` - Styling, responsive design (clamp-based), animations
- `CNAME` - Custom domain configuration (amjadhu.com)
- `.github/workflows/deploy.yml` - GitHub Pages deploy workflow

## Design Decisions

- Dark theme (#0a0a0f background) with light text
- Inter font (weights 300, 400) loaded from Google Fonts
- Animated orbs on canvas with breathing/pulse effect
- Dot grid overlay via CSS pseudo-element
- Minimalist: name + single LinkedIn CTA

## Working With This Site

- No install or build step needed - just edit files and push
- Test locally by opening `index.html` in a browser
- All deployment is automatic via GitHub Actions on push to main
- Keep the site lightweight - avoid adding frameworks or build tools
