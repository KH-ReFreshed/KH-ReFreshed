![image](https://user-images.githubusercontent.com/95656963/171788826-e2049957-b00b-4502-87e9-6cf7df9d8efd.png)

## Download

Get the latest v1.50 release by clicking the button below.

[![KH-ReFixed](https://img.shields.io/badge/KH--ReFixed-Download-blue.svg)](https://github.com/KH-ReFreshed/KH-ReFreshed/releases/tag/v1.50)

This release is out of date. See the [main branch](https://github.com/KH-ReFreshed/KH-ReFreshed/) for up-to-date source code and releases.

## Features

### All Games

| Error/Bug Fix | Enhancement | Description |
|---------------|-------------|-------------|
| :heavy_check_mark: | - | Disable cutscene framelimiter. [[1]](#reference) |
| - | :heavy_check_mark: | Voice channels will now be muted when set to "1" in the PC settings menu. |
| - | :heavy_check_mark: | Autosaving functionality, utilizing Slot #99. This functionality is toggleable. |
| - | :heavy_check_mark: | An RPC Engine is now present for use with Discord. |
| - | :heavy_check_mark: | The MP bar will no longer be present until Sora learns his first magic. [[2]](#reference) | 
| - | :heavy_check_mark: | Press START + SELECT to soft reset. |
| - | :heavy_check_mark: | Every game has an update agent built-in, so Re:Fixed can keep itself updated. |
| - | :heavy_check_mark: | Creates a game-specific configuration file named `config_xxx.dat` so that changes only have effects on a per-game basis. |

### Kingdom Hearts 1

| Error/Bug Fix | Enhancement | Description |
|---------|-------------|-------------|
| :heavy_check_mark: | - | The player can now open chests and examine objects while in combat. |
| :heavy_check_mark: | - | Fix an issue with cutscenes, preventing pausing + skipping during a fade effect. |
| :heavy_check_mark: | - | Fix the `Title Screen` option in the save menu so it no longer crashes the game. |
| - | :heavy_check_mark: | Autodetect the correct screen aspect ratio when in fullscreen. |
| - | :heavy_check_mark: | ??? |


### Kingdom Hearts 2

| Error/Bug Fix | Enhancement | Description |
|---------|-------------|-------------|
| :heavy_check_mark: | - | Fix an issue with 60fps being locked in certain scenarios. | 
| :heavy_check_mark: | - | Correct an issue with Limit Form's shortcuts being misplaced when O/B is used to confirm. |
| :heavy_check_mark: | - | Correct Limit Form's Limit names so that they are more accurately translated. [[3]](#reference) |
| - | :heavy_check_mark: | The `Kingdom Hearts` Command Menu setting will now display a menu that is more resembling of the menu from the first game. |
| - | :heavy_check_mark: | Include an option upon selecting `New Game` to skip Roxas' introduction sequence. |
| - | :heavy_check_mark: | The player is now able to reorganize the Magic menu to their liking. [[4]](#reference) | 

### Kingdom Hearts - Birth by Sleep

| Error/Bug Fix | Enhancement | Description |
|---------|-------------|-------------|
| :heavy_check_mark: | - | Fix an issue with 30fps being forced when talking to people. | 
| :heavy_check_mark: | - | Add back the ability to rename finishers. [[5]](#reference) |

#### Reference

1. Cutscenes will by default lock the game to 30fps. This alleviates that.
2. Sora/Roxas immediately have MP Bars when the game begins, despite having no magic. This fix will now make said MP bar invisible until the player learns their first magic spell. (Usually Fire in KH1, Blizzard in KH2.)
3. In the HD remaster of KH2, the localization team changed the translation of certain attacks to contrast with their usual translations from Japanese. E.g. Ragnarok -> Infinity. This fix reverts that awful decision. 
4. In KH3, the player can reorganize their magic menu. This feature is neat, so now it's in KH2. To do this, highlight your magic command and press L2/LT+DPAD to shift around.
5. In the PC and Xbox ports of Birth by Sleep, the ability to rename the finishers has been removed. This fix adds that feature back, bound to Tri/Y, popping up a window to allow for renames. (Before you judge me for using a window, this is basically how the PSP goes about doing this, too.)

## Credits

### All Games
- TopazTK for the original work on [Re:Fined](https://github.com/TopazTK/KH-ReFined).
- Televo for the icons used in Discord Rich Presence and the Executables.
- KSX for his work on the MP Bar enhancement.
- Denhonator for his work on Soft Reset, Volume Mute, and the location of 1FM RAM Saves.
- Xeeynamo for the functions used to calculate the Save Checksum.

### Kingdom Hearts 1
- Denhonator for his work on Cutscene Skip.
- TopazTK for everything else.

### Kingdom Hearts 2
- Stickman Sham for the idea that led to Magic Reorganization.
- Drahsid for his work on the 60FPS Framelock Issue.
- Y2K for his work on the Roxas Skip.
- TopazTK for everything else.

### Kingdom Hearts - Birth by Sleep
- TopazTK for everything so far.

## Third Party Libraries

[DiscordRPC by Lachee](https://github.com/Lachee/discord-rpc-csharp)  
[DotNetZip by DinoChiesa](https://github.com/DinoChiesa/DotNetZip)  
[Octokit.NET by GitHub](https://github.com/octokit/octokit.net)

