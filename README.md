# Gear Tracker

A phone-friendly tracker for farming prototype gear in *The Division 2*: tracked sets with per-slot target rolls, a build maker with a dismantle check, and a collection checklist.

It's a Progressive Web App (PWA), so it installs to your home screen and works offline.

**Open it:** https://salaydh.github.io/gear-tracker/

## Install on your phone

- **iPhone (Safari):** open the link, tap the Share button, then **Add to Home Screen**.
- **Android (Chrome):** open the link, tap the ⋮ menu, then **Install app** (or **Add to Home screen**).

## Your data

Progress is saved on the device you use it on, not in the cloud. Use **Export** in the tab bar to save a backup file, and **Import** to load one on another device or after clearing your browser.

Meta research (the per-set build suggestions) runs from the claude.ai version of the tracker. Export a backup there and import it here to bring results over.

## Files

| File | What it does |
| --- | --- |
| `index.html` | The whole app: layout, styles and code in one page |
| `manifest.webmanifest` | App name, colours and icons used when it's installed |
| `sw.js` | Service worker that saves the app for offline use. Bump `VERSION` after changing any file so installed copies update |
| `icons/` | App icons |

## Notes

Unofficial fan tool. Not affiliated with or endorsed by Ubisoft. *The Division* is a trademark of Ubisoft Entertainment. All icons and artwork in this repository are original.
