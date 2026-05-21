<p align="center">
  <img src="app-icon.png" alt="WorkSpace Manager Icon" width="120" height="120" style="border-radius: 28px; box-shadow: 0 10px 30px rgba(0,0,0,0.2);" />
</p>

<h1 align="center">WorkSpace Manager for macOS</h1>

<p align="center">
  <strong>Version 2.0.8</strong> • Native macOS Automation<br/>
  Apps, Websites, Folders, and Terminals launched in <strong>one click</strong>.
</p>

<p align="center">
  <a href="README.it.md">🇮🇹 Leggi in Italiano</a>
</p>

<p align="center">
  <a href="https://frafra077.github.io/workspace-manager/"><b>🌐 Official Website</b></a> •
  <a href="https://github.com/frafra077/workspace-manager/releases/latest"><b>📦 Download v2.0.8 (.dmg)</b></a>
</p>

<!-- BADGES -->
<div align="center">
  <img src="https://img.shields.io/badge/Apple-Notarized_%26_Signed-success?style=for-the-badge&logo=apple&logoColor=white" alt="Apple Notarized" />
  <img src="https://img.shields.io/badge/SwiftUI-100%25%20Native-blueviolet?style=for-the-badge&logo=swift&logoColor=white" alt="SwiftUI" />
</div>

<br/>

> [!TIP]
> **New in v2.0.8:** Native macOS menu follows app language · multiple terminals per workspace · smarter Finder group reopening · Help menu linked to official site · French release notes for Sparkle 🇫🇷
> **v2.0.7:** Liquid Glass Design for Settings and selectors · animated Apple-style onboarding · improved Finder controls · French localization 🇫🇷 · smarter numeric badges
> **v2.0.6:** Finder Management Revolution — Unified paths, deterministic opening order, manual sorting UI, and reliable persistence
> **v2.0.5:** Finder Tabs · Folder Window Groups · Pro Demo for Free users

---

## ⚡️ Why WorkSpace Manager?

Stop wasting 10 minutes every morning setting up your digital desk.
Create "Contexts" (e.g., *Work, University, Freelance*) and launch them instantly.

### ✨ Key Features

| 🔒 **Privacy & Security** | 🚀 **Performance** | 🌍 **Localization** | 🌗 **Themes** |
|---|---|---|---|
| **TouchID / FaceID** support | Native engine rewritten | English 🇬🇧 / Italian 🇮🇹 / French 🇫🇷 | Light/Dark/System |

| 💾 **Backup** | 🔄 **Close Workspace** | 🞃 **Hide Dock Icon** | 🗂️ **Finder Tabs** |
|---|---|---|---|
| JSON Export/Import | Close only what was opened | Menu Bar only mode (Pro) | Group folders in one window (Pro) |

---

## 📸 Preview

<p align="center">
  <img src="SCREEN_DASHBOARD.png" alt="WorkSpace Manager Dashboard" width="100%" style="border-radius: 12px; border: 1px solid #333;" />
</p>

---

## 💎 Free vs Pro

| Feature | Free | Pro |
|---|---|---|
| Workspaces | 1 | Unlimited |
| Launch Apps, Folders, Websites | ✅ | ✅ |
| Menu Bar Resident | ✅ | ✅ |
| **Automatic Updates** | ✅ | ✅ |
| Close Workspace | 3x / month | ✅ Unlimited |
| Finder Tabs (grouped folders) | 🔒 Demo | ✅ Unlimited |
| Hide Dock Icon | ❌ | ✅ |
| TouchID Protection | ❌ | ✅ |
| Backup & Restore | ❌ | ✅ |
| Priority Support | ❌ | ✅ |

---

## 🌐 Native Menu & Multi-Terminal Support — A More Consistent Experience (New in v2.0.8)

WorkSpace Manager 2.0.8 refines the app experience with a more consistent native menu, smarter Finder behavior, and expanded terminal support.

