# Sarat's Umbrel app store

Community app store for Umbrel with a customised WatchYourLAN.

## Install
1. On the Umbrel, once (the image is private): `sudo docker login ghcr.io -u sarat03`
   and paste a GitHub token with only the `read:packages` scope.
2. Umbrel → App Store → ⋯ → Community App Stores → add
   `https://github.com/sarat03/umbrel-apps`.
3. Open "Sarat App Store" → WatchYourLAN (Sarat) → Install. It runs on port 8841.

## Updating
New images are built on every push to the app's `main`. Bump `version` in
`sarat-watch-your-lan/umbrel-app.yml` to make Umbrel show the Update button.
