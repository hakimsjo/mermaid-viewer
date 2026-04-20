# Mermaid Viewer

A lightweight Mermaid diagram viewer built with plain HTML, CSS, and JavaScript.

This app runs directly from a local file and does not require Node.js, npm, or a web server.

## Features

- Paste Mermaid code and render instantly
- Zoom in and out with mouse wheel or buttons
- Pan the diagram by dragging
- Reset view
- Fullscreen toggle
- Export rendered diagram as SVG
- Light and dark mode toggle with saved preference
- Responsive layout for desktop and mobile

## Project Structure

- `index.html` - Main app (UI, styles, and logic)
- `lib/mermaid.min.js` - Local Mermaid library bundle
- `favicon.svg` - App icon

## Run Locally

1. Clone or download this repository.
2. Open `index.html` in your browser.

That is all. No build step is required.

## Usage

1. Paste Mermaid code into the editor on the left.
2. Click **Render** (or press **Ctrl+Enter**).
3. Use the controls in the diagram panel:
   - **In / Out** for zoom
   - **Reset** to center and reset scale
   - **SVG** to download
   - **Expand** for fullscreen
4. Use the theme button in the code panel to switch light/dark mode.

## Keyboard Shortcuts

- `Ctrl+Enter` (or `Cmd+Enter` on macOS): Render diagram
- `Esc`: Exit fullscreen

## Notes

- The app is optimized for local usage (`file://`).
- Mermaid rendering is done client-side in the browser.
- If your diagram does not render, check Mermaid syntax in the editor.

## License

Add your preferred license here (for example MIT).
