# Infinite Platformer

A 3D infinite-runner platformer built with [Three.js](https://threejs.org/), playable directly in the browser — no build step, no dependencies to install.

## Play

Just open `index.html` in a browser, or play it live once deployed to GitHub Pages (see below).

- **1 Player:** Strafe with A/D or Left/Right. Jump with W, Up, Space, or Enter.
- **2 Players (split screen):** Player 1 strafes with A/D and jumps with W. Player 2 strafes with Left/Right and jumps with Up.
- The track is procedurally generated and infinite — the longer you survive, the faster and harder it gets.
- Falling ends the run immediately. Your score and high score (per mode) are saved in your browser via `localStorage`.

## Deploying to GitHub Pages

This repo is a single static `index.html` file, so GitHub Pages can serve it with no build process.

1. Push this repo to GitHub (see commands below).
2. On GitHub, go to your repo's **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Set **Branch** to `main` and the folder to `/ (root)`, then **Save**.
5. GitHub will give you a URL like `https://<your-username>.github.io/<repo-name>/` — that's your live game.

### Pushing this repo to GitHub

```bash
# Create a new repo on github.com first (without a README/license, since this repo already has one),
# then run:
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```
