# Infinite Platformer

A 3D infinite-runner platformer built with [Three.js](https://threejs.org/), playable directly in the browser — no build step, no dependencies to install.

## Features

- Procedurally generated, truly infinite track — gaps, height changes, and difficulty keep coming for as long as you survive
- Speed ramps up the longer you last, so runs get progressively harder
- 1 Player or 2 Player split-screen modes, picked from the home screen
- Score tracking with a persistent per-mode high score (saved via `localStorage`)
- A different procedurally generated space backdrop (stars, nebula, planet, sun) every time you start a run

## Play

Just open `index.html` in a browser.

- **1 Player:** Strafe with A/D or Left/Right. Jump with W, Up, Space, or Enter.
- **2 Players (split screen):** Player 1 strafes with A/D and jumps with W. Player 2 strafes with Left/Right and jumps with Up.
- The track is procedurally generated and infinite — the longer you survive, the faster and harder it gets.
- Falling ends the run immediately. Your score and high score (per mode) are saved in your browser via `localStorage`.