- **Native macOS Menu Follows App Language** — The menu bar now respects the language chosen in the app settings, including titles and common entries automatically injected by macOS.
- **Multiple Terminals per Workspace** — The Terminal & Commands section can now define multiple folders and commands, all launched at once when the workspace opens, while keeping compatibility with single-terminal setups.
- **Smarter Finder Group Reopening** — The “Reopen Group” command first closes the tracked group before reopening it, avoiding duplicate windows when the group was already open.
- **Help Menu Linked to Official Website** — The WorkSpace Help menu item now points directly to the app’s official website for quick access to documentation and support.
- **French Release Notes for Sparkle** — French release notes (`notes-fr.html`) have been added to the Sparkle feed, and the release/appcast script now generates update links for `it`, `en`, and `fr`.
- **Stable Native View Menu** — The native macOS View menu is kept active to prevent intermittent re-insertions, and native panel/tab entries have been removed without deleting the menu itself.
- **Improved Menu Bar Localization** — Menu titles are normalized and updated during `menuNeedsUpdate`, so macOS‑generated entries also follow the app language.
- **Smoother Menu Bar Behavior** — Menu bar synchronization has been stabilized, eliminating freezes when opening menus.

---

## 🎨 Liquid Glass Refresh — A More Native Settings Experience (v2.0.7)

WorkSpace Manager 2.0.7 modernizes the app experience with a full Settings refresh and clearer Finder controls.

- **Liquid Glass Design** — Settings and selection tabs now use native materials, translucency, and a more spacious visual language inspired by modern macOS.
- **Animated Onboarding** — First-time users are welcomed by a smoother Apple-style intro animation.
- **Better Finder Controls** — Folder ordering is clearer, more responsive, and easier to understand at a glance.
- **Finder Group Button** — The group selector is now a rounded, readable button instead of a compact dropdown.
- **Accidental Close Recovery** — A new in-app popup lets you quickly reopen folders and related workspaces closed by mistake.
- **French Localization** — Full French language support has been added.
- **Smart Numeric Badges** — Workspace configurations now show counts for Apps, Websites, and Files without opening each section.
- **Improved Symbol Legend** — The legend now explains the new indicators more clearly.

---

## 🗂️ Finder Revolution — Total Folder Control (v2.0.6)

We have completely redesigned how folders are handled. It's no longer just about tabs; it's about absolute order and organization.

- **Unified Paths** — No more distinction between "Main" and "Additional" folders. A single, streamlined list for everything.
- **Deterministic Opening Order** — Folders open exactly in the order you set them in the UI. Every time.
- **Window Groups (Pro)** — Truly decide which folders open as tabs and which open in separate windows.
- **Manual Sorting UI** — New directional arrows to easily move folders up or down within your groups.
- **Smart Activation** — The app intelligently detects already open folders and avoids opening redundant windows or tabs.
- **Reliable Persistence** — A new saving engine ensures your window group configurations are never lost.

> 🔒 Advanced Window Grouping and Tab support is a **Pro** feature (Demo included for Free users).

---

## 📦 Secure Installation

As fully notarized software, installation is standard:

