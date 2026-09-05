# Drawing

A light clip-board of the Are.na channel [Drawings](https://www.are.na/deen/drawings-37mwydwa-8a).

- Site: https://drawings.deeeen.xyz
- Fallback: https://gundaif.github.io/drawing/

Written as markdown. Served as one small HTML file.

- `index.md` — the page
- `_data/drawings.yml` — the sheets
- `_layouts/default.html` — the frame
- `index.html` — the built board (what GitHub Pages serves)

No runtime Are.na fetch. No libraries. Click a sheet to take the clip off. Clip it back to return.

To pin a new drawing, add a block to `_data/drawings.yml` (and rebuild `index.html`).
