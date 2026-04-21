# Hack Lab

Two things in one repo, both themed around **Hack Lab '26** — e-conomic's internal hackathon.

## `index.html`
A neon 80s retro-futurist event landing page: animated grid + sun, CRT scanlines, glitch wordmark, live countdown to **Sept 16, 2026 08:30 CEST**, and the Hack Lab manifesto. Mobile-first, no build step.

## `hackthon-game.html`
A tiny platformer game. A Little CTO runs through an accountant office grabbing idea lightbulbs and AI coins (which give a speed boost). One level: *Hack Lab*.

### Controls
- `←` `→` move
- `Space` / `↑` jump
- `R` restart

## Run
Open either HTML file directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000/> (event page) or <http://localhost:8000/hackthon-game.html> (game).

## Credits
Design handoff from Claude Design. Assets under `assets/`.
