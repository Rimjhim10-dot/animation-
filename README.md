# Into the Void

Into the Void is a single-file generative motion tool for creating looping visuals to accompany music. It draws animated radial lines on a 2D canvas, with a warm, high-contrast palette inspired by the supplied reference artwork.

**Designed by Rimjhim**

## Preview

### Artwork

![Into the Void animated artwork](screenshots/artwork.png)

### Controls

![Into the Void controls](screenshots/controls.png)

## Run locally

Open `index.html` directly in a modern desktop browser. No server, dependencies, build step, or network access is required.

## Controls

- Adjust the center position, wave shape, line count, line width, animation speed, and rotation with the sliders.
- Choose a line style, canvas aspect ratio, line colors, and background color.
- Move the origin with the pointer, or click the canvas to set it; turn off **Move origin with cursor** to use the X/Y sliders alone.
- **Space** pauses or resumes; **R** randomizes the sliders; **S** saves a PNG; **V** records a five-second video; **H** hides or shows the panel.
- When a recording finishes, select **Save video** in the panel to download it. The file format depends on browser support (MP4 when available, otherwise WebM).

## Project files

- `index.html` — the complete app: HTML, CSS, JavaScript, and canvas animation.
- `screenshots/` — preview images for the README.

There are no external runtime dependencies.
