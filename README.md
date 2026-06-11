# Playground

A collection of interactive creative-coding toys, hosted with GitHub Pages. The landing page is a minimal index in pure blue and white; each toy lives in its own folder.

**Live:** https://janetcheng0311.github.io/Bubble-/

## Toys

- **[Bubbles](bubbles/)**: realistic soap bubbles with iridescent rim film and organic wobble. Pop them by tap or swipe, style them with sliders and presets, upload a background photo and rope off where bubbles appear.
- **[Flow](flow/)**: generative flow-field line art. Tap to grow a field from a point, tweak line count and swirl, save the result as a PNG.

## Adding a new toy

1. Create a folder, e.g. `sparks/`, with its own `index.html` (self-contained, no dependencies).
2. Add a link to it in the root `index.html` nav list.

Everything is plain HTML/CSS/JS with zero build steps. To preview locally:

```bash
python3 -m http.server 8000
```
