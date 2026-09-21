# LUMENVALE — Guardians Rework v2.3

Single-file, offline-capable 2D action platformer. No build step, no API keys.

## Deploy on Render

1. Upload `index.html` and `render.yaml` to a GitHub repository.
2. Render Dashboard → New → Static Site, connect the repository.
3. Set build command: `echo "Static game ready"`; publish directory: `.`
   Or use New → Blueprint and select `render.yaml`.
4. Deploy. Render supplies the actual `*.onrender.com` URL once successful.

## Save data

Saves are stored in this browser, on this site origin, using localStorage. They do **not** transfer automatically from a local `file://` URL, another domain, or another device. Save after visiting checkpoints.