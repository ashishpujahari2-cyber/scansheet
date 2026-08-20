# ScanSheet PWA

This package contains the supplied ScanSheet app prepared for GitHub Pages as an installable PWA.

## Files
- `index.html` — your app
- `manifest.json` — PWA installation metadata
- `sw.js` — offline service worker
- `icons/icon-192.png`
- `icons/icon-512.png`

## GitHub Pages
Upload all files/folders to the **root** of your repository, with `index.html` at the root.
Then enable **Settings → Pages → Deploy from branch → main → /(root)**.

Open the published HTTPS URL in Chrome on Android and use **Install app** / **Add to Home screen**.

## Updating the PWA
When you publish a new version, change the cache version in `sw.js`, for example:
`scansheet-pwa-v2`
This forces the new app shell to be cached.
