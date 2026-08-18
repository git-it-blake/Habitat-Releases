<p align="center">
  <img src="Images/habitat%20icons/Habitat%20Menubar%20Icon.png" width="160" alt="Habitat menu bar icon">
</p>

<h1 align="center">Habitat</h1>

<p align="center">
  The ecosystem your Mac's been missing.<br>
  Everyday Mac utilities in one native app — no Electron, no subscriptions.
</p>

<p align="center">
  <a href="#installation">Install</a> ·
  <a href="#tools">Tools</a> ·
  <a href="#privacy">Privacy</a> ·
  <a href="#pro--trial">Pro</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-MacOS%2026%2B-blue?style=for-the-badge" width="160" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/Apple%20Silicon-Arm64-black?style=for-the-badge" width="158" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/Swift-6.0+-orange?style=for-the-badge" width="91" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/git-it-blake/Habitat-Releases/releases"><img src="https://img.shields.io/github/downloads/git-it-blake/Habitat-Releases/total?style=for-the-badge&label=Downloads&color=brightgreen" alt="Downloads" width="128" /></a>
</p>

**Habitat** is a native macOS utility suite that brings together the everyday tools you need to manage, optimize, and protect your Mac — all inside a single, beautifully designed app. No Electron. No subscriptions. Just a fast, lightweight SwiftUI app that lives in your Dock and menu bar.

<p align="center">
  <img src="screenshots/habitat-home.png" alt="Habitat home dashboard with featured tools" width="720"/>
</p>

## Tools

Habitat is organized into ten purpose-built tools, each named after an animal or element that reflects its personality.

### Chomp

*Cleaner, Scanner & Quitter*

Chomp keeps your Mac feeling light and clean. Scan your disk with a visual Storage Orbit, uninstall apps with caches in one click, and stop background apps from hogging RAM.

- **App & Junk Uninstaller:** Removes support files, preference plists, and cache folders in one click.
- **Storage Orbit:** Visualizes disk usage using an interactive cluster of files.
- **Smart Quitter:** Automatically stops background app threads when the last window is closed.

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Chomp-Cleaner-Apps.png" alt="Chomp Cleaner — uninstall apps and related files" />
    </td>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Chomp-Cleaner-Junk.png" alt="Chomp Cleaner — scan and clean junk" />
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Chomp-Scanner.png" alt="Chomp Storage Orbit scanner" />
    </td>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Chomp-Quitter.png" alt="Chomp Smart Quitter" />
    </td>
  </tr>
</table>

### Squeak

*Mouse & Cursor Gestures*

Take absolute control over your mouse and trackpad. Map side mouse buttons to custom actions, fine-tune pointer speed, scroll direction, and snaps windows easily.

- **Title-Bar Snap:** Scroll on a window's title bar to snap, zoom, or minimize with haptics.
- **Mouse Gestures:** Set side buttons to trigger Mission Control, swiping Spaces, or clipboard history.
- **Mouse Jiggler:** Keeps your Mac active during long rendering operations or code compiling.

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Squeak-Trackpad-Gestures.png" alt="Squeak Trackpad Gestures for title-bar window management" />
    </td>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Squeak-Mouse-Settings.png" alt="Squeak Mouse Settings with button mapping and scrolling" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="screenshots/Squeak-Cursor-Tools.png" alt="Squeak Cursor Tools" width="50%" />
    </td>
  </tr>
</table>

### Spark

*Power Management*

Spark gives you a clear window into your Mac's battery health and power utilization. Monitor cycle counts, per-app energy, and customize your status menu bar items.

- **Power Dashboards:** Beautiful conic ring dials showing CPU load, memory, and remaining battery.
- **Battery History:** Log and check system battery charts over any 24-hour cycle.
- **Menu Bar Items:** Show custom stats, draw percentage, or customized indicators.

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Spark-Battery.png" alt="Spark Battery tab with charge ring, specs, power modes, and 24-hour graphs" />
    </td>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Spark-Energy.png" alt="Spark Energy tab with per-app power utilization" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="screenshots/Spark-Behaviour.png" alt="Spark Behaviour tab with menu bar items and power settings" width="50%" />
    </td>
  </tr>
