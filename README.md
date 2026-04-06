# Snake Game (Vanilla JS Portfolio Project)

A polished browser-based Snake game built with **pure HTML, CSS, and JavaScript** in a **single file**.  
No frameworks, no build tools, no dependencies — just double-click and play.

## Project Overview

This project recreates the classic Snake gameplay and upgrades it into a portfolio-ready frontend showcase with:

- modern card-style UI
- multilingual support (Chinese / English)
- persistent settings and high score
- smooth interaction design and clear game state feedback

## Features

### Core Gameplay
- Classic Snake rules
- Keyboard controls: `Arrow Keys` and `WASD`
- Score tracking
- Start, Pause/Resume, Restart
- Game-over handling with final score

### Portfolio Enhancements
- High score persistence via `localStorage`
- Difficulty/speed levels: Easy / Normal / Hard
- Visible game status: `Ready`, `Playing`, `Paused`, `Game Over`
- Theme switching: Light / Dark / Forest
- Intro instructions before play
- Subtle UI animations (hover, panel transitions)
- Mobile usage tip (keyboard recommended)

### i18n (Chinese / English)
- One-click language toggle
- All texts are translated (titles, labels, buttons, hints, status)
- Unified dictionary structure:
  ```js
  const i18n = { zh: {...}, en: {...} }
  ```
- `t(key)` helper for text lookup
- Instant language update without page reload
- Language preference saved in `localStorage`

## Tech Stack

- **HTML5**
- **CSS3** (custom properties, responsive layout, transitions)
- **Vanilla JavaScript**
- **Canvas API** for rendering the game board

## Run Locally

1. Save the file as `snakeGame01.html`
2. Double-click it to open in a browser  
   (or drag it into a browser tab)

No installation required.

## Controls

- Move: `↑ ↓ ← →` or `W A S D`
- Pause / Resume: `Space` or pause button
- Start: Start button
- Restart: Restart button

## Why This Project Stands Out

- Single-file architecture with clear modular logic
- Clean state management (`ready / playing / paused / over`)
- Independent structures for i18n and themes
- Safe `localStorage` read/write handling
- Portfolio-friendly UI with consistent visual language

## Future Improvements

- Touch controls for mobile gameplay
- Sound effects and background music toggle
- Particle effects for food pickup
- Level map / obstacles mode
- Leaderboard sync with backend API
