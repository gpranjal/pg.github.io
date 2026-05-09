# pg.github.io

Personal site at [pg.github.io](https://pg.github.io). Static HTML/CSS, no framework.

## Design system

This site is the first real application of my personal design system at [`../design/`](../design/) (sibling repo). See `../design/DESIGN.md` and `../design/principles.md` for the source of truth.

## Build

```bash
bun build-tokens.mjs   # regenerates tokens.css from ../design/tokens.json
python3 -m http.server 8000   # local preview at http://localhost:8000
```

`tokens.css` is generated; do not edit by hand. Edit `../design/tokens.json` and re-run the build.
