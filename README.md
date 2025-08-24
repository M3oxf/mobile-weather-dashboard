# Mobile Weather Dashboard (PWA)

Single-file HTML weather dashboard using the free Open‑Meteo API. Works on mobile, supports dark mode, hour selector, swipe day change, and can be installed as a PWA.

## Files
- `index.html` — the app
- `manifest.webmanifest` — PWA manifest
- `sw.js` — service worker for offline shell

## Local test
```bash
python -m http.server 8000
# then open http://localhost:8000/
```

## Update notes
When you change files and want existing installs to pick up the update, bump the `CACHE` value in `sw.js` (e.g. `mw-v2`) and re‑deploy.
