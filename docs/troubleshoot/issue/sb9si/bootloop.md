# 3DS always boots into SafeB9SInstaller

![Image](/images/sb9si/loop.png)

`SafeB9SInstaller.firm` is currently set as your `boot.firm`, so your 3DS will always boot into it. To fix this:

1. When you see the key combo prompt, force power off your device by holding the power button for 15 seconds.

    !!! danger "Careful!"
	    Do **NOT** force power off the device if SafeB9SInstaller isn't idle (that is, you see a progress bar on the top)! If you do, you may brick the device!

1. Insert your SD card into your computer
1. Download the latest release of [Luma3DS](https://github.com/LumaTeam/Luma3DS/releases/latest) and copy `boot.firm` and `boot.3dsx` to the root of the SD card, replacing any existing files
1. Reinsert your SD card into your 3DS

![Image](/images/sb9si/loop-root.png)

{% include-markdown "../../../includes/successfail.md" %}