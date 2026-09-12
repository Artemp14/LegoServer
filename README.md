# Custom Eaglercraft Client Template

A clean template for hosting an EaglercraftX web client. 

## Deployment Instructions

1. **Upload to GitHub**: Create a new repository and upload `index.html` and `README.md`.
2. **Enable GitHub Pages**: Go to **Settings -> Pages**, set the source to the `main` or `master` branch, and click **Save**.
3. **Configure Custom Assets**: Open `index.html` in a text editor to update the default server list or change embedded base64 assets.

## How to Customize Graphics & Servers

- **High-Res Packs**: Upload custom `.zip` resource packs via the in-game menu (`Options -> Resource Packs`).
- **Multiplayer**: Connect to multiplayer via WebSocket proxies (`wss://`). Change pre-loaded servers inside the `<script>` array in `index.html`.
