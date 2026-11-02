# Traffic Dodge — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Dodge 12 lanes of speeding traffic! Hop one lane at a time, chain crossings
for combo bonuses, and reach the safe grass to face faster rounds. 3 lives,
police cars, trucks and a night shift.

(190 characters)

## Details

- Genre: Arcade / Action / Casual (Frogger-like road crossing)
- Controls: Keyboard: ←/→/↑/↓ or WASD to hop one tile. Mobile: swipe in any
  direction, or tap an adjacent tile.
- Features:
  - 12 lanes with random direction, 3 speed tiers and random gaps, refreshed
    and sped up every round
  - +1 per new lane, +5 to reach the top grass, combo bonus (+combo x 0.5)
  - Police cars (fast) and 2-cell trucks appear occasionally
  - Night mode with glowing headlights once you pass 30 points
  - 3 lives, 1.5s spawn shield, best score saved locally
  - Crossable-by-design traffic: same-direction adjacent lanes share speed and
    aligned gaps, so a safe crossing window always appears
- Tech: Vanilla JavaScript, Canvas, WebAudio. Single-file HTML5, zero external
  assets (no CDN, images or fonts), works offline once loaded, no tracking.

## Tags

frogger, arcade, crossing, traffic, dodge, casual, retro, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales to fit viewport, portrait-friendly), keyboard + touch
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## GameDistribution
- Upload traffic-dodge-gd.zip (contains only index.html)
- SDK v2 loader is embedded and activates automatically on
  gamedistribution / gd.games domains

## itch.io
- Upload zip (traffic-dodge-itch.zip), mark "This file is playable in browser",
  entry file: index.html, viewport 480×720, kind: html
- Pricing: $0 (donations optional)
