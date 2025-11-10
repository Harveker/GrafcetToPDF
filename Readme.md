# Grafcet Editor (grafcet.html)

A small interactive Grafcet (SFC) sample implemented as an HTML file. grafcet.html contains the UI and logic to display and edit Grafcet elements (steps, transitions, actions) using the GoJS diagramming library.

## What this file does
- Renders an interactive Grafcet diagram in the browser.
- Supports creating, editing and connecting steps and transitions.
- Provides basic layout, styling and simple interaction handlers suitable as a starting point for customization.

## Files
- grafcet.html — the single-page demo containing HTML, CSS and JavaScript for the Grafcet editor.
- README.md — this file (overview, how to run, credits).

## How to run
1. Place grafcet.html (and any local dependencies such as go.js if used locally) in a web-accessible folder.
2. Open grafcet.html in a modern browser (Chrome, Edge, Firefox).
3. If loading GoJS from a CDN, ensure an internet connection. For offline use, include the go.js script bundle in the same folder and update the script tag accordingly.

## Customization tips
- Modify node and link templates in the JavaScript to change appearance and behavior.
- Hook into diagram events to add persistence, export/import, or custom tools.
- Use GoJS documentation and samples to add features like palettes, palettes, layouts and undo/redo.

## Credits
- Diagramming engine: GoJS — Northwoods Software. GoJS is a third-party commercial library; consult its website and license for terms and attribution requirements.
- Sample code and UI patterns: adapted from public GoJS samples and example code. Retain any original headers and attributions from those samples when redistributing.
- This repository’s Grafcet-specific code: original work unless otherwise noted in file headers.

## License & attribution
- Respect the GoJS license for use, distribution and attribution. If you adapted code from a specific GoJS sample, keep the original sample header and author attribution as required.
- For project-specific licensing, add a LICENSE file describing how this repository may be used.

If you want, I can:
- Generate a more detailed README with example screenshots and code snippets.
- Add a sample package.json or an offline bundling approach for GoJS.
- Produce a minimal LICENSE template for this repository.
