# VA-11 Hall-A

## Pre-requisites
To play the game on the RG351 you will need the linux version of this game. BUT there is one file that you will need from the windows version of the game. Have both versions of the game on hand for install. 

You can get this a number of ways...
(GOG\HumbleBundle\Install Steam on a Linux machine\etc.)
## Patching the Game
Since the GOG\Steam versions of the game do not have native controller support you will need to patch the game to enable it. Luckily, [mono21400](https://www.moddb.com/mods/controller-mod) has already accomplished this.

Unzip the ```VA-11_HALL-A_Controller_Mod.zip```, launch the ```DeltaPatcherLite.exe```. This is where you will need the windows version of VA-11 Hall-A. Copy the ```data.win``` file from the windows version somewhere on your pc. In DeltaPatcher select the ```data.win``` file for the Original File. Then select the ```ControllerMod_v01.xdelta``` as the XDelta Patch. 

Apply the patch and it should create a new PATCHED version of the data.win file. Rename the ```dataPATCHED.win``` file to ```game.unx```. Copy the ```game.unx``` file into the assets folder in the Linux version of VA-11 Hall-A and replace the existing one. 

## Installing the Port
Copy the contents of ```vallhalla.zip``` into your ports folder on your device. Copy everything from the linux version of VA-11 Hall-A into the vallhalla folder you just added. 
