# Remotely Save (Community Edition) — Extended Cloud Sync

This repository provides a community-optimized version of the [Remotely Save](https://github.com/remotely-save/remotely-save) Obsidian plugin. It is designed to offer a cohesive, unrestricted synchronization experience by enabling support for a wider range of cloud providers and simplifying the authentication lifecycle.

## ✨ Key Enhancements

- **Unified Cloud Support**: Full native support for pCloud, OneDrive (Full), Google Drive, Box, Yandex Disk, Koofr, and Azure Blob Storage.
- **Optimized Authentication**: Streamlined logic to reduce authentication overhead and ensure persistent connections for all cloud providers.
- **Extended Token Lifecycle**: Removal of the 80-day manual token renewal requirement, providing a truly permanent synchronization experience.
- **Clean Aesthetic**: A de-bloated settings interface focused on simplicity and functionality.

## 📂 Repository Structure

- **`PC-Version/`**: Optimized for Obsidian Desktop (Windows/macOS/Linux). 
  - *Plugin ID:* `remotely-save-custom`
  - *Note:* Uses a custom ID to allow side-by-side installation with official releases.
- **`Mobile-Version/`**: Optimized for Obsidian Mobile (iOS/Android) stability.
  - *Plugin ID:* `remotely-save`
  - *Version:* `9.9.99`
  - *Note:* Uses the standard ID for protocol integrity while utilizing a version-lock to maintain community-specific configuration.

## 🚀 Installation Guide

### Mobile (iOS/Android)
1. Navigate to your vault's `.obsidian/plugins/` directory.
2. Create a folder named **`remotely-save`**.
3. Copy all files from the [Mobile-Version](./Mobile-Version/) folder into it.
4. Restart Obsidian and enable the plugin in **Settings > Community Plugins**.

### Desktop (PC/Mac/Linux)
1. Navigate to your vault's `.obsidian/plugins/` directory.
2. Create a folder named **`remotely-save-custom`**.
3. Copy all files from the [PC-Version](./PC-Version/) folder into it.
4. Restart Obsidian and enable the plugin in **Settings > Community Plugins**.

## ⚙️ Universal Sync Setup
To sync multiple devices to the same remote source:
- Open the settings on **both** devices.
- Ensure the **Remote Folder Name** (under specific cloud settings) is identical across all instances.

---
*Disclaimer: This is a community-maintained version intended for self-hosting and personal productivity. Please refer to the original repository for official support.*
