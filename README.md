# NextUI Arduboy Pak

An [Arduboy](https://www.arduboy.com/) [Libretro](https://www.libretro.com/) core for use with [NextUI](https://nextui.loveretro.games/) to play Arduboy games. Uses the [Ardens](https://github.com/tiberiusbrown/Ardens) project.

## Installation

1. Download the ARDENS.pakz file from the [latest release](https://github.com/amayer5125/nextui-arduboy-pak/releases) on GitHub.
1. Extract the zip file to the root of your SD card. You should see a new ARDENS.pak directory under `/Emus/<platform>` after extracting.
1. Create the `/Roms/Arduboy (ARDENS)` directory on your SD card for your games.

You can download games for free from the [Arduboy Community](https://community.arduboy.com/c/games/35). Place the .hex or .arduboy files in the `/Roms/Arduboy (ARDENS)` directory.

## Debug Logs

If you are having trouble launching games you can look for clues in the debug logs at `/.userdata/<platform>/logs/ARDENS.txt`.
