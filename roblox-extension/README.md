# Roblox Blank Extension

This directory contains a minimal Chrome extension configured to run on pages within the Roblox domain. The extension is intentionally blank so you can build functionality on top of it.

## Files

- `manifest.json` – Declares the extension metadata and loads the placeholder content script on any `roblox.com` page.
- `content.js` – An empty script where you can add Roblox-specific logic in the future.

## Loading the Extension

1. Open Chrome and navigate to `chrome://extensions/`.
2. Enable **Developer mode** in the top-right corner.
3. Click **Load unpacked** and select this `roblox-extension` folder.
4. Visit [roblox.com](https://www.roblox.com) to verify the extension loads.

You're now ready to start customizing the extension.
