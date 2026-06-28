# Fireworks Over Vince's Castle 🎆

A single-file browser fireworks game for America's 250th. Real castle photo as a
full-bleed background — tap anywhere to launch a firework that arcs up and bursts.
Two swappable scenes (lawn + water with reflections) and a **FINALE** button that
spells out **250** in the sky.

## Run it

Just open `index.html` in any browser. No server, no build step, no dependencies.

## Add the photos

Drop two images next to `index.html`:

- `castle-lawn.jpg` — the lawn hero shot
- `castle-water.jpg` — the water view

Until they're added, the game runs on a twilight-gradient fallback. Export both at
the **same aspect ratio** with the horizon at a **similar height** so switching
scenes doesn't make the launch points jump.

## Controls

- **Tap / click anywhere** — launch a firework (works on mouse + touch, multi-tap supported)
- **🏰 Lawn / 🌊 Water** — switch the background scene (crossfade)
- **FINALE 🎆** — spell "250" in the sky
- **Ambient** — toggle the gentle auto-launching fireworks
- **🔇 Mute** — optional WebAudio pop on each burst (off by default)

The HUD auto-hides after a few seconds and reappears on tap or mouse-move.

## Hosting on GitHub Pages

This repo is ready for GitHub Pages. After pushing:

1. Go to the repo's **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Pick branch **`main`** and folder **`/ (root)`**, then **Save**.
4. Wait ~1 minute — your game will be live at
   `https://jimmyardis.github.io/castle-fireworks-250/`.

Because everything is inline and relative-pathed, it works identically on Pages and
from a local `file://` open.
