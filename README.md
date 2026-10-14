# Sarat's Umbrel app store

Community app store for Umbrel with [LanLookout](https://github.com/sarat03/lanlookout),
a home network monitor.

## Install
1. Umbrel → App Store → ⋯ → Community App Stores → add
   `https://github.com/sarat03/umbrel-apps`.
2. Open "Sarat" store → LanLookout → Install. It runs on port 8841.

## Updating
Images are built on every push to LanLookout's `main`. To release one here, set the
`image:` in `sarat-watch-your-lan/docker-compose.yml` to the new commit tag and digest,
and bump `version` in `sarat-watch-your-lan/umbrel-app.yml` so Umbrel shows the Update button.
