# VA-11 Hall-A

## Pre-requisites
You need the windows version of the game as the patch does not work with any other platform version.

## Patching the Game
Since the GOG\Steam versions of the game do not have native controller support you will need to patch the game to enable it. Luckily, [mono21400](https://www.moddb.com/mods/controller-mod) has already accomplished this.

Unzip the ```VA-11_HALL-A_Controller_Mod.zip```, launch the ```DeltaPatcherLite.exe```. This is where you will need the windows version of VA-11 Hall-A. Select the ```data.win``` file from the windows version in your VA-11 Hall-A game folder. In DeltaPatcher select the ```data.win``` file for the Original File. Then select the ```ControllerMod_v01.xdelta``` as the XDelta Patch. 

Apply the patch and it should create a new PATCHED version of the data.win file. Rename the ```dataPATCHED.win``` file to ```game.unx```.

## Installing the Port
Copy the contents of ```vallhalla.zip``` into your ports folder on your device. Copy the everything from your VA-11 Hall-A gamedata folder to the ```assets``` folder on your device (minus the executable). 

## Issues 

1. If your game is not launching, re-verify your game files on steam and repatch the ```data.win```. Copy that patched file again into your assets folder after you rename it to ```game.unx```. 

2. Renaming the Linux versions ```game.unx``` file to ```data.win``` then patching it does not work. If you have the linux version, re-download the windows version. The runner is all that is needed from linux and is provided.

3. There is a bug with the jukebox music selection and the controller port. Sometime when a track is selected and added to the playlist or selected from the playlist, the cursor will be trapped unable to navigate back to track selection (No way to exit out without adding all the tracks). Only use "A" to add music and "Y" to remove. I have gotten this a couple times in a row but also been able to navigate the menu without issue on occasion. Just remember to save when you can!
