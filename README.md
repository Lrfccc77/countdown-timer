# Countdown Timer

A minimalist, single-file countdown timer with a DIY color theme engine.

## Features

- Oversized tabular-digit display (HH:MM:SS), responsive from mobile to desktop
- Quick presets: 1m / 5m / 10m / 15m / 25m / 1h
- Click any digit to edit inline; hover steppers and mouse wheel also adjust units
- Start / Pause / Resume / Reset, with `Space` and `R` keyboard shortcuts
- Razor-thin top progress hairline that tracks remaining time
- 3D rotating palette carousel with 13 curated two-tone color themes
- Free-form two-tone color pickers with automatic contrast-safe derived tones
- Theme persisted to `localStorage`
- Web Audio completion chime (no external audio assets)
- Browser tab title mirrors the live countdown

## Run locally

Open `index.html` directly in a browser. No build step or dependencies to install.

## Deployment

Hosted as a static site via GitHub Pages.

## Tech

Vanilla HTML/CSS/JavaScript, Tailwind CSS (CDN), Google Fonts (Inter).
