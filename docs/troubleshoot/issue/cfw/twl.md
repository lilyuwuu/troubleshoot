# TWL mode functionality issues

To fix any TWL mode issues, we can delete our TWL titles and then re-download them from Nintendo's system update server.

1. Download the latest release of [TWLFix-CFW](https://github.com/MechanicalDragon0687/TWLFix-CFW/releases/latest) (the `.3dsx` file)
1. Power off your device
1. Create a folder named `3ds` on the root of your SD card if it does not already exist
1. Copy `TWLFix-CFW.3dsx` to the `/3ds/` folder on your SD card
1. Reinsert your SD card into your device
1. Open the Homebrew Launcher
1. Launch TWLFix-CFW from the list of homebrew
1. Press (A) to uninstall the broken TWL titles
1. Press (Start) to reboot the device
1. Perform a System Update by going to System Settings, then "Other Settings", then going all the way to the right and using "System Update"
  + The update will see that the essential TWL titles have been uninstalled, and will redownload and reinstall them
1. Once the update is complete, tap "OK" to reboot the device 

[It worked!](/troubleshoot/issue/success){ .md-button }
[It didn't work :(](/troubleshoot/issue/failure){ .md-button }