![combined_no_shadow_or_logo](https://github.com/TopazTK/KH-ReFined/assets/95656963/482d02f4-66f6-4b7e-8b73-06c1635da2ef)

## Download

Get the latest v3.00 release by clicking the button below.

[![KH-ReFreshed](https://img.shields.io/badge/Kingdom_Hearts_Re:Freshed-Download-blue.svg)](https://github.com/KH-ReFreshed/KH-ReFreshed/releases/tag/v3.00)

If you're going to play Kingdom Hearts II, see [the v4.00 branch instead](https://github.com/KH-ReFreshed/KH-ReFreshed/tree/v4-dev).

## Installation

### Without Dual Audio
- Drag the EXE unto the game directory.
- Rename the dragged EXE to the name of the original ones (Ex. "KINGDOM HEARTS FINAL MIX" for KH1)
- Tada! You have installed it.

### With Dual Audio
- Drag the EXE unto the game directory.
- Rename the dragged EXE to the name of the original ones (Ex. "KINGDOM HEARTS II FINAL MIX" for KH2)
- Download the patch in https://bit.ly/DualAudioBBS for BBS, the one in https://bit.ly/DualAudioKH2 for KH2, and the one in https://bit.ly/DualAudioDDD for DDD.	
- Download KHPCPatchManager v1.2.0 or higher from https://github.com/AntonioDePau/KHPCPatchManager/releases.
- Patch both the games with the patches you downloaded. Instructions are at: https://github.com/AntonioDePau/KHPCPatchManager/blob/main/README.md
- Done! You now have Re:Freshed with Dual Audio!

## Discord

For all kinds of technical support and discussion, join the Discord Server:  

[![Discord](https://img.shields.io/badge/Kingdom_Hearts_Re:Freshed-Discord-purple)](https://discord.gg/8JWQjuxqbB)

## Features

### All Games

| Error/Bug Fix | Enhancement | Description |
|---------------|-------------|-------------|
| :heavy_check_mark: | - | Disable cutscene framelimiter. [[1]](#reference) |
| :heavy_check_mark: | - | The Mouse Cursor will now follow a VirtualBox-style capture mechanism. |
| :heavy_check_mark: | - | The game will no longer infinitely freeze while shutting down. |
| :heavy_check_mark: | - | The game will no longer crash OBS after a resize. |
| :heavy_check_mark: | - | Added the ability to launch and play the game whilst offline. |
| :heavy_check_mark: | - | Removed savefile Epic ID check. [[2]](#reference) |
| - | :heavy_check_mark: | Voice channels will now be muted when set to "1" in the PC settings menu. |
| - | :heavy_check_mark: | Autosaving functionality, utilizing Slot #99. |
| - | :heavy_check_mark: | An RPC Engine is now present for use with Discord. |
| - | :heavy_check_mark: | The MP bar will no longer be present until Sora learns his first magic. [[3]](#reference)| 
| - | :heavy_check_mark: | Soft reset implementation (R1 + L1 + START + SELECT) |
| - | :heavy_check_mark: | Create a game-specific configuration file named `config_xxx.dat` so that changes only have effects on a per-game basis. |
| - | :heavy_check_mark: | Moved savefiles to a more suitable place. Please move them if you had some already! [[4]](#reference) |

### Kingdom Hearts 1

| Error/Bug Fix | Enhancement | Description |
|---------|-------------|-------------|
| :heavy_check_mark: | - | Fixed an issue with cutscenes, preventing pausing + skipping during a fade effect. |
| :heavy_check_mark: | - | Fixed the `Title Screen` option in the save menu so it no longer crashes the game. |
| :heavy_check_mark: | - | Restore the ability to exit the game from the title screen. |
| - | :heavy_check_mark: | Added a toggle in the Camp Menu to switch between original and a KH2-like improved field of view. |
| - | :heavy_check_mark: | Abilities can now be toggled with Triangle just like in KH2. | 
| - | :heavy_check_mark: | Autodetect the correct screen aspect ratio when in fullscreen. |
| - | :heavy_check_mark: | Added the ability to Auto Attack by holding down the configured attack button. It will trigger everywhere except the World Map. Toggleable through the config file. |
| - | :heavy_check_mark: | Added the ability to enforce either Controller or MKB Prompts through the config file. |

### Kingdom Hearts 2

| Error/Bug Fix | Enhancement | Description |
|---------|-------------|-------------|
| :heavy_check_mark: | - | Correct Limit Form's Limit names so that they are more accurately translated. [[5]](#reference) |
| - | :heavy_check_mark: | Drive Forms will now appear in the inventory. | 
| - | :heavy_check_mark: | It is now possible to customize Limit Form's Shortcut Menu. |
| - | :heavy_check_mark: | It is now possible to unpause the Atlantica Musical segments. |
| - | :heavy_check_mark: | The `Kingdom Hearts` Command Menu setting will now display a menu that is more resembling of the menu from the first game. |
| - | :heavy_check_mark: | Include an option upon selecting `New Game` to skip Roxas' introduction sequence. |
| - | :heavy_check_mark: | The player is now able to reorganize the Magic menu to their liking. [[6]](#reference) | 
| - | :heavy_check_mark: | Dual-Audio capabilities, allowing one to switch from and to English or Japanese vocals. [[7]](#reference) |  
| - | :heavy_check_mark: | The party will now switch up their attire at appropriate times. [[8]](#reference) | 
| - | :heavy_check_mark: | The player can now retry all forced encounters on command, and can choose to continue via the D-Pad. [[9]](#reference) |

### Kingdom Hearts - Birth by Sleep

BBS support is currently broken and you *will* experience issues, such as crashes.

| Error/Bug Fix | Enhancement | Description |
|---------|-------------|-------------|
| :heavy_check_mark: | - | Fix an issue with 30fps being forced when talking to people. | 
| :heavy_check_mark: | - | Add back the ability to rename finishers. |
| - | :heavy_check_mark: | Dual-Audio capabilities, allowing one to switch from and to English or Japanese vocals. [[7]](#reference) |  

### Kingdom Hearts - Dream Drop Distance

| Error/Bug Fix | Enhancement | Description |
|---------|-------------|-------------|
| - | :heavy_check_mark: | Added the ability to toggle the Drop Gauge. |
| - | :heavy_check_mark: | Dual-Audio capabilities, allowing one to switch from and to English or Japanese vocals. [[7]](#reference) | 
| - | :heavy_check_mark: | Added the ability to start with Critical difficulty without playing Proud first. |

#### Reference

1. Cutscenes will by default lock the game to 30fps. This alleviates that.
2. The savefiles are DRM'd normally - meaning you can't share savefiles with other people. Re:Freshed removes that DRM.
3. Sora/Roxas immediately have MP Bars when the game begins, despite having no magic. This fix will now make said MP bar invisible until the player learns their first magic spell. (Usually Fire in KH1, Blizzard in KH2.)
4. The game originally saves everything to `Documents/KINGDOM HEARTS HD 1.5+2.5 ReMIX\Epic Games Store\[EGS ID]`. Re:Freshed changes the path to `Documents\Kingdom Hearts\Save Data\[EGS ID]`.
5. In the HD remaster of KH2, the localization team changed the translation of certain attacks to contrast with their usual translations from Japanese. E.g. Ragnarok -> Infinity. This fix reverts that awful decision. 
6. In KH3, the player can reorganize their magic menu. This feature is neat, so now it's in KH2. To do this, highlight your magic command and press L2+DPAD to shift around.
7. CrazyCatz00's English Patch for Kingdom Hearts 2 - Final Mix on the PS2 had an option in the menu to switch from and to English or Japanese voice acting. This mod reimplements that to the games. There's also extra patches to have a 3rd language - it can be German, French or Spanish.
8. The party will wear their Halloween costumes in the days between October 31st and November 2nd (inclusive). Whilst they wear their Christmas costumes in the days between December 24th and January 1st (also inclusive).
9. Starting in Birth by Sleep, the player is given an option to retry a forced encounter instead of being sent to the room before. Re:Freshed implements this feature to KH2 and it will replace the continue option. To revert back to and from the continue option, you can use the left and right D-Pad buttons.

## Credits

### All Games
- **TopazTK** for the original work on [Re:Fined](https://github.com/TopazTK/KH-ReFined).
- **Televo** for almost every asset Re:Freshed uses.
- **Denhonator** for his work on Soft Reset, Volume Mute, and the location of 1FM RAM Saves.
- **Xeeynamo** for the functions used to calculate the Save Checksum.
- **RukaPML** and **Ruby-Chan** for the German translation.
- **Svenchu** and **Mikote11** for the Spanish translation.
- **blobdash** for the French translation.
- **iTeoh** for the Italian translation.

### Kingdom Hearts 1
- **Denhonator** for his work on Cutscene Skip.

### Kingdom Hearts 2
- **CrazyCatz00** for his contributions to Ultrawide Compatibility.
- **TieuLink** for providing the Japanese voices for the Multi Audio Add-on.
- **DA** and **AntonioDePau** for their help with injecting ".a.jp" files for the Multi Audio Add-on.
- **Y2K** for his work on the Prologue Skip.
- **VladABDF** for his work on the Crown Engine.
- **Mikote111** for his work on Alternative Title Screens.
- **Some1fromthedark** for his contributions to the new Configuration System.
- **gg3502** for his help in the SharpHook Engine.
- **MainMemory** for her help in fixing Panacea related issues.

### Kingdom Hearts - Birth by Sleep
- **TopazTK** for everything so far.

### Kingdom Hearts - Dream Drop Distance
- **Explode** for his work on Drop Bar Toggling.

## Third Party Libraries

- [DiscordRPC by Lachee](https://github.com/Lachee/discord-rpc-csharp)  
- [DotNetZip by DinoChiesa](https://github.com/DinoChiesa/DotNetZip)
- [Octokit.NET by GitHub](https://github.com/octokit/octokit.net)
- [NAudio by Mark Heath](https://github.com/naudio/NAudio)
