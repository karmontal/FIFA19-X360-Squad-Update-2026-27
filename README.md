# FIFA 19 (Xbox 360) — 2026/27 Squad Update

An unofficial, fan-made squad update for **FIFA 19 on Xbox 360**. This is an early test build, and testers are wanted, especially on real hardware.

**⬇️ Download:** the zip in [Releases](../../releases/latest).

## What's in it (v0.3)
- **Fixed in v0.3:** in v0.2, 59 new players (Bellingham, Musiala, Wirtz, Palmer, Mainoo and others) were women in game. If you installed v0.2, replace `data0.big` with the one from v0.3; the other two files are unchanged.
- **Seven leagues** with their full 2026/27 squads: Premier League, LaLiga, Serie A, Bundesliga, Ligue 1, Saudi Pro League and MLS.
  - 1,201 transfers
  - 3,058 new players
  - 5,461 rating updates
- Promoted and relegated clubs follow the 2026/27 season.
- **Inter Miami CF** takes Colorado Rapids' slot, with Messi, De Paul, Casemiro and Suárez.
- A few examples:
  - Real Madrid: Mbappé, Alexander-Arnold
  - Liverpool: Wirtz, Isak, Ekitiké
  - Bayern: Kane, Olise, Luis Díaz
  - PSG: Kvaratskhelia, João Neves
  - Al Nassr: Ronaldo, João Félix
  - LAFC: Son

## Known limits
- Inter Miami has its new name and colours, but still uses Colorado's crest and kits.
- New players have generic faces, and the commentator does not say their names.
- Saudi Pro League: four clubs (Al Batin, Al Raed, Al Wehda, Ohod Club) aren't in this season's league. They stand in for current clubs FIFA 19 doesn't have, and keep their 2018 squads.
- Other leagues keep their 2018 squads.

## Requirements
- FIFA 19 for Xbox 360, **US version** (Title ID `454109F9`).
- An **extracted game folder** (with `default.xex` and `data0.big`). A GOD (Games on Demand) container will not work, because its files cannot be replaced.
- Your original `data0.big` must be **7,726,256 bytes**, SHA-1 `51d0f55d229550dd37abc191a10c0a8ec296d849`. If yours differs, do not install.
- An RGH/JTAG console with Aurora or FSD, or the Xenia emulator.

## Files in the zip

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
5. Upload the three new files to the places in the table above.
6. Start the game.

**To uninstall:** delete the new files and rename the `.orig` files back.

**On Xenia:** same steps, in the extracted game folder on your computer.

## What to test and report
Please open an [issue](../../issues) with what you find:
1. **First start:** the "Your Club" screen should show a country, a league and a club, with a crest and stars. A grey shield with 0 stars means the update failed; please attach a screenshot.
2. **Kick Off:** all leagues and teams should be listed.
3. **A full match:** any freeze or crash.
4. **Squads:** wrong players, numbers or positions.

Also say whether you played on a real console or in Xenia.

## Notes
- **Do not load an old Squads save.** It replaces the update with the old squads.
- So far the update has been tested in an emulator only, not yet on a real Xbox 360.

## Disclaimer
This is an unofficial fan project, not affiliated with or endorsed by Electronic Arts. FIFA is a trademark of its owners. You need your own copy of the game.
