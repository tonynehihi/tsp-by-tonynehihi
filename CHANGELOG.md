# Changelog

## TS PowerPoint 1.1.1

- **RENAMED APP BUNDLE**: the macOS app bundle is now **TS PowerPoint.app** (it was TsP.app), so Spotlight finds the app when you search "PowerPoint". The bundle id, documents, settings and data folders are unchanged — everything keeps working exactly as before, and the built-in updater handles the rename by itself.

— tonynehihi

## TS PowerPoint 1.1.0

First release of TS PowerPoint, a personal build based on DeckCraft 0.9.0 by storytold.

- **NEW NAME AND ICON**: the app is now "TS PowerPoint" everywhere — window title, About screen and the macOS bundle **TsP.app** — with a new PowerPoint orange-red icon drawn in the Tony Suite design language. Settings and document folders keep their original names, so existing data is untouched.
- **SELF-UPDATE BUILT IN**: Help → **Check for Updates** (and a one-time check at launch) asks this repo's Releases for a newer version and shows its changelog in the app. On macOS the update downloads, builds and installs itself; the app closes only for a few seconds at the end to swap versions, keeps the previous version as a backup, and reopens on its own.
- **UPSTREAM LINKS REMOVED**: the Help menu is now exactly About TS PowerPoint / Check for Updates / Command Palette. The Discord and GitHub links in About, on the start screen and on the Backstage info page, the ribbon's "Learn More" button, and the command-line tool's `links` command are gone — nothing in the app points back to the upstream project anymore.
- Everything else is DeckCraft 0.9.0 as released by storytold; TS PowerPoint tracks the upstream project and folds its new features into future releases.

— tonynehihi