1. **Download** `WorkSpace.2.0.8.dmg` from the [Releases Section](https://github.com/frafra077/workspace-manager/releases/latest)
2. **Drag** the app into your `Applications` folder
3. **Launch** and enjoy your saved time 🚀

*(No weird security warnings, no "Right Click → Open" needed)*

---

## 💼 License & Support

WorkSpace Manager uses a **Freemium** model.
- **Starter (Free):** Core functionality forever, no time limit.
- **Pro License:** Unlocks TouchID, Unlimited Workspaces, Close Workspace (unlimited), Finder Tabs, Hide Dock Icon, and Priority Support.

👉 [Get PRO License](https://frafra077.github.io/workspace-manager/#download)

For bug reports or feature requests:
- 🐞 **Issue Tracker**: [GitHub Issues](https://github.com/frafra077/workspace-manager/issues)

---

## 📋 Changelog

### v2.0.8 (May 21, 2026)
- 🌐 **Native Menu Follows App Language** — the macOS menu bar now reflects the language chosen in the app settings, including titles and entries automatically injected by macOS
- 🖥️ **Multiple Terminals per Workspace** — the Terminal & Commands section now supports multiple folders and commands per workspace, all launched when the workspace opens
- 🔁 **Smarter Finder Group Reopening** — the “Reopen Group” command first closes the tracked group and then reopens it, avoiding duplicate windows
- ❓ **Help Menu Linked to Official Website** — the WorkSpace Help menu item now points directly to the app’s official website
- 🇫🇷 **French Release Notes for Sparkle** — French release notes (`notes-fr.html`) added to the Sparkle feed, with multi‑language links (`it`, `en`, `fr`)
- 🖥️ **Stable Native View Menu** — the native macOS View menu is kept active to prevent intermittent re‑insertions, while native panel/tab entries have been removed
- 🌐 **Improved Menu Bar Localization** — menu titles are normalized and updated during `menuNeedsUpdate`, so macOS‑generated entries also follow the app language
- ⚙️ **Smoother Menu Bar Behavior** — menu bar synchronization has been optimized to avoid freezes when opening menus

### v2.0.7 (April 22, 2026)
- 🎨 **Liquid Glass Design** — redesigned Settings and selection tabs with native materials, translucency, and a more spacious macOS look
- ✨ **Animated Onboarding** — new Apple-style welcome animation for first-time users
- 📂 **Better Finder Controls** — clearer folder ordering, improved group selector button, and faster visual feedback
- ♻️ **Accidental Close Recovery** — new popup to quickly reopen folders and related workspaces closed by mistake
- 🇫🇷 **French Localization** — full French language support added
- 📊 **Smart Numeric Badges** — Apps, Websites, and Files now show item counts directly in the workspace configuration
- 🧭 **Improved Symbol Legend** — updated explanations for the new indicators

### v2.0.6 (April 15, 2026)
- ✅ **Finder Revolution** — Unified paths, deterministic opening order, and new sorting UI (arrows)
- ✅ **Smart Activation** — Automatically detects already open folders to prevent redundant windows or tabs
- ✅ **Window Grouping 2.0** — Refactored data model for reliable grouping and persistence
- ✅ **Premium Workspace Selector** — High-fidelity card design in Settings with "Ghost Picker" interaction
- ✅ **Localization 2.0** — Fixed language fallback logic (English now correctly defaults for non-Italian users) and translated system permission strings
- ✅ **UI Grouping** — Settings now visually group folders by window ID for extreme clarity
- ✅ **Reliable Saving Engine** — Switched to custom `Codable` implementation to prevent configuration loss
- 🔧 Improved menu bar menu positioning to prevent clipping outside window bounds

### v2.0.5 (April 14, 2026)
- ✅ **Finder Tabs** — open multiple workspace folders in a single Finder window using tabs (Pro)
- ✅ **Folder Window Groups** — choose which folders open together and which open in a separate window
- ✅ **Pro Demo for Finder Tabs** — Free users can try the feature with a limited demo
- ✅ Clearer Pro upgrade prompt when demo ends
- 🔧 Accessibility permissions check — alert shown only when actually needed
- 🐛 Fixed folders opening in separate windows even with tabs enabled
- 🐛 Fixed potential duplication of the first folder

### v2.0.4 (April 13, 2026)
- ✅ **Automatic Updates** — faster & more secure
- ✅ **macOS Sonoma Support** restored (macOS 14.0+)
- ✅ Manual update check from Settings → Info tab
- ✅ Smart startup update checks (non-intrusive)
- 🎨 Settings UI refinements

### v2.0.3 (March 13, 2026)
- ✅ Hide Dock Icon — toggle from Settings → General (Pro only)
- 🐛 Bug fixes and stability improvements

### v2.0.2 (February 26, 2026)
- ✅ Close Workspace (session-based, 3x/month Free – Unlimited Pro)
- 🐛 Fixed website opening in new window
- ✨ Minor UI improvements

### v2.0.1 (January 27, 2026)
- ✅ Enhanced English localization
- 🐛 Minor bug fixes

### v2.0.0 (January 19, 2026)
- 🔒 TouchID / FaceID support
- 🌍 English & Italian localization
- 🌗 Light/Dark/System theme
- 💾 Backup & Restore
- ⭐ Favorite workspace
- 📖 Interactive onboarding

[View all releases →](https://github.com/frafra077/workspace-manager/releases)

---

## 📱 System Requirements

- macOS **Sonoma 14.0** or later
- Processor: Apple Silicon (M1/M2/M3/M4) or Intel

![Notarized](https://img.shields.io/badge/macOS-Notarized_%26_Signed-brightgreen?style=for-the-badge&logo=apple&logoColor=white)
