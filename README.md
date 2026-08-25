# IMXP — Fundraise Deck

A web version of the IMXP *"Immersive Experiences at Global Scale"* fundraise deck.

The 23 published slides are exported at full resolution (1920×1080) from the source
Canva design and presented in a lightweight, self-contained slide viewer.

## View

Once GitHub Pages is enabled for this repo, the deck is live at:

```
https://<org>.github.io/<repo>/
```

## Navigation

- **← / →** (or click left / right) — previous / next slide
- **Space / Page Down** — next
- **Home / End** — first / last slide
- **F** — toggle fullscreen
- Swipe left / right on touch devices
- Deep-link to any slide with `#<n>` (e.g. `…/#7`)

## Structure

```
index.html        # self-contained slide viewer (no build step, no dependencies)
slides/           # slide-01.png … slide-23.png
.nojekyll         # serve files as-is on GitHub Pages
```

## Updating

Re-export the published slides from Canva as PNG (Pro quality), replace the files in
`slides/`, and adjust `TOTAL` in `index.html` if the slide count changes.
