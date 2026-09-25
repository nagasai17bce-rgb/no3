# Naga Sai — Scroll Driven 3D Portfolio

A single-page Three.js portfolio where the character rotates as the visitor scrolls through Home, Experience, Education, Projects, Skills and Contact. Sponsor-style logos are attached to the character's outfit so they rotate with the body.

## Run locally

Because this uses ES modules, serve the folder with any static server.

```bash
python3 -m http.server 5173
```

Open `http://localhost:5173`.

## Deploy to Vercel

Upload this folder to GitHub and import the repository into Vercel. No build command is required; `index.html` is the entry point.

## Replace the avatar

The current build uses `assets/face.png` as a face plate on a procedural 3D body. For a true photorealistic full-body 3D model, replace the procedural avatar with a `.glb/.gltf` character and keep the same scroll-state system. The sponsor patches can then be converted to GLTF decals/materials attached to the jacket, pants and backpack.

## Scroll states

- Home: front
- Experience: front → 3/4 → side for Salesforce → Walmart → Tekion
- Education: side/rear view
- Projects: rear view
- Skills: rear 3/4 / opposite side
- Contact: return toward front
