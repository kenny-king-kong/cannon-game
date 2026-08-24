# Chalkboard Cannon — Demolition

A chalkboard-styled physics sandbox. Aim a cannon, tear down a procedurally
generated city of buildings and bridges, then sweep the rubble down the incline
into the hole.

**Play it:** https://kenny-kong-facemo.github.io/cannon-game/

## How to play

- **Move the mouse / drag** to aim the cannon.
- **Hold** to fire — 10 balls per second.
- Knock the buildings and bridges apart, then push the debris into the hole.
- Sinking a brick scores 5, sinking a ball scores 1.
- **new city** regenerates the level.

## Running locally

It's a single static page with no build step. Open `index.html` in a browser,
or serve the folder:

```bash
python -m http.server 8000
```

## Built with

- [Matter.js](https://brm.io/matter-js/) 0.19.0 for rigid-body physics (loaded from cdnjs)
- Canvas 2D for the hand-drawn chalk rendering
- Google Fonts: Patrick Hand, Gochi Hand

Both are loaded from CDNs, so the page needs an internet connection to look and
behave as intended.
