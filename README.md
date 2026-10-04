# Crimson Save Editor

A save editor for Crimson Desert on PC, from AR Smart Tech Solutions. Download it from the **Releases** section on the right. It's a single `CrimsonSaveEditor.exe` with nothing to install.

## Using it

1. Quit Crimson Desert to the desktop.
2. Run `CrimsonSaveEditor.exe`. Windows may say it "protected your PC", because the file isn't code-signed. Choose **More info**, then **Run anyway**.
3. Your browser opens the editor. It runs only on your own PC and never sends your saves anywhere.
4. Pick a save slot, change things, then press **Save**. A backup is made before every change, and the **Backups** tab puts a slot back with one click.

It finds your saves in `%LOCALAPPDATA%\Pearl Abyss\CD\save` automatically. Item names, icons and the world map are read from your installed game.

## Good to know

- Built and tested with game version 1.04.02. The save format describes itself, so other versions should open. Names, shop data and challenge data come from 1.04.02, so a few may be wrong on other patches.
- Changing values (money, quantities, levels) is the safest kind of edit. Adding things (items, gems, knowledge, mounts) makes the save bigger. The editor checks every internal pointer before it writes, but try it on a spare slot first and keep the backup until you've loaded the slot in game.
- Not affiliated with Pearl Abyss. Use at your own risk.

## Credits

The save format was worked out by the community: NattKh's [CRIMSON-DESERT-SAVE-EDITOR](https://github.com/NattKh/CRIMSON-DESERT-SAVE-EDITOR-AND-GAME-MODS) and bbfox0703's [crimson-rs](https://github.com/bbfox0703/crimson-rs) and [CrimsonAtomtic](https://github.com/bbfox0703/CrimsonAtomtic).

Some name data bundled in the exe comes from NattKh's project under the Mozilla Public License 2.0 (see `LICENSE-MPL-2.0.txt`). Those data files are available in that project.
