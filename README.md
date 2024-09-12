# SteamoddedNX - A Balatro ModLoader port for Nintendo Switch

## Prelude

### Warning!
By using this mod you AGREE not to ask for help in the official Balatro server! Discussion of any sort of unofficial console modding of Balatro is forbidden (for their safety.) Doing so will likely result in a warning or a ban from the server. Just don't do it. Secondly, do not bother Steamo or any mod makers on the topic of making their mods work on older versions of Steamodded. Find older versions that work and don't use lovely! 

## Introduction

SteamoddedNX is a mod loader and injector for the game Balatro. Much like the [LÖVE2D engine](https://love2d.org/wiki/Main_Page) itself, it is built using [Lua](https://www.lua.org/). It is made with modularity and extensibility in mind, providing a large selection of APIs and other features to facilitate bringing your ideas to life.

## Installation

### Requirements

- A modded switch
- A legal copy of Balatro for the switch, with the latest update
- A valid python install

### How to Install SteamoddedNX

- Download this repo by clicking the green `Code` button near the top and clicking `Download ZIP`, and extract it som safe.
- Dump your current **update** of Balatro, in NCA FS or romFS format using your favorite NX dump tool.
- Once complete, connect your SD card to your computer, navigate to the dumped update location. Copy the `Patch RomFS` folder to inside your repo extraction folder. Now enter the folder and ZIP the contents of the `Patch RomFS` into a standard ZIP, ensuring that your ZIP contains the dumped files at the root, and are NOT nested in an additional folder inside the ZIP.
- Copy your dumped ZIP inside the safe location of your extracted repo on your computer.
- Drag the ZIP onto `SteamoddedNX_injector.py` and wait for the injector to complete. If you see `Process completed successfully. Press any key to exit...` then continue, if not, check your zip structure.
- Extract the contents of the modded ZIP into the included `\atmosphere\contents\0100CD801CE5E000\romfs` directory.
- This step is not needed but if you would like to see exact crash errors from your mods: while in your romfs folder, open `globals.lua` and jump to `line 62` `self.F_NO_ERROR_HAND =`  Now replace `true` with `false`
- Copy your prepped `atmosphere` folder to your switch sdcard, then launch the game and enjoy Balatro with mods!

## How to Install a Mod

- Find and download a sMODS 0.9.8 compatible mod.
- Navigate to your Mods directory (see the installation instructions).
- Put the mod into that directory. (The mod can be a single file if there is only one file provided, or it can be a whole folder.)
- Launch the game and enjoy!

## Limitations

- Lovely is not supported on the switch, so mods that require it will NOT work.
- Limited to mods that function on 0.9.8 version of sMOD. This means you may need to find an older version of a mod you want to play, if it already doesn't require lovely.
- Card suit customization introduced in version 1.0.1g (Friends of Jimbo) will not work.

## Thanks

Thanks to Steamo and co for helping develop such a versatile tool that basically works on any platform. I only needed to make a couple of minor adjustments to make this not crash on switch.
Thank you to the mod community that make amazing add-ons and of course thanks to localthunk for making such an amazing, addictive game.

## License

This project is licensed under the GNU General Public License. This ensures that the software is free to use, modify, and distribute. For more details, click [here](https://github.com/Steamopollys/Steamodded/actions?tab=GPL-3.0-1-ov-file)
