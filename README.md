# WTS — 2D Wind Tunnel Simulator

A single-file, browser-based 2D wind tunnel prototype for GitHub Pages.

## Run locally
Open `index.html` in a modern browser.

## Publish with GitHub Pages
1. Create a GitHub repository (for example, `flowlab`).
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site.

## Controls
- **Line source:** click and drag. Air blows in the drag direction.
- **Point source:** click to create outward-radiating airflow.
- **Free draw / Rectangle / Circle:** create solid obstacles.
- **Select:** click and drag sources or obstacles to move them.
- **Erase:** click an item to delete it.
- Adjust source speed, viscosity, density, and strength in the right panel.
- Switch between particles, streamlines, velocity map, and pressure map.

## Important physics note
This is a first working prototype with a lightweight grid-based flow approximation, particle advection, viscosity-like diffusion, and an approximate pressure projection. It is intended for experimentation and visualization, not for validated aerodynamic measurements or engineering design. The density control is currently a displayed physical parameter and does not yet alter the solver. Free-drawn obstacles are represented as solid strokes rather than filled enclosed regions.
