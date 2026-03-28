# Woodworking Workshop Companion PWA

This bundle is ready for GitHub Pages.

## Files
- `index.html` — the app
- `manifest.webmanifest` — install metadata
- `service-worker.js` — offline caching
- `icon-192.png`, `icon-512.png` — app icons

## Deploy to GitHub Pages
1. Create a GitHub repository.
2. Upload all files from this zip to the repo root.
3. In GitHub, open **Settings → Pages**.
4. Set the source to deploy from the **main branch** root.
5. Save, then open the Pages URL after GitHub finishes publishing.

## Notes
- Project text data is stored in `localStorage`.
- Photos and PDF plans are stored in `IndexedDB`.
- The built-in export/import covers text state only. Media and PDFs stay on the current browser/device.
- The app works offline after the first successful load.
