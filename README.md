# Mermaid Viewer

A lightweight Mermaid diagram viewer built with plain HTML, CSS, and JavaScript.

This app runs directly from a local file and does not require Node.js, npm, or a web server.

**[Try Mermaid viewer live →](https://htmlpreview.github.io/?https://github.com/hakimsjo/mermaid-viewer/blob/master/index.html)**

## Features

- Paste Mermaid code and render instantly
- Zoom in and out with mouse wheel or buttons
- Pan the diagram by dragging
- Reset view
- Fullscreen toggle
- Export rendered diagram as SVG
- Light and dark mode toggle with saved preference
- Save Mermaid code to localStorage
- Open and delete saved diagrams from localStorage
- Automatically opens the most recently used saved diagram
- Responsive layout for desktop and mobile
- Resizable split between editor and viewer on desktop
- Quick toggle to expand the editor panel

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
4. Use **Expand editor** in the left panel to focus on editing.
5. Drag the divider between panels (desktop) to change the editor/viewer proportions.
6. Use the theme button in the code panel to switch light/dark mode.
7. Use the save tools under the editor:
   - Enter a name and click Save
   - Select a diagram and click Open
   - Select a diagram and click Delete

## Keyboard Shortcuts

- `Ctrl+Enter` (or `Cmd+Enter` on macOS): Render diagram
- `Esc`: Exit fullscreen

## Notes

- The app is optimized for local usage (`file://`).
- Mermaid rendering is done client-side in the browser.
- If your diagram does not render, check Mermaid syntax in the editor.


