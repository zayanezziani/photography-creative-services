# Photography & Creative Services

A photography and creative services website prototype built with [Figma Make](https://www.figma.com/make), React, Tailwind CSS v4, and Vite.

## Features

- **Hero section** — Full-width fashion photography with gradient overlay and bottom-fade vignette blending into the dark section below
- **Navigation bar** — Pine tree logo + Services / About / Contact links
- **Client logos** — Fiverr, Amazon (G2), eBay, and Amazon logos rendered as inline SVGs
- **Services grid** — Six photography types: Video & Paid Social, Product Photography, Fashion & Ghost Mannequin, Post-Production, Lifestyle & Campaign, Jewellery
- **Portfolio gallery** — Full-height masonry-style portfolio
- **CTA button** — "Get a free quote"

## Tech stack

| Tool | Version |
|---|---|
| React | 18.3.1 |
| Vite | 6.3.5 |
| Tailwind CSS | 4.1.12 |
| TypeScript | via Vite |

## Fonts

- **Playfair Display** — headings
- **Inter** — body / UI text
- **Petrona** — ampersand accents in service names

Loaded via Google Fonts and mapped to Figma's font naming convention using CSS attribute selectors in `src/styles/fonts.css`.

## Assets

All images are imported via `figma:asset` references (resolved by Vite at build time inside Figma Make). SVG paths are stored in `src/imports/svg-ljlhfgivb7.ts` and `src/imports/svg-yypkgdcit0.ts`.

## Getting started

This project is designed to run inside **Figma Make**. If running locally, you will need to resolve the `figma:asset/*` virtual module references with your own image assets.

```bash
pnpm install
pnpm build
```
