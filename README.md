# Crumb 1.0
A free, local-first, English-language recipe PWA.

## Publish for free (GitHub Pages)
1. Create a free GitHub account and a new public repository, for example `crumb-app`.
2. Upload `index.html`, `sw.js`, `icon.svg`, and `manifest.webmanifest` into the repository root.
3. In repository Settings > Pages, select Deploy from a branch, `main`, `/ (root)`, and save.
4. Open the generated HTTPS Pages URL in Safari on your iPhone. Use Share > Add to Home Screen.

**Privacy:** A public GitHub Pages repository exposes the app source code, but not recipes stored locally in your browser. The site URL is not access-controlled. Do not commit personal recipe data or private backups to the repository.

## Features
- Recipe add/edit/delete, ingredients, steps, tags, categories
- Favorites, Want to try / Made it, search
- Save Instagram/original URLs (no automatic extraction)
- Local browser storage (localStorage)
- JSON export/import backup
- Offline shell via service worker after first successful visit

## Limitations
- Data is per browser/origin and may be erased when clearing site data or changing devices. Export backups regularly.
- No cloud sync, account login, AI analysis, automatic Instagram import, or photo uploads.
- An optional image URL must be hosted elsewhere and may not be available offline.
- For best iPhone icon support, a PNG apple-touch-icon can be added later.


Crumb 1.1: screenshot OCR via Tesseract.js 5.1.1 CDN, performed in browser. Open Add recipe, upload images, tap Read screenshots, review, then Fill recipe fields. OCR needs internet. Replace index.html and sw.js in repository root; stored recipes are preserved.