</table>

### Hoo

*Network Monitoring*

Monitor your Mac's outgoing connections in real-time. Hoo geolocates destination servers on a world map, detailing sockets, IP connections and applications.

- **Map Geolocator:** Track connection locations on a high-fidelity stylized global map.
- **Process Logs:** View connection threads filtered by specific active applications.
- **100% Local Checkup:** All resolves and tracking run privately without external servers.

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Hoo-Watch.png" alt="Hoo Watch mode with geolocated connections on a world map and side summaries" />
    </td>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Hoo-Monitor.png" alt="Hoo Monitor with process connection logs" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="screenshots/Hoo-Toolkit.png" alt="Hoo Toolkit" width="50%" />
    </td>
  </tr>
</table>

### Boa

*Secure File Compression*

Compress and encrypt files natively at speed. Boa supports ZIP/TAR archives, AES-256 encryption, password safety, and SHA-256 check sums.

- **File Compression:** Create ZIP archives quickly with drag-and-drop functionality and adjustable compression levels.
- **Encryption:** Lock files and archives with AES-256 password protection that stays on your Mac.
- **File Converter:** Convert common file formats in place without sending anything to the cloud.

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Boa-Compression.png" alt="Boa File Compression with queue, preview, and zip options" />
    </td>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Boa-Encryption.png" alt="Boa Encryption with AES-256 password protection" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="screenshots/Boa-Converter.png" alt="Boa File Converter" width="50%" />
    </td>
  </tr>
</table>

### Echo

*Clipboard Manager*

Rich searchable history for everything you copy. Echo runs silently in the background, logging text, links, code blocks, and files with previews.

- **Rich Preview Cards:** Hover to review image content, URLs, code files, and formatting.
- **Quick Filters:** Search and sort logs instantly by source program or content category.
- **Flyout Clipboard:** View a popup clipboard on the fly using a keybind or menubar shortcut.

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Echo-Clipboard.png" alt="Echo History view with categories, search, and media preview" />
    </td>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Echo-Controls.png" alt="Echo Controls with filters and settings" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="screenshots/Echo-Menubar.png" alt="Echo menu bar clipboard flyout" width="50%" />
    </td>
  </tr>
</table>

### Shadow

*Notch Tool & Screen Breaks*

Shadow turns the notch space into an interactive files and settings dropdown drawer. Plus, stay healthy with full screen break reminders.

- **Notch Stash:** Drag active files to the notch to temporarily store or share them.
- **Rest Break Reminders:** Setup full-screen timers (Biscuits) to limit long eye fatigue.
- **Glass HUD:** Beautiful overlay graphics blending seamlessly into MacOS design.

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Shadow-Nook.png" alt="Shadow notch shelf with Now Playing and quick actions" />
    </td>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Shadow-Biscuits.png" alt="Shadow Biscuits rest-break reminders" />
    </td>
  </tr>
</table>

### Burrow

*Folder Quick Look*

Preview folder contents instantly without entering directories. Select any folder in Finder, hit Spacebar, and browse sortable directories and zip index archives.

- **Spacebar Folders:** Select folders in Finder and hit Spacebar to view their file list.
- **File Inspector:** Scroll directories and check file statistics inside the preview panel.
- **Archive Peek:** Browse zip folders without extracting files to disk.

<p align="center">
  <img src="screenshots/burrow-preview.png" alt="Burrow folder Quick Look preview with detailed file table" width="50%"/>
</p>

### Leap

*Window Switcher & Navigator*

Leap is a bouncy frog window switcher that replaces the default app switcher with a clearer, more useful interface. Bind any modifier + key combo, browse live window thumbnails, and jump between apps in a hop.

- **Custom Hotkeys:** Bind your own modifier + key combo for a better looking Cmd+Tab-style switcher.
- **Live Window Previews:** Browse open windows with thumbnails across apps, Spaces, and screens.
- **Keyboard Actions:** Close, minimize, fullscreen, hide, or quit selected windows without leaving the switcher.

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Leap-Switcher.png" alt="Leap window switcher with live window thumbnails" />
    </td>
    <td align="center" valign="top" width="50%">
      <img src="screenshots/Leap-Dock-Preview.png" alt="Leap Dock preview" />
    </td>
  </tr>
