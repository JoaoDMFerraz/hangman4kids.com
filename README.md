# Hangman4Kids

Static site. Everything needed to run is in this folder.

## Publish on GitHub Pages
1. Upload the contents of this folder to your repo (either the repo root, or a `/docs` folder).
2. Repo → **Settings → Pages** → Source: *Deploy from a branch* → pick your branch and `/ (root)` or `/docs`.
3. Wait ~1 minute, then open the URL GitHub shows.

## Files
- `index.html` — the game
- `support.js` — runtime the page needs (must stay next to index.html)
- `themes-data.js` — 30 daily themes, 50 easy + 50 hard words each
- `*.png` — favicon and sponsor banner images
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Notes
- Must be served over http(s), not opened as a local `file://` page (the themes file loads as a module).
- Google AdSense and the affiliate links are already wired in `index.html`.
