<div align="center">
  <img src="https://github.com/LukeZGD/DDLC-LOVE/raw/ddlclove/logo.png"/>
  <h1>DDLC-LOVE</h1>
  <h3>Will you write the way into her heart?</h3>
</div>

- **DDLC-LOVE** is a Doki Doki Literature Club port programmed in Lua for the **Nintendo Switch, 3DS, Sony PS Vita, PSP, and PS3!**
- This forked repository focus is updating the **PSP** version and fix it's bugs.
- **This port is unofficial and is not affiliated with Team Salvato. Please support the official game. You can download Doki Doki Literature Club at: https://ddlc.moe**
- **For the full experience of the game on the PC, Switch, and other consoles, please support Team Salvato and buy Doki Doki Literature Club Plus! Get the official console versions at: https://ddlc.plus**

## Downloads:
- [PSP v1.2.4 (.zip)](https://github.com/FagnerLSantos/DDLC-LOVE/releases/download/v1.2.4/DDLC-LOVE-PSP.zip)
- For other systems, check out [LukeZGD's original repository](https://github.com/LukeZGD/DDLC-LOVE#downloads)

## Notes:
- Although some bugs from the original release have been fixed, the support for PSP is still limited. For more details, see [Issue #123](https://github.com/LukeZGD/DDLC-LOVE/issues/123) in LukeZGD's original repository.
- DDLC-LOVE is not compatible with any existing mods and translations. Also, DDLC-LOVE is a port of the free base game only. Content from DDLC Plus will not be ported over to DDLC-LOVE. If you want DDLC Plus content, please support Team Salvato and buy the game from the official platforms.

## Usage:
- **PSP** - Download the `.zip` for the PSP version, and extract the folder with `EBOOT.PBP` to your Memory Stick at `ms0:/PSP/GAME/`. You can now run DDLC-LOVE from the XMB (**PSP Go** users should use a Memory Stick, Internal Storage is not supported).
NOTE: You can extract it into a subfolder instead if you're using `Game Categories Lite` plugin, but the [location of Save Files](https://github.com/FagnerLSantos/DDLC-LOVE#locations-of-save-files) will remain the same.


## Locations of Save Files:
- You can reset the Save Data and start over by deleting the Save File folder or the files inside it. This is also mentioned in the help menu ingame.

| Platform | Location                            |
|----------|-------------------------------------|
| PSP      | ms0:/PSP/GAME/DDLC-LOVE/savedata/   |

## Building:
- For v1.2.1 and newer, game assets are to be extracted from the latest release.
- Game assets from the [DDLC-LOVE-Assets](https://github.com/LukeZGD/DDLC-LOVE-Assets) repo are only to be used for v1.2.0 and older.
- For all Sony devices, [LOVE-WrapLua](https://github.com/LukeZGD/LOVE-WrapLua) is also required beside the game folder (`index.lua`, `script.lua`, and the `LOVE-WrapLua` folder). See the contents of the Vita, PSP, and PS3 versions for the directory tree (`.vpk` and `.zip` releases).

### Credits:
- [OneLua](http://onelua.x10.mx/) by OneLua Team is used for the PSP version
- [Spanish translation](https://tradusquare.es/ficha.php?ddlc) by GlowTranslations