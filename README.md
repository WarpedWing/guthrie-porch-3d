# PBATT: Porch Blood Analysis and Timing Tool

Interactive, photo-textured, to-scale 3D model of the Guthrie front porch, with moon lighting for any minute of the night of Feb 1, 2026 (MST), and tools for measuring, tracing wheel paths and axles, and marking imprints on the floor. By WarpedWing Labs.

## Files

- `index.html` – the viewer (three.js r160, bundled in `vendor/`, no external dependencies except Google Fonts)
- `porch.glb` – the model (glTF binary, meters). Also opens in Blender, Windows 3D Viewer, macOS Preview.
- `moon.json` – moon altitude/azimuth per minute, 00:30–04:30 MST, Tucson (32.31 N, 110.94 W), computed with PyEphem
- `og.jpg` – link preview image

## Model notes

- Scale: 1 tile spacing ≈ 12.2 in.
- Porch heading 334° (door faces outward, NNW), measured from a map view; adjustable in the page.
- Ceiling height (8.6 tile spacings) and beams estimated from the doorbell view.
- Estimated: pillar depth, vase position, doorbell camera position.
- Tiles not visible in any image use a plain generic tile; stains appear only where they were photographed.

## Local preview

`python3 -m http.server` in this folder, then open <http://localhost:8000>
