# Marshall

The official website for Marshall, the music player for Windows and Android. This repository contains the site's static HTML, CSS, JavaScript, and supplied application screenshots.

## Run locally

Open `index.html` in a browser, or serve this directory with any static file server. No build step or package installation is required.

## Project structure

- `index.html` — page content, SEO and social metadata, and application links
- `style.css` — responsive layout, visual design, and animations
- `script.js` — mobile navigation and scroll/reveal interactions
- `assets/` — Marshall logo and application screenshots

## Cloudflare Pages

Create a Pages project connected to this GitHub repository with these settings:

- Framework preset: **None**
- Production branch: **main**
- Root directory: **/**
- Build command: leave empty
- Build output directory: **/**

The site is served directly from the repository root. Pushes to `main` can be deployed automatically by Cloudflare Pages.
