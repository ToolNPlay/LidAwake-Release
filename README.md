<div align="center">

# ☕ LidAwake
### Modern Windows-Style Keep-Awake & Closed-Lid Processing Suite for macOS

**Developed by [ToolNPlay.com](https://ToolNPlay.com) • Author: Pardeep Kumar (Lead Software Engineer & Architect)**

[![macOS](https://img.shields.io/badge/macOS-13.0%2B-blue?logo=apple)](https://ToolNPlay.com)
[![Version](https://img.shields.io/badge/Release-v1.0.0-green.svg)](https://github.com/ToolNPlay/LidAwake-Release/releases/latest)
[![License: Freeware](https://img.shields.io/badge/License-Freeware%20%2F%20Closed%20Source-orange.svg)](https://ToolNPlay.com)

---

### [📥 Download LidAwake v1.0.0 (.dmg)](https://github.com/ToolNPlay/LidAwake-Release/releases/latest/download/LidAwake.dmg)
*Compatible with macOS Ventura, Sonoma, and Sequoia (Apple Silicon M1/M2/M3/M4 & Intel)*

---

</div>

## ✨ Key Features

- **🛡️ Closed-Lid Clamshell Mode:** Keep your computational scripts, 3D renders, video exports, code builds, and servers running uninterrupted even when you shut your MacBook lid on battery power.
- **🌑 Instant Display Blackout (`⌘⇧D`):** Press `⌘⇧D` or click "Display Off" to immediately turn off your screen to save battery and display lifespan while CPU and GPU processing stays 100% active.
- **🎯 App Watcher Auto-Sleep:** Keep your Mac awake while a selected application runs (*Xcode*, *Blender*, *Final Cut Pro*, *Terminal*, *Chrome*). Once that app finishes and closes, LidAwake safely restores sleep.
- **📥 Active Download Tracker:** Automatically monitors `~/Downloads` for ongoing browser downloads (`.crdownload`, `.download`, `.part`). Stays awake until all downloads complete, then safely sleeps.
- **⏱️ Quick Presets & Custom Timers:** Instant presets (`15m`, `30m`, `1h`, `2h`, `3h`, `4h`), custom hours and minutes steppers, or "Until Time of Day" clock picker.
- **⚡ Zero Password Standard Usage:** Normal keep-awake sessions communicate directly with macOS native IOKit power assertion APIs without requiring sudo, passwords, or administrative dialogs.
- **🪫 Low Battery Auto-Guard:** Built-in battery guard automatically halts keep-awake sessions if battery drops below your safety threshold (default 10%) so you never wake up to an unbootable Mac.
- **⚡ Menu Bar Companion:** Right-click the menu bar icon for quick actions and preset timers; left-click to open the full interactive Sequoia glass control deck.

---

## 🚀 How to Install & Open (First Time Setup)

Because LidAwake is distributed freely outside the Mac App Store:

1. **Download** the latest [`LidAwake.dmg`](https://github.com/ToolNPlay/LidAwake-Release/releases/latest/download/LidAwake.dmg) installer.
2. Double-click the `.dmg` and **drag LidAwake into your Applications folder**.
3. **First launch**:
   - In Finder -> `Applications`, **Right-Click** (or `Control` + Click) **LidAwake**.
   - Select **Open** from the context menu.
   - Click **Open** in the confirmation dialog.
   *(You only need to do this once — macOS will remember your permission!)*

---

## 🛡️ Optional: One-Time Passwordless Closed-Lid Setup

Standard keep-awake and display sleep require **zero setup and zero passwords**.

To enable passwordless toggling for the **closed-lid clamshell mode** on battery:
1. Open Terminal.
2. Run:
```bash
sudo /Applications/LidAwake.app/Contents/Resources/install-helper.sh
```
*(Or run the helper script included inside the DMG)*.

---

## 🔄 Automatic Updates

LidAwake includes a built-in update verification tool:
- Click **LidAwake Menu Bar > About > Check for Updates** to verify the latest release status.

---

## 📜 Credits & License

- **Publisher:** [ToolNPlay.com](https://ToolNPlay.com)
- **Author & Architect:** **Pardeep Kumar** ([LinkedIn](https://www.linkedin.com/in/pardeeppatel/))
- **License:** Freeware / Proprietary. Free for personal, educational, and commercial use on macOS. Redistribution without modification permitted. Closed source.
