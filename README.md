# plasma-looks

The GitHub Pages site for **Plasma**, a music visualizer for Fire TV created by Geezi Creations.

- `manifest.json`: the live, signed Look Pack manifest the app reads. It only changes when an approved pack is promoted.
- `update.json`: the live, signed app-update manifest. It also only changes on promotion.
- `packs/`: approved Look Packs.
- `preview/`: packs staged for approval. Each has stills and short clips. The app never reads anything in `preview/`.
