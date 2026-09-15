# EntGuard: Website

Static one-page site for [EntGuard](https://github.com/EntGuard/entguard), an open-source
enterprise VPN built on WireGuard®, by PANTHEON.tech.

Live at: https://entguard.github.io/

## Structure

Plain HTML/CSS, no build step. Everything needed is in `index.html` plus a handful of
static assets (favicons, `og-image.png`). Open `index.html` in a browser, or serve the
folder with any static file server.

## Deployment

This deploys as the `EntGuard` org's root GitHub Pages site (`https://entguard.github.io/`), which
means the repository itself must be named exactly `entguard.github.io`.

Deploys automatically to GitHub Pages via [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml)
on every push to `main`. In the repo settings, under **Settings → Pages**, set the source to
**GitHub Actions** (one-time setup).
