# Aegisub Cheat Sheet

A visual reference for every icon, menu item, and default hotkey in [Aegisub](https://aegisub.org), grouped by where you actually find them in the app.

→ **[View the cheat sheet](https://YOUR-USERNAME.github.io/aegisub-cheat-sheet/)**

## What's in it

- Every icon from `src/bitmaps/button/` in the Aegisub source tree (~93 unique icons embedded inline)
- Default hotkeys from `default_hotkey.json`, scoped by context (Default, Always, Subtitle Grid, Audio, Video)
- Menu and toolbar placements parsed from `default_menu.json` and `default_toolbar.json`
- 205 commands across 15 sections, ordered exactly as they appear in the app — toolbars first (Main, Audio, Video, Visual Tools), then menus left-to-right (File → Edit → Subtitle → Timing → Video → Audio → Automation → View → Help), then context menus

## How to use it

Open `index.html` in any browser, or visit the live URL above. The top nav jumps to each section. Items are laid out as cards: icon on the left, name + tooltip + hotkey context badges on the right. Commands without an icon (e.g. `Open Subtitles from Video` in the File menu) still appear at their correct position so the order matches what you see in Aegisub.

The whole thing is one self-contained HTML file — every icon is embedded as base64 in CSS, so it works offline once downloaded.

## Credits & license

Aegisub itself is © its respective contributors and licensed under a 3-clause BSD license. The icons, menu/toolbar JSON configs, and command metadata used to build this page all come from the [TypesettingTools/Aegisub](https://github.com/TypesettingTools/Aegisub) repository.

This cheat sheet is a personal reference compilation. Use however you like.
