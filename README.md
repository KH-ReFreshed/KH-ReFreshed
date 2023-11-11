![combined_no_shadow_or_logo](https://github.com/TopazTK/KH-ReFined/assets/95656963/482d02f4-66f6-4b7e-8b73-06c1635da2ef)

## Download

Get the latest v4.xx release by clicking the button below.

[![KH-ReFixed](https://img.shields.io/badge/Kingdom_Hearts_Re:Freshed-Download-blue.svg)](https://github.com/KH-Refreshed/KH-ReFreshed/releases/latest)

If you plan to play games other than Kingdom Hearts II, see the [v3.00 branch](https://github.com/KH-Refreshed/KH-ReFreshed) instead.

### Installation

Installing Re:Freshed is easy, even though it may seem like a monumential task. Please refer to [this page](SETUP.md) for full instructions.

## Features (Kingdom Hearts II)

| Error/Bug Fix | Enhancement | Description |
|---------------|-------------|-------------|
| :heavy_check_mark: | - | Disable cutscene framelimiter. [[1]](#reference) |
| :heavy_check_mark: | - | The Mouse Cursor will now follow a VirtualBox-style capture mechanism. |
| :heavy_check_mark: | - | The game will no longer infinitely freeze while shutting down. |
| :heavy_check_mark: | - | The game will no longer crash OBS after a resize. |
| :heavy_check_mark: | - | Added the ability to launch and play the game whilst offline. |
| :heavy_check_mark: | - | Removed savefile Epic ID check. [[2]](#reference) |
| :heavy_check_mark: | - | Correct Limit Form's Limit names so that they are more accurately translated. [[3]](#reference) |
| :heavy_check_mark: | - | Restore the ability to exit the game from the title screen. |
| :heavy_check_mark: | - | The Credits FMV can now be skipped. |
| - | :heavy_check_mark: | Voice channels will now be muted when set to "1" in the PC settings menu. |
| - | :heavy_check_mark: | Autosaving functionality, utilizing Slot #99. |
| - | :heavy_check_mark: | An RPC Engine is now present for use with Discord. |
| - | :heavy_check_mark: | The MP bar will no longer be present until Sora learns his first magic. [[4]](#reference)| 
| - | :heavy_check_mark: | Soft reset implementation (R2 + L2 by default). Can be cancelled by pressing the CONFIRM button. |
| - | :heavy_check_mark: | Create a game-specific configuration file named `config_xxx.dat` so that changes only have effects on a per-game basis. |
| - | :heavy_check_mark: | Moved savefiles to a more suitable place. Please move them if you had some already! [[5]](#reference) |
| - | :heavy_check_mark: | Implemented 21:9/32:9 compatibility. |
| - | :heavy_check_mark: | Removed the FMV on the Title Screen. |
| - | :heavy_check_mark: | The player can now retry all forced encounters. [[6]](#reference) |
| - | :heavy_check_mark: | Added the ability to "Prepare and Retry". [[7]](#reference) |
| - | :heavy_check_mark: | Added the Encounter Plus ability to the game. [[8]](#reference) |
| - | :heavy_check_mark: | Added a warp point to Garden of Assemblage. |
| - | :heavy_check_mark: | Sora's Crown will now also appear in the HUD Image according to the crown he has. |
| - | :heavy_check_mark: | Dual-Audio capabilities, allowing one to switch from and to English or Japanese vocals plus one more language of choice. [[9]](#reference) |
| - | :heavy_check_mark: | Atlantica Musical segments can be unpaused now. |
| - | :heavy_check_mark: | Include an option upon selecting `New Game` to skip Roxas' introduction sequence. |
| - | :heavy_check_mark: | The player is now able to re-organize the Magic menu to their liking. This is done on a per-save basis. [[10]](#reference) |
| - | :heavy_check_mark: | Drive Forms will now appear in the inventory. |
| - | :heavy_check_mark: | Drive Forms can now be placed in the Shortcut Menu. |
| - | :heavy_check_mark: | Limit Form's Shortcuts can now be reorganized through the config file. |
| - | :heavy_check_mark: | In-game config options will now persist on a per-save basis. |
| - | :heavy_check_mark: | The `Kingdom Hearts` Command Menu setting is now more resembling of the menu from the first game. |
| - | :heavy_check_mark: | Added the ability to enforce either Controller or MKB Prompts through the config menu. |
| - | :heavy_check_mark: | Implemented the Resource Pack Engine. Peers can now make 3 types of Resource Packs for Re:Freshed. |

#### Reference

1. Cutscenes will by default lock the game to 30fps. This alleviates that.
2. The savefiles are DRM'd normally - meaning you can't share savefiles with other people. Re:Freshed removes that DRM.
3. Sora/Roxas immediately have MP Bars when the game begins, despite having no magic. This fix will now make said MP bar invisible until the player learns their first magic spell. (Usually Fire in KH1, Blizzard in KH2.)
4. The game originally saves everything to `Documents/KINGDOM HEARTS HD 1.5+2.5 ReMIX\Epic Games Store\[EGS ID]`. Re:Freshed changes the path to `Documents\Kingdom Hearts\Save Data\[EGS ID]`.
5. In the HD remaster of KH2, the localization team changed the translation of certain attacks to contrast with their usual translations from Japanese. E.g. Ragnarok -> Infinity. This fix reverts that awful decision. 
6. Starting in Birth by Sleep, the player is given an option to retry a forced encounter instead of being sent to the room before. Re:Freshed implements this feature to KH2.
7. In KH3, the player is able to press "Prepare and Retry" after dying to enter the loadout menu. Re:Freshed implements this feature into KH2.
8. In KH1, there was a convenient "Encounter Plus" ability to make the grinding experience more bearable. Re:Freshed implements this ability into KH2.
9. CrazyCatz00's English Patch for Kingdom Hearts 2 - Final Mix on the PS2 had an option in the menu to switch from and to English or Japanese voice acting. This mod reimplements that to the games. There's also extra patches to have a 3rd language - it can be German, French or Spanish.
10. In KH3, the player can reorganize their magic menu. This feature is neat, so now it's in KH2. To do this, highlight your magic command and press L2+DPAD to shift around.

## Credits
- **TopazTK** for the original work on [Re:Fined](https://github.com/TopazTK/KH-ReFined).
- **Televo** for almost every asset Re:Freshed uses.
- **Denhonator** for his work on Soft Reset, Volume Mute, and the location of 1FM RAM Saves.
- **Xeeynamo** for the functions used to calculate the Save Checksum.
- **RukaPML** and **Ruby-Chan** for the German translation.
- **Svenchu** and **Mikote11** for the Spanish translation.
- **blobdash** for the French translation.
- **iTeoh** for the Italian translation.
- **CrazyCatz00** for his contributions to Ultrawide Compatibility.
- **TieuLink** for providing the Japanese voices for the Multi Audio Add-on.
- **DA** and **AntonioDePau** for their help with injecting ".a.jp" files for the Multi Audio Add-on.
- **Y2K** for his work on the Prologue Skip.
- **VladABDF** for his work on the Crown Engine.
- **Mikote111** for his work on Alternative Title Screens.
- **Some1fromthedark** for his contributions to the new Configuration System.
- **gg3502** for his help in the SharpHook Engine.
- **MainMemory** for her help in fixing Panacea related issues.

## Third Party Libraries

[DiscordRPC by Lachee](https://github.com/Lachee/discord-rpc-csharp)  
