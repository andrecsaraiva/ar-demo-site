# TRR Fake Structured - V8 Publish Ready

This package includes:

- Main desktop product page: `index.html`
- Separate mobile AR page: `ar-view.html`
- QR code on the desktop page that points automatically to `ar-view.html` on the same published site
- Legacy pinned 3D viewer stack on the desktop page
- Simple and robust AR stack on the AR page

## Files you must add

### Desktop + AR
- `assets/models/relogio.glb`

### iPhone / iPad AR
- `assets/models/relogio.usdz`

If you do not add `relogio.usdz`, iPhone/iPad AR will not work.

## Local desktop test
Run:
python -m http.server 8000

Then open:
http://localhost:8000

## Easiest free publishing option
Use GitHub Pages.

You will publish this whole folder, including:
- `index.html`
- `ar-view.html`
- `.nojekyll`
- the folders `css`, `js`, and `assets`

## Important
The QR code only works for other people after the site is published to a public HTTPS URL.
