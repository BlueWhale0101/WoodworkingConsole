# Woodworking Workshop Companion PWA

This package is ready for GitHub Pages deployment.

## Files
- `index.html` — the app
- `manifest.webmanifest` — install metadata
- `service-worker.js` — offline caching
- `icons/` — app icons

## Deploy to GitHub Pages
1. Create a GitHub repository.
2. Upload all files from this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose your main branch and the **/(root)** folder, then save.
6. After GitHub Pages publishes, open the site over HTTPS.

## Notes
- The app works offline after the first successful load.
- Browser data and media stay on the device in local storage and IndexedDB.
- Export/import remains the best way to move data between devices or back it up.
