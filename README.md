# Patterium

**Seamless Pattern Studio** — a browser-based tool for designing perfectly tileable pattern tiles.

🔗 **[Live app](https://genz000.github.io/Patterium/)**

## What it does

The tile is treated as a torus: every element is drawn into the tile *and* wrapped across all 8 neighbor offsets, so anything you push over an edge reappears on the opposite side — guaranteeing a seamless repeat. A live 3×3 preview confirms the tiling before you export.

## Features

- **Upload** images (PNG · SVG · JPG) via drop zone, file picker, or drag-and-drop, plus built-in vector shapes
- **Arrange** elements freely — they wrap live across tile edges
- **Resize** with corner handles or the Scale slider
- **Rotate** with the rotor handle or the Rotation slider
- Alt-drag to duplicate; multi-select, group / ungroup, and drag-and-drop layer ordering
- Opacity, undo / redo (Ctrl+Z), center
- **Repeat modes**: Free, Grid, Half-drop, Brick
- **Auto-arrange**: grid fill or scatter
- Adjustable tile size (128–1024px), background swatches, transparent, and a free color picker
- Zoom / pan canvas
- **Export** as PNG, JPG, or SVG at a custom size

## Shortcuts

| Action | Key |
| --- | --- |
| Move element | Drag · Arrow keys (Shift = ×10) |
| Resize | Drag corner handle |
| Rotate | Drag top dot |
| Delete | `Delete` / `Backspace` |
| Zoom | Scroll wheel |

## Running locally

It's a single self-contained `index.html` — no build, no dependencies. Open it in any modern browser.

---

Built with vanilla JS + Canvas.
