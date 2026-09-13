# LaunchDock

> **A sleek, modern glassmorphic floating application launcher for Windows.**  
> Keep your desktop clean, organize your software and files into custom categories, and launch anything instantly with zero friction.

---

## 🌟 Overview

**LaunchDock** is a lightweight, unobtrusive desktop dock that rests seamlessly at the top center of your primary screen. It remains as a compact, elegant pill until you hover over it, expanding into a rich, dark glassmorphic command center for all your daily apps, files, folders, and web shortcuts.

Designed specifically for Windows with high attention to visual polish, responsive animations, and physical desktop usability.

---

## ⬇️ [Download](https://github.com/beingmahdi/LaunchDock/releases/tag/v1.0.1)

---

## 🚀 Installation

1. Download **`LaunchDock-Setup.exe`** from [Releases](https://github.com/beingmahdi/LaunchDock/releases/tag/v1.0.1)
2. Run the installer.
3. Choose your desired installation folder (defaults to your local programs directory) and choose whether to create a Desktop shortcut.
4. Click **Install LaunchDock** and enjoy the showcase presentation while the installation completes.
5. Click **Launch LaunchDock** to start immediately.

> [!NOTE]
> **Windows SmartScreen Notice**: Because LaunchDock is an independent open-source release without an expensive corporate EV code-signing certificate, Windows Defender SmartScreen may display a blue *"Windows protected your PC"* prompt on first launch. Click **More info** and then **Run anyway** to proceed.

---

## 🖼️ Screenshots
![Pills](https://github.com/beingmahdi/LaunchDock/blob/main/screenshots/LaunchDock_Pills.png)
![Panel](https://github.com/beingmahdi/LaunchDock/blob/main/screenshots/LaunchDock_Panel_Expanded.png)
![Settings](https://github.com/beingmahdi/LaunchDock/blob/main/screenshots/LaunchDock_Settings.png)
---

## ✨ Key Features

- **Pill & Expandable Dock**: Sits tucked away at the top edge of your monitor; smoothly expands on hover and collapses when your cursor moves away.
- **Pin & Lock Mode**: Click the pill handle to lock the launcher panel open while you work or organize.
- **Drag & Drop Adding**: Drag `.exe` files, shortcuts (`.lnk`), documents, and folders directly from Windows Explorer into the dock.
- **Custom Categorization**: Organize your items with customizable category tabs (e.g., *Dev*, *Games*, *Productivity*, *Media*, *Tools*).
- **Fast Search & Filter**: Instantly search across all your pinned apps and files with keyboard navigation (`Enter` to launch, `Esc` to clear/collapse).
- **Smart Relocation**: If an application or file is moved or renamed, LaunchDock lets you quickly relocate the broken path without re-adding it.
- **Context Menu Actions**: Right-click any item to open file location, edit properties, relocate missing target, or remove.
- **Customizable Appearance**: Fine-tune panel width, icon size, animation speed, accent color, and opacity via the integrated Settings menu.
- **Windows Auto-Start**: Optionally launch LaunchDock silently at Windows boot.

---

## 📖 User Guide

### 1. First Launch & The Pill
Upon startup, LaunchDock docks at the top center of your main screen as a subtle, translucent pill:
- **Expand**: Move your mouse pointer over the pill. The panel expands downward smoothly.
- **Collapse**: Move your mouse pointer away from the panel onto the desktop or another window.
- **Pin Open**: Click the pill handle to pin LaunchDock open. A violet accent indicator will illuminate. Click again to unpin.

### 2. Adding Apps, Files, and Folders
You can add items to LaunchDock using two quick methods:
- **Drag and Drop**: Drag any file, application executable, or folder from Windows Explorer and drop it directly onto the expanded LaunchDock panel or category area.
- **Add Item Button**: Click the `+` button in the launcher header to manually select a target file or executable and specify a custom display name.

### 3. Creating & Managing Categories
Categories help keep your workspace tidy:
- Click the **Manage Categories** icon (or access via Settings) to add, rename, reorder, or delete tabs.
- When an item is dragged into a specific category tab, it is automatically assigned to that category.
- The **All** tab always displays your full collection.

### 4. Relocating Missing Items
If an external drive is disconnected or you move an executable to a new directory, LaunchDock highlights the item with an indicator:
- Right-click the missing item.
- Select **Relocate Target...** from the context menu.
- Select the new file location. LaunchDock immediately updates the target path and restores the icon.

### 5. Removing Items Safely
- Right-click any app or file card and select **Remove from LaunchDock**.
- Removing an item only deletes the launcher shortcut; your original files, folders, and applications are **never** deleted from your system.

### 6. Settings & Customization
Click the **Gear** icon in the launcher panel to customize:
- **Accent Color**: Personalize your launcher glow and highlight color.
- **Panel Width & Icon Size**: Tailor the dock layout to your monitor dimensions.
- **Glass Opacity**: Adjust background translucency.
- **Animation Speed**: Set expand/collapse transition duration to your preference.
- **Auto-Start**: Toggle whether LaunchDock starts automatically on Windows boot.

---

## 📂 Data Storage

LaunchDock stores all user settings, categories, and item lists safely in your standard Windows Application Data folder:

```
%APPDATA%\launchdock-data\floating-launcher-data.json
```

- **Upgrades**: Running a newer version of the installer preserves your items and configurations automatically.
- **Backups**: You can easily back up your launcher setup by copying `floating-launcher-data.json`.

---

## 🗑️ How to Uninstall

If you ever wish to uninstall LaunchDock:
1. Open Windows **Settings** > **Apps** > **Installed apps** (or Windows Control Panel > **Programs and Features**).
2. Find **LaunchDock** in the list and click **Uninstall**.
3. Follow the uninstallation prompts.

The uninstaller removes all application files and shortcuts cleanly. Your custom launcher configuration in `%APPDATA%` is preserved by default so your items remain intact if you ever reinstall.

---

## ❓ FAQ & Troubleshooting

- **The launcher isn't opening on mouse hover**:  
  Ensure LaunchDock is running in the background. If you previously closed it, launch it again from your Start Menu.
- **Windows SmartScreen blocked the installer**:  
  Click **More info**, then select **Run anyway**. This is standard for independent open-source software that lacks an enterprise code-signing certificate.
- **My pinned application doesn't open**:  
  Check if the target application was moved or uninstalled. Right-click the item and select **Relocate Target...** to choose its current path.
- **The dock is behind my full-screen game or video**:  
  By default, LaunchDock operates at desktop level to avoid interrupting full-screen applications. Hover over the top-center edge or pin the launcher if you want it to remain on top.

---

## 👨‍💻 Developer & Credits

**Developed by**: Mahdi Hasan AKA Colonelx  
**License**: MIT License  
**Copyright**: © 2026 Mahdi Hasan AKA Colonelx. All rights reserved.