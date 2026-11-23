# Installing the FIFA 19 (Xbox 360) 2026/27 squad update

## Requirements
- **Game:** FIFA 19 for Xbox 360, US version (Title ID `454109F9`).
- **Format:** an **extracted game folder** (with `default.xex` and `data0.big`). A GOD (Games on Demand) container will not work, because its files cannot be replaced.
- **Same base version as this update:** your original `data0.big` must be **7,726,256 bytes**, SHA-1 `51d0f55d229550dd37abc191a10c0a8ec296d849`. If yours differs, do not install.

## Files in each release

| File | Where it goes in the game folder |
|---|---|
| `data0.big` | game root (next to `default.xex`) |
| `data0.bh` | game root |
| `locale.big` | `data/loc/` |

## Install on Xbox 360 (Aurora / FSD over FTP)
1. Start the console and open Aurora. Note the console's IP address.
2. Connect with an FTP client (e.g. FileZilla), using the FTP login set in Aurora.
3. Open the game folder, the one that holds `default.xex`.
4. **Back up first:** rename each original file by adding `.orig`:
   - `data0.big` → `data0.big.orig`
   - `data0.bh` → `data0.bh.orig`
   - `data/loc/locale.big` → `data/loc/locale.big.orig`
5. Upload the three new files from the zip to the places in the table above.
6. Start the game.

**To uninstall:** delete the new files and rename the `.orig` files back.

## Install on an emulator (Xenia)
Same steps, in the extracted game folder on your computer. Keep `.orig` copies before replacing the files.

## What to test and report
1. **First start:** the "Your Club" screen should show a country, a league and a club, with a crest and stars.
   - A grey shield, 0 stars and "Build Up Speed Slow" means the update failed. Take a screenshot and report it.
2. **Kick Off:** all leagues and teams should be listed.
3. **A full match:** report any freeze or crash.
4. **Squads:** report wrong players, numbers or positions.

## Notes
- **Do not load an old Squads save.** It replaces the update with the old squads.
- **Inter Miami** (in Colorado Rapids' slot) has its new name and colours, but still uses Colorado's crest and kits.
- **New players** have generic faces, and the commentator does not say their names.
- So far every release has been tested in an emulator only, **not yet on a real Xbox 360**.
