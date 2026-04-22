<p align="center">
  <img src="https://img.shields.io/badge/platform-macOS%2026%2B-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/apple%20silicon-arm64-black?style=flat-square" />
  <img src="https://img.shields.io/badge/swift-6.0-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/price-%246.99%20one--time-green?style=flat-square" />
</p>

<p align="center">
  <b>Habitat</b><br/>
  <i>The ecosystem your Mac's been missing.</i>
</p>

---

## About

**Habitat** is a native macOS utility suite that brings together the everyday tools you need to manage, optimize, and protect your Mac — all inside a single, beautifully designed app. No Electron. No subscriptions. Just a fast, lightweight SwiftUI app that lives in your Dock and menu bar.


## Tools

Habitat is organized into six purpose-built tools, each named after an animal or element that reflects its personality:

| Tool | Role | What It Does |
|------|------|--------------|
| **Chomp** 🦈 | Cleaner · Scanner · Quitter | Disk cleanup, **Space Lens** storage visualization, local virus scanning, and an intelligent app quitter that auto-terminates apps when their last window closes. |
| **Spark** ⚡ | Battery Manager | Real-time battery health dashboard, charge-history charts, power-adapter stats, per-app energy tracking, and a menu-bar battery indicator with configurable icons. |
| **Squeak** 🐭 | Mouse & Cursor Tools | Per-mouse profile settings, scroll speed & direction control, pointer acceleration curves, custom button mappings, and **mouse gestures** (Spaces & Mission Control, Scroll & Navigate). |
| **Hoo** 🦉 | Network Security | Live outgoing-connection monitor with IP geolocation mapping, per-app bandwidth, DNS resolver tools, and a world-map view of where your Mac is talking to. |
| **Boa** 🐍 | Compress & Scan | File compression (ZIP / TAR), and local directory scanning utilities. |
| **Echo** 🦜 | Clipboard Manager | Persistent clipboard history with search, pinning, per-app exclusions, and one-click paste — never lose a copied snippet again. |

## System-Wide Features

These work everywhere on macOS, not just inside Habitat's window:

- 🪟 **Trackpad title-bar gestures** — Scroll up on any window's title bar to maximize, down to minimize, and left/right to snap to halves or quarters. Subtle haptic feedback confirms each commit. Gestures are gated to visible windows only, so they never leak onto the desktop below the menu bar.
- 🖱️ **Mouse gestures** — Map any of buttons 2–7 on a configurable mouse to **Scroll & Navigate**, including a native-feeling **Spaces & Mission Control** horizontal swipe that commits intentionally and ignores accidental wiggle-backs.
- 📐 **Window snapping with live reflow** — Halves, quarters, and a configurable grid gap; change the gap and already-snapped windows refit in place.
- 🔓 **Drag-to-unsnap** — Drag a snapped window off by its title bar and it pops back to its pre-snap frame.
- 🖱️ **Double-click-to-zoom (native title bar only)** — Respects browsers and rich document views so double-clicks on web pages aren't swallowed.
- 🎛️ **Squeak menu-bar HUD** — A tiny on-screen tooltip confirms the gesture you just performed (minimize, maximize, snap, etc.) with a smooth render-server fade.

## Menu Bar

Habitat integrates with the macOS menu bar without getting in the way:

- 🌿 **Habitat main icon** — Click for a native-feeling dropdown with a **dashboard shortcut**, per-tool quick opens, About, and Check for Updates. The dropdown uses a transparent divot-arrow panel that matches the rest of macOS HUDs.
- 🔋 **Spark battery** — Optional live charge / time-remaining indicator with customizable glyph styles.
- 📋 **Echo clipboard** — Optional quick-access popover for your clipboard history with hover previews that fly in and out smoothly as you move between items.

## Pro & Trial

- 🆓 **14-day full trial** — Every Pro tool is unlocked during the trial. Trial time is counted as **active runtime**, not wall-clock: if you close Habitat for a week, the trial doesn't tick down.
- 🆓 **Chomp is always free** — Cleanup, Space Lens, and the window-aware quitter work forever without a license.
- 💳 **$6.99 one-time via [DodoPayments](https://dodo.pe/hatitat-pro)** — Lifetime access, no subscriptions. Trial expiry never deletes your data; Chomp keeps working, and the other tools can be reactivated any time by entering a key.
- 🔁 **Self-service deactivation** — Free up a license seat from **Settings → License → PRO** so you can move Habitat to another Mac.

## Privacy

- 🔒 **100% local processing** — Clipboard history, connections, battery telemetry, disk scans — nothing leaves your Mac.
- 🚫 **No accounts, no telemetry, no cloud sync**.

## Features

- 🎨 **Beautiful native UI** — Frosted glass panels, smooth animations, and a design built entirely with SwiftUI.
- 🚀 **Lightweight** — A single native process with minimal CPU and memory footprint.
- 🖥️ **Persistent** — Habitat stays running in the background when you close its window, just like Finder. Reopen from the Dock icon to surface the main window again.
- 📥 **Auto-updates** — Powered by [Sparkle](https://sparkle-project.org) with an in-app **Check for Updates** in both Settings and the Habitat app-menu.

## Requirements

- **macOS 26.0 (Tahoe)** or later
- **Apple Silicon** (arm64)
- **Accessibility permission** — required for Squeak's mouse controls, trackpad title-bar gestures, window management, and Chomp's window-aware quitter.

## Installation

1. Download the latest release from the [Releases](../../releases) page.
2. Open the `.dmg` and drag **Habitat** to your Applications folder.
3. On first launch, macOS will prompt for access in **System Settings → Privacy & Security → Accessibility** (and optionally **Input Monitoring** / **Automation** depending on which tools you enable).

Habitat ships with [Sparkle](https://sparkle-project.org) for automatic updates — you can also trigger a check manually from **Habitat → Check for Updates** (menu bar) or **Settings → Check for Updates** (in-app).

## Screenshots

<!-- Screenshots will be added here -->

*Coming soon — screenshots and demo videos showcasing each tool.*

You can also explore the live interactive demo on the [Habitat website](https://habitatforyourmac.com).

## Support

If you enjoy Habitat and want to support its development:

<p align="left">
  <a href="https://buymeacoffee.com/blakebaker">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" >
  </a>
</p>

## Feedback & Bugs

Found a bug or have a feature request? Open an [Issue](../../issues) or use the **Report Bug** button inside **Habitat → Settings**.

## Acknowledgements

Habitat is a labor of love for the macOS ecosystem. While the project is original and all code in this app is written from scratch, the spirit and direction of individual tools were **inspired** by the incredible work of the independent macOS developer community — in particular the attention to detail that apps have brought to their respective domains.

---

## License

Habitat is proprietary software. All rights reserved.
See [LICENSE](LICENSE) for details.

---

<p align="center">
  Made with ❤️ for macOS
</p>
