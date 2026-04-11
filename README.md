# ARC Coral Facility - Download Page

GitHub Pages site for distributing the ARC Coral Facility app.

## Structure

- `index.html` — Redirects to download page
- `download-admin.html` — Password-protected download page with Android/iOS/Desktop links
- `manifest.plist` — iOS OTA install manifest
- `app/` — PWA build (deployed via `build_pwa.sh` in coral-facility-app)

## Setup

1. Create a GitHub repository: `nature-seychelles-arc-app`
2. Enable GitHub Pages (Settings → Pages → Deploy from branch: `main`)
3. The download page will be at: `https://jessicanasica.github.io/nature-seychelles-arc-app/`

## Passwords

- **Download page:** `arcfacility`
- **Desktop PWA:** `arcfacility1234`

> Replace the placeholder hashes in `download-admin.html` with the actual SHA-256 hashes (logged to console on first load).

## Updating

The PWA is deployed by running `./build_pwa.sh` from the `coral-facility-app` project.
