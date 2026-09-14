# Swipe Snake

A one-thumb mobile snake game — swipe to steer, eat the dots, beat your high score.

**Play now:** [https://juliusreischaur.github.io/phone-game/](https://juliusreischaur.github.io/phone-game/)

## How to play

1. Open the link on your phone (mobile Safari / Chrome).
2. Tap **Play**.
3. **Swipe** up / down / left / right to change direction.
4. Eat the yellow food to grow and score.
5. Don’t hit the walls or yourself. Speed ramps up as you score.
6. Your **best score** is saved in the browser (`localStorage`).

## Features

- Touch / swipe controls (mobile-first)
- Score + high score in `localStorage`
- Start / game over / restart overlays
- Dark theme, large tap targets, safe-area insets
- Scroll / bounce prevented while playing
- Plain HTML / CSS / JS — single `index.html`

## Local

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Hosting

Published via **GitHub Pages** from the `main` branch root (`/`).
