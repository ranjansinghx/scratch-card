# Scratch Surprise

This is a mobile-first scratch card web app that works on GitHub Pages.

## How it works

- The app does not use `localStorage`, `sessionStorage`, or `indexedDB`.
- All reveal images are bundled in the repository under `assets/`.
- `catalog.js` lists the image filenames.
- `index.html` loads the catalog and picks a random image at runtime.

## What to upload to GitHub

Make sure these files and folders are included in your GitHub repo:

- `index.html`
- `catalog.js`
- `assets/`
- `manifest.webmanifest`
- `icon-192.png`
- `icon-512.png`
- `apple-touch-icon.png`

## GitHub Pages setup

1. Push the repo to GitHub.
2. Open the repository settings.
3. Turn on GitHub Pages for the branch you want to publish.
4. Open the published Pages URL.

## Notes

- The app uses relative paths, so it works correctly when hosted online.
- If you later want the images loaded from an external CDN instead of the repo, the code can be changed for that too.
