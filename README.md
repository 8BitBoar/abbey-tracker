# Abbey Tracker

A small offline-capable web app for tracking the whale shark abbey's systems, arrays, and roster.

## Files
- `index.html`: the app
- `manifest.webmanifest`: app name, icon, and full-screen settings
- `sw.js`: offline support
- `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`: app icons
- `icon.svg`: source drawing for the icons

## Updating
When you upload a new `index.html`, change `VERSION` at the top of `sw.js` (for example `abbey-tracker-v2`) so phones pick up the new version.

## Data
Data is saved on each device separately. Use **Export backup** / **Import backup** to move it between devices or keep a safe copy.
