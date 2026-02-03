# ABLE - A Better LaTeX Editor

A web-based LaTeX editor with a freeform canvas for creating mathematical notes. Built with MathLive.

## Features

- **Freeform Canvas**: Double-click anywhere to create draggable math boxes
- **Rich Math Shortcuts**: 100+ shortcuts for calculus, vectors, matrices, set theory, and quantum physics
- **Drawing Tools**: Pen, lines, circles, curves, and eraser for annotations
- **Arrow Connections**: Shift + drag to draw arrows between elements
- **Auto-Save**: Content automatically saved to browser storage
- **Export Options**: Save as `.able` file or export to PDF
- **Numpad Shortcuts**: Quick access to integrals (7), sums (8), roots (9), limits (4), and matrices (5)

## Usage

1. Double-click to create a math box
2. Type LaTeX shortcuts (e.g., `alpha`, `int`, `sum`, `22mat` for 2x2 matrix)
3. Drag boxes by their handle
4. Use sidebar tools for drawing
5. Press F1 for full shortcut reference

## Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| New Box | Double Click |
| Draw Arrow | Shift + Drag |
| Toggle Mode | Shift + Tab |
| Help Menu | F1 |
| Undo | Ctrl + Z |

## Tech Stack

- MathLive for math rendering
- html2canvas + jsPDF for PDF export
- Vanilla JavaScript, no build step required

## License

MIT
