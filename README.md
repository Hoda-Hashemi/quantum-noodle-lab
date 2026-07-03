# Ink Splatter Garden

An immersive empty sketch-gallery shell. The concept frames an ADHD mind as abundance and parallel richness: many branching thoughts blooming at once, connected by associative ink paths.

The homepage contains:

- pointer/touch-driven WebGL ink field
- pan/drag garden navigation
- map mode
- calm mode
- keyboard movement between connected bloom slots
- empty bloom views ready for future drawings

## Adding Sketches Later

Replace the `slots` array in `index.html` with real metadata:

- `id`
- `title`
- `medium`
- `x` / `y` garden position
- `links` connected bloom ids
- later: add image paths/captions inside the bloom dialog

## Local Use

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

## GitHub Pages

Live URL: https://Hoda-Hashemi.github.io/quantum-noodle-lab/
