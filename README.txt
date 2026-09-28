VERTASCAN Concepts | ARTIC SNOWFLY

Open the published application for direct use on desktop or mobile.
For self-hosting, upload this folder to a static HTTP/HTTPS host.
For local use, run: python -m http.server 8080
Then open http://localhost:8080 on that same computer.
Opening index.html directly from a file manager is not supported by browser module security.
All dependencies and the original FBX are bundled; no CDN is required.

CONTROLS
Drag to orbit, pinch/scroll to zoom, right drag to pan.
Choose a fixed orthographic view for distortion-free inspection.
Click an object or choose it from the inspection menu. Isolate / Show all controls visibility.
Exploded separation offsets the 14 original meshes; joined body features remain together.
Section cut opens the surface without inventing internal engineering.
Export view saves a labeled PNG. Export elevation sheet generates six current-state projections.
The projection gallery includes eight pre-rendered material-color plates. Click a plate to download.
Regenerate gallery uses the current configuration and available textures.

MODEL & LIMITATIONS
Original model: source/artic SLIEGH.fbx in supplied arctic-snowfly.zip.
14 meshes, 644,880 triangles. Original model hierarchy is flattened for object-level inspection.
Model proportions are preserved; working viewport length normalized to 12 units, not meters.
Front is the pointed fairing, positive model Z. Top is positive model Y.
The FBX references three textures absent from the supplied archive: nike texture.jpg,
scifipanel2.jpg, pbr-tileable-sci-fi-panel-textures-with-wires-3d-model-low-poly.jpg.
These receive neutral fallback textures. The camo filename is remapped to the supplied file.
Other supplied textures are included unchanged. Static plates show material colors, not textures.
Materials are converted to adjustable real-time standard shading for the presentation.
This is a concept visualization, not a validated CAD/manufacturing or engineering model.
Performance depends on device GPU; approximately 645,000 triangles are displayed.
JavaScript syntax, dependency paths, and source model parsing checked; browser runtime QA
was unavailable in the production environment.

Third-party renderer: Three.js, MIT license included in vendor/LICENSE.txt.
