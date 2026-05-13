# Newspaper Builder — Quick Start

Two static HTML files that work together to design and fill newspaper layouts.

## Files
- `editor.html`    — Preset Editor (design your layout)
- `generator.html` — Newspaper Generator (fill and export)
- `style.css`      — Shared styles (must stay in same folder)

## Workflow

### 1. Design a Layout (editor.html)
1. **Upload a background** — drag/drop or click the upload zone (JPG/PNG newspaper page scan or blank paper).
2. **Draw frames** — select the Image or Text tool, then click-and-drag on the canvas to create frames. Use Select tool to move/resize.
3. **Set properties** — select a frame and edit font, size, alignment (text frames) in the right panel.
4. **Save Preset** — click "Save Preset", name it, download the JSON. Also downloads the background image separately.
5. Place both files in the same accessible folder.

### 2. Fill the Layout (generator.html)
1. **Load Preset** — upload the JSON file from step 1.
2. **Load Background** — upload the background image file.
3. **Add images to library** — drag or upload images into the image library (left panel).
4. **Fill image frames** — drag images from the library onto image frames on the canvas, or click a frame to browse.
5. **Fill text frames** — click any text frame and type directly.
6. **Adjust text** — select a text frame and adjust font, size, bold/italic, color in the right panel.
7. **Export** — click Export, choose PNG or JPG, scale, and download.

## Keyboard Shortcuts (Editor)
- `S` — Select/Move tool
- `I` — Image frame tool  
- `T` — Text frame tool
- `D` — Duplicate selected frame
- `Delete / Backspace` — Delete selected frame
- `Esc` — Deselect

## Tips
- Enable Snap-to-Grid for precise alignment (default: 20px grid)
- Use 2× or 3× export scale for print-ready output
- The JSON preset stores all layout data; background image is separate
- Frames can be layered — later frames appear on top in the list

## Folder Structure (recommended)
```
/newspaper-builder/
  editor.html
  generator.html
  style.css
  /presets/       ← save your JSON files here
  /images/        ← your content images
  /exports/       ← downloaded exports land here (browser default)
```
