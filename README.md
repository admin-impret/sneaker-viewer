# Stylized Sneaker - Interactive 3D Viewer

An original stylized 3D sneaker product model, viewable in the browser with drag-to-rotate.

- Static page using Google's `<model-viewer>` web component (loaded from CDN). No build step.
- `sneaker.glb` - glTF binary, ~59k triangles, baked 1024px textures, exported from Blender 5.2.
- Deployed on Vercel as a static site (framework preset: Other).

The model is an original design (no brand elements, no third-party assets); built procedurally
in Blender with an AI-assisted workflow (Claude Code + bpy script), textures baked in Cycles.
