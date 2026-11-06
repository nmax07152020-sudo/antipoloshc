# Antipolo SHC Client Visit PWA

## GitHub / Vercel deployment
1. Upload the **contents** of this folder to the root of your GitHub repository.
2. In Vercel, import that repository.
3. Framework Preset: Other.
4. Build Command: leave blank.
5. Output Directory: `.` (root).
6. Deploy.

## App icon / PWA
- `assets/icon-192.png` — Android icon
- `assets/icon-512.png` — Android icon / maskable icon
- `assets/apple-touch-icon.png` — iOS Add to Home Screen
- `manifest.json` — PWA metadata
- `service-worker.js` — app shell caching

## Important
The current index.html is still the visual/local prototype. It is not yet connected to Google Sheets.
Do not enter real patient information until the secure Google Apps Script backend, authentication, access controls, and privacy protections have been implemented and tested.