</table>

### Snap

*Screenshots & Recordings*

Snap captures your screen without leaving Habitat. Drag a selection, click a window, grab a display, or stitch a scrolling page — stills or recordings, with a capture toolbar on a global shortcut.

- **Selection, Window, Screen:** Capture or record a rectangle, an app window, or a whole display.
- **Scrolling Capture:** Auto-scroll and stitch a long page into one still.
- **Capture Toolbar:** A global shortcut opens a compact picker on the display under your pointer.

<p align="center">
  <img src="screenshots/Snap-Capture.png" alt="Snap Capture tab with screenshot and recording modes" width="50%"/>
</p>

## Menu Bar

Habitat integrates with the macOS menu bar without getting in the way:

- **Habitat main icon** — Click for a native-feeling dropdown with a **dashboard shortcut**, per-tool quick opens, About, and Check for Updates. The dropdown uses a transparent divot-arrow panel that matches the rest of macOS HUDs.
- **Spark battery** — Optional live charge / time-remaining indicator with customizable glyph styles.
- **Echo clipboard** — Optional quick-access popover for your clipboard history with hover previews that fly in and out smoothly as you move between items.

## Pro & Trial

- **14-day full trial** — Every Pro tool is unlocked during the trial. Trial time is counted as **active runtime**, not wall-clock: if you close Habitat for a week, the trial doesn't tick down.
- **Chomp is always free** — Cleanup, Space Lens, and the window-aware quitter work forever without a license.
- **$6.99 one-time** — Lifetime access, no subscriptions. Trial expiry never deletes your data; Chomp keeps working, and the other tools can be reactivated any time by entering a key.
- **Self-service deactivation** — Free up a license seat from **Settings → License → PRO** so you can move Habitat to another Mac.

## Privacy

- **100% local processing** — Clipboard history, connections, battery telemetry, disk scans — nothing leaves your Mac.
- **No accounts, no telemetry, no cloud sync**.

## Features

- **Beautiful native UI** — Frosted glass panels, smooth animations, and a design built entirely with SwiftUI.
- **Lightweight** — A single native process with minimal CPU and memory footprint.
- **Persistent** — Habitat stays running in the background when you close its window, just like Finder. Reopen from the Dock icon to surface the main window again.
- **Auto-updates** — Powered by [Sparkle](https://sparkle-project.org) with an in-app **Check for Updates** in both Settings and the Habitat app-menu.

## Requirements

- **macOS 26.0 (Tahoe)** or later
- **Apple Silicon** (arm64)
- **Accessibility permission** — required for Squeak's mouse controls, trackpad title-bar gestures, window management, and Chomp's window-aware quitter.
- **Screen Recording permission** — required for Snap screenshots, recordings, and scrolling capture.

## Installation

1. Download the latest release from the [Releases](../../releases) page.
2. Open the `.dmg` and drag **Habitat** to your Applications folder.
3. On first launch, macOS will prompt for access in **System Settings → Privacy & Security → Accessibility** (and optionally **Screen Recording**, **Input Monitoring**, or **Automation** depending on which tools you enable).

Habitat ships with [Sparkle](https://sparkle-project.org) for automatic updates — you can also trigger a check manually from **Habitat → Check for Updates** (menu bar) or **Settings → Check for Updates** (in-app).

## Support

If you enjoy Habitat and want to support its development:

<p align="left">
  <a href="https://buymeacoffee.com/blakebaker">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" >
  </a>
</p>

## Feedback & Bugs

Found a bug or have a feature request? Open an [Issue](../../issues) or use the **Report Bug** button inside **Habitat → Settings**.

---

## License

Habitat is proprietary software. All rights reserved.
See [LICENSE](LICENSE) for details.

---

<p align="center">
  Made with ❤️ for macOS
</p>
