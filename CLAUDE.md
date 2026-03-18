# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Plain HTML/CSS/JS personal portfolio site, deployed to GitHub Pages via GitHub Actions.

No build step — the files are served directly. The `.nojekyll` file prevents GitHub Pages from running Jekyll.

## Structure

- `index.html` — single-page site with sections: hero, about, projects, contact
- `css/style.css` — all styles; uses CSS custom properties defined in `:root`
- `.github/workflows/deploy.yml` — deploys on push to `main` using the GitHub Pages Actions workflow

## Deployment

Push to `main`. GitHub Actions uploads the repo root as the Pages artifact. Enable Pages in the repo settings under **Settings → Pages → Source: GitHub Actions**.

## Customization points

- Colors/fonts: CSS variables at the top of `css/style.css` under `:root`
- Projects: duplicate/edit `.project-card` blocks in `index.html`
- Nav links: `<nav>` in `<header>` and matching `id` attributes on sections
