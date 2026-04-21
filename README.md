# The Oracles — Website

A static site for theoracles.studio. Built with Astro + Tailwind CSS v4, deployed on Netlify. Aesthetic reference: [thelinestudio.com](https://thelinestudio.com/).

## Local setup

Requirements: Node 20+ (install via Homebrew: `brew install node` if needed).

```bash
# from the project folder
npm install
npm run dev        # http://localhost:4321
```

## Build

```bash
npm run build      # output goes to ./dist
npm run preview    # preview the built site locally
```

## Project structure

```
src/
  components/      # Header, Footer, and reusable UI primitives
  layouts/         # BaseLayout wrapping every page
  pages/           # One .astro file per route (index.astro = /)
  styles/          # global.css — tokens, type scale, filmic motifs
public/            # static assets served at site root
docs/              # inspiration + reference docs (not deployed)
headers/           # design mockup PNGs (not deployed)
```

## Design tokens

Defined at the top of `src/styles/global.css` using Tailwind v4's `@theme` block. Change color/type/spacing there; changes cascade site-wide.

Core palette:
- `--color-paper` `#efeeea` — warm off-white body
- `--color-ink` `#0b0b0b` — near-black type
- `--color-vermillion` `#d64228` — accent, used sparingly
- `--color-muted` `#6b6a66` — secondary text
- `--color-hairline` `#d6d4cf` — dividers

Fonts (loaded from Google Fonts in `BaseLayout.astro`):
- Display — Archivo Black (DenimWeb stand-in)
- Body — Inter
- Mono — IBM Plex Mono

## Deployment

Netlify pulls from Git and runs `npm run build`. Publish directory: `dist/`.
