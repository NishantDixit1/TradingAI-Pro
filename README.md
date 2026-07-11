# TradingAI Pro

A marketing landing page for TradingAI Pro, a concept product that showcases advanced machine learning models for financial market prediction. Built as a fast, static single page site with Vite and vanilla JavaScript.

## What it shows

The page is composed of modular sections, each rendered by its own component:

- **Hero** — headline pitch for AI driven trading strategies
- **Features** — key selling points of the platform
- **Models** — the ML approaches on display: GANs, Multi-Head GANs (MHGANs), Information GANs (InfoGANs), VAEs, CNNs, and Bayesian Networks
- **Results** — sample performance highlights
- **Footer** — links and contact

> Note: This is a front end marketing site only. It is a UI demo and does not include any live trading engine, model inference, or financial advice.

## Tech stack

- Vite for dev server and build
- Vanilla JavaScript component modules (`src/components/`)
- Plain CSS (`src/style.css`)

## Getting started

```bash
npm install
npm run dev      # start the dev server on http://localhost:5173
npm run build    # production build into dist/
npm run preview  # preview the production build
```

## Project structure

```
index.html            # entry, mounts #app
src/
  main.js             # composes the page from components
  style.css           # styles
  components/
    header.js
    hero.js
    features.js
    models.js
    results.js
    footer.js
vite.config.js
vercel.json           # Vercel deploy config
```

## Deployment

Configured for Vercel via `vercel.json`. Any static host works: run `npm run build` and serve the `dist/` folder.
