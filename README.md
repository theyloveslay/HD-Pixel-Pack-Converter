# HD-Pixel-Pack-Converter
A tool to convert the MHGU HD Pixel Pack to work for MHXX Nintendo Switch Ver. Also includes an English Patch based on [Klark231's MHXX 3DS English Patch](https://gbatemp.net/threads/mhxx-complete-english-patch.609362/)

Note that some XX exclusive gear may or may not be retextured. I do not plan on creating new textures for those at this moment.

# Requirements
- HD Pixel Pack (Manual Install). You can download it [here](https://www.reddit.com/r/MonsterHunter/comments/1icfs4z/mhgu_hd_texture_mod_60_fps_and_multiplayer_2025/)
- A dump of the game's romFS (search how to do it for CFW Switch or emulator)
- Python 3.10.0 or higher
- Windows 10/11 (will provide Linux script in the future)

# Installation
1. Download the latest HDPixelPackConverter.zip
2. Extract and run Run-Converter.zip
- Select the HD Pixel Pack you installed in step 1
- Select the game's romFS dump
- Put in whatever glyphs that you want to use
- Select if you want HD or classic icons
- Lastly, choose the location of the converted textures. Ideally this should be your emulator's mod data location (if using on CFW Switch, put it anywhere on your computer)
3. Once fully converted, enable the mod and launch the game.
- If on a CFW Switch, put the textures in sdcard:/atmosphere/content/[Game ID]/romfs/

# Event Quest Information
Event quests by default will still be in Japanese. This is because they store their text inside of your save file rather than the game's text files.
I have already prepared a clean DLC save that includes all DLC + translated text. This can be found in HDPixelPackConverter/assets/CleanDLCSave

If starting fresh, just simply put the system file into your save location.

If using an existing save, this requires some extra setup. Make sure to back up your save files in case anything goes wrong.
1. Launch the game
2. Go to your room in any of the villages
3. Open your save location and replace your save file with the clean DLC save
4. Save the game at your bed. Do not close the game.
If saving the game worked, then you can safely save and quit. The translated event quest should now be present.

If you're on a CFW Switch, I have no idea how to add the translated DLC to an existing save file. For now I suggest you perform this on an emulator and then transfer your save back.

# Credits
Pixel Clover for distributing the HD Pixel Pack
Monkbruh for creating the MHGU HD Project
Klark231 for creating the MHXX 3DS English Patch
Capcom for creating Monster Hunter Generations Ultimate and Double Cross Nintendo Switch Ver.

# Other Suggested Mods/Cheats
[MHXX Nintendo Switch Ver. 60FPS Cheat by masagrator](https://gbatemp.net/threads/monster-hunter-generations-ultimate-60-fps-hack.553053/)
