OpenVR Fly

CAUTION: This program allows you to fly without restrictions to your movement or vision. Be careful if you get motion sickness in VR. Setting the maximum speed lower may help. Also, try setting RestrictVision to true.

NOTE: Please don't share this program with anyone else or use it to cheat. In single player, you can define cheating however you want, but you can't brag about a high score achieved using this program. In multiplayer, only use this in private games when everyone in the game is OK with it. This feature is sure to be patched out either by individual games or by SteamVR if too many people are found abusing it.

Running the program:
Run "OpenVrFly.exe" to run the program.
Run "Install OpenVR Fly.bat" to install OpenVR Fly in the current folder, which will make it start automatically when SteamVR starts.
Run "Uninstall OpenVR Fly.bat" to no longer start OpenVR Fly from the current folder automatically when SteamVR starts.

Instructions:
NOTE: You can define your own custom configurations. These instructions apply to the default configuration.
Double press the grip button to enable flying for that controller.
Control your fly speed and direction using the touchpad (move your finger away from its starting position to move faster).
Press the grip button while flying is enabled to return to your original location.
Hold the grip button until the controller vibrates to disable flying for that controller.
Enjoy your flight!

Configuration:
In the Config folder, copy "Template.txt" and rename it to begin with a number from 1 to 9. Press that number while the program is running to load that configuration. By default, the lowest numbered configuration file will be loaded, or the default configuration if no custom configurations are defined.

Log Files Tip:
SteamVR seems to write a lot of data to log files as you are flying, including the following on my system:
* STEAM_INSTALL_DIR\logs\vrclient_OpenVrFly.txt
* STEAM_INSTALL_DIR\logs\vrcompositor.txt
* C:\Program Files (x86)\ViveSetup\PCClient\web\apps\phone\vivephoneinit\log.txt
I'm not sure if this would cause problems, but I resolved it by clearing those files and removing permissions to access them:
1. Right click the file and go to Properties.
2. Click the Security tab.
3. Click Edit...
4. Select Users.
5. Check the Deny box next to "Full control".
Just remember that you will no longer have permission to access the file, even to delete it, until you revert the settings.
