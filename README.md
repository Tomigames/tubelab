# Tube Lab

Tube Lab is a browser-based ball-sort puzzle solver. It lets you recreate any ball-sort level, solve it with a single click, and step through the shortest move sequence.

## Features

- In-browser puzzle editor for tubes, balls, and colors
- Drag and drop ball placement and tube editing
- Solve button that finds a shortest solution
- Light/Dark theme toggle
- Clean, responsive interface

## Usage

1. Open `index.html` in a web browser.
2. Use the brush palette and tube editor to build a puzzle.
3. Click **Solve** to compute the solution.
4. Step through the returned moves to see the solution play out.

## Development

This repository is currently a static frontend project with a single entry file:

- `index.html`

To update the UI or solver behavior, edit `index.html` directly in your preferred editor.

## Notes

- No build step is required.
- If you want to serve the app locally, you can use a simple static server such as `python -m http.server` in the repo folder.
