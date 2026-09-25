# Naga Sai — 3D Interactive Portfolio

A static Vercel-ready portfolio with a Three.js interactive 3D portrait. The portrait is built from the supplied photo/stylized render and wrapped on a 3D head shell; career/project stickers are positioned on the face and rotate with it.

## Run locally

Because the page imports Three.js from jsDelivr, use a local static server rather than opening the HTML directly:

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173

## Deploy

Upload the folder to GitHub and import the repository into Vercel. No build command is required; `index.html` is the entry point.

## Interaction

- Scroll to Work / Education / Projects to change the active 3D sticker set.
- Click a company/project chapter to rotate the head to its angle.
- Drag the 3D portrait horizontally to rotate it manually.
- Work mode shows Salesforce, Walmart and Tekion stickers.
- Education mode shows BITS Goa.
- Projects mode shows RAG, Voice AI and MCP stickers.
