# Pressure Gauge — Steam Art Studio

**Make your Steam library look the way you want.** Pressure Gauge is a free Windows app for choosing and customising the artwork in your Steam library: covers, wide banners, hero backgrounds, logos and icons, for Steam games and your non-Steam shortcuts alike.

Browse thousands of community designs from SteamGridDB, add frames and banners, colour them, bake in logos, and see it all on a live preview before anything touches Steam.

> **Beta.** Pressure Gauge is still in beta. It always keeps a copy of everything it replaces, but please keep your own backup too and report anything odd.

---

## Features

- **Every kind of library art:** vertical covers, horizontal banners, heroes, logos and icons, including icons for non-Steam games.
- **SteamGridDB built in:** search by game, filter static or animated, and pick a result straight onto your game. Steam's own official art is one click away too.
- **Frames and banners:** dozens of styles you can recolour, stack and position, plus folders for your own PNG frames and banners (vertical and horizontal).
- **Logo tools:**
  - place logos in Steam's own spots, or anywhere on the hero with *Anywhere*
  - make text logos in several fonts
  - clean up backgrounds, outline, add a shadow or glow
- **Edit tools:** crop, brightness, contrast, saturation, colour tint, squares and circles, and an eyedropper with saved colours.
- **Nothing changes until you press Apply.** Every pick is staged first, and you can undo, discard, or restore from History at any time.
- **History and Favourites:** everything you've applied is kept, so going back is one click.
- **Backups:**
  - "Back up now", with a choice of what to include
  - automatic backups in the background
  - restores that check the backup first and undo themselves if anything goes wrong
- **More than one Steam account:** each account keeps its own edits and History.
- **Library extras:**
  - export your whole library, or one collection, as a single PNG
  - find games that Steam never gave a cover
  - tags, hidden games, collections and size controls
- **Your choice of look:** dark and light themes, plus several colour themes, and keyboard shortcuts you can change.

## Requirements

- Windows 10 or 11 (64-bit)
- Steam installed, and signed in at least once on this PC
- A free **SteamGridDB API key** to browse SteamGridDB. You can get one from your [SteamGridDB API preferences](https://www.steamgriddb.com/profile/preferences/api). Everything else works without it.

## Install

1. Download the latest installer from **[Releases](https://github.com/HookerHeels/pressuregauge/releases)**.
2. Run it. No administrator rights are needed: Pressure Gauge installs just for you.
3. Open Pressure Gauge, paste your SteamGridDB key at the top of **Settings**, and pick a game.

The first launch shows a short tour. You can skip it and replay it any time from Settings.

### Updating

Pressure Gauge checks this page for new versions and tells you when one is out. To update, install the new version over the old one: your settings, edits, History and Favourites stay where they are.

### Uninstalling

Use **Settings › Apps** in Windows, as usual. Your **Pressure Gauge Data** folder (settings, History, Favourites, your own frames, banners and fonts) is left in place in case you come back. Delete it yourself if you don't need it.

## Good to know

- **Steam sometimes needs a restart** to show new art, especially icons for non-Steam games. Pressure Gauge shows a *Restart Steam* button when that's likely.
- **Heroes move around.** Steam crops the hero differently depending on window size, so a logo placed with *Anywhere* can take a try or two to line up.
- **Where your data lives:** everything is in the **Pressure Gauge Data** folder next to the app. Automatic backups and recovery copies are kept there as well.

## Privacy

- Your SteamGridDB API key is stored on your PC only, encrypted with Windows' own protection. It's never written into settings files or backups.
- Pressure Gauge only connects to:
  - **SteamGridDB:** searching and downloading art
  - **Steam:** official art, and checking which games have covers
  - **GitHub:** checking for updates, which you can turn off
- No accounts, no tracking, no analytics.

## Support

Found a bug or have an idea? Open an [issue](https://github.com/HookerHeels/pressuregauge/issues) or email **oddboxcode@gmail.com**. It helps to say what you did, what you expected, and your Pressure Gauge version (shown in Settings).

## Credits

- Built with [Neutralinojs](https://neutralino.js.org) (MIT License).
- Fonts: Manrope, IBM Plex, Bebas Neue, Russo One, Playfair Display and Press Start 2P (SIL Open Font License 1.1).
- Community artwork comes from [SteamGridDB](https://www.steamgriddb.com) and belongs to its creators.

Pressure Gauge is not affiliated with or endorsed by Valve, Steam or SteamGridDB.

## Licence

© 2026 OddBoxCode. Pressure Gauge is free to download and use; see [LICENSE](LICENSE) for the full terms.
