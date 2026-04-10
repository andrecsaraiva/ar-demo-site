# How to publish this for free on GitHub Pages

This guide assumes you are a beginner.

## What you need
- A GitHub account
- This project folder extracted on your computer
- Your files copied into:
  - `assets/models/relogio.glb`
  - `assets/models/relogio.usdz` (for iPhone/iPad AR)

## Step 1 — Create a GitHub account
Create a GitHub account if you do not already have one.

## Step 2 — Create a new repository
Create a new repository.

Recommended name:
`ar-demo-site`

It can be public.

## Step 3 — Upload the files
Open the repository.
Use the option to upload files.
Upload everything from this project folder:
- `index.html`
- `ar-view.html`
- `.nojekyll`
- the folders `css`, `js`, and `assets`

## Step 4 — Enable GitHub Pages
Inside the repository:
- go to **Settings**
- click **Pages**
- in **Build and deployment**, choose **Deploy from a branch**
- choose branch **main**
- choose folder **/ (root)**
- click **Save**

## Step 5 — Wait for the URL
GitHub will generate a public URL like:
`https://YOUR-USERNAME.github.io/ar-demo-site/`

Your pages will be:
- Main page:
  `https://YOUR-USERNAME.github.io/ar-demo-site/`
- AR page:
  `https://YOUR-USERNAME.github.io/ar-demo-site/ar-view.html`

## Step 6 — Test the desktop page
Open the main URL on your computer.

The QR code on the desktop page will automatically point to:
`/ar-view.html`

## Step 7 — Test on your phone
Open the AR page directly on your phone, or scan the QR code from the desktop page.

## Notes
- Desktop 3D should work with the GLB.
- Android AR uses WebXR or Scene Viewer.
- iPhone/iPad AR uses Quick Look and needs the USDZ file.
