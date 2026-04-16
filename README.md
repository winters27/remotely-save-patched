# Remotely Save (Patched) — Total Pro Unlock

This repository contains a surgically patched version of the [Remotely Save](https://github.com/remotely-save/remotely-save) Obsidian plugin. It unlocks all premium features and removes artificial restrictions, providing a fully unrestricted synchronization experience for all cloud providers.

## 🔓 Unlocked Features

- **Total Service Unlock**: Native support for pCloud, OneDrive (Full), Google Drive, Box, Yandex Disk, Koofr, and Azure Blob Storage without a PRO subscription.
- **Permanent Sync**: Bypasses the `checkProRunnable` gate, allowing sync execution for all providers.
- **No Expiration (Anti-Timebomb)**: Removes the `credentialsShouldBeDeletedAtTimeMs` logic that artificially expires tokens after 80 days.
- **UI Decoupling**: Removes the "!!PRO!!" warning labels and de-bloats the settings menu for a clean, professional aesthetic.

## 📂 Repository Structure

- **`PC-Version/`**: Targeted for Obsidian Desktop (Windows/macOS/Linux). 
  - *Plugin ID:* `remotely-save-custom`
  - *Why:* Uses a custom ID to live side-by-side with the official plugin if desired.
- **`Mobile-Version/`**: Targeted for Obsidian Mobile (iOS/Android).
  - *Plugin ID:* `remotely-save`
  - *Version:* `9.9.99`
  - *Why:* Uses the original ID to maintain internal protocol handlers required for mobile stability, but uses a version bump to prevent Obsidian from auto-updating it back to the official gated version.

## 🚀 Installation Guide

### Mobile (iOS/Android)
1. Navigate to your vault's `.obsidian/plugins/` directory.
2. Create a folder named **`remotely-save`**.
3. Copy all files from the [Mobile-Version](./Mobile-Version/) folder into it.
4. Restart Obsidian on your device.
5. Enable the plugin in **Settings > Community Plugins**.

### Desktop (PC/Mac/Linux)
1. Navigate to your vault's `.obsidian/plugins/` directory.
2. Create a folder named **`remotely-save-custom`**.
3. Copy all files from the [PC-Version](./PC-Version/) folder into it.
4. Restart Obsidian.
5. Enable the plugin in **Settings > Community Plugins**.

## ⚙️ Shared Sync Setup
To ensure your Desktop and Mobile devices sync to the same remote folder:
- Open the plugin settings on **both** devices.
- Ensure the **Remote Folder Name** (under pCloud/OneDrive/etc settings) is identical (e.g., `MyNotes`).

---
*Disclaimer: This is a community-patched version intended for self-hosting and research. Use at your own risk.*
