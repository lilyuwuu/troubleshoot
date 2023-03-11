# Browser update required

![Image](/images/ssloth/browserupdate.png)

First, make sure you entered the correct proxy for the connection you're using. If not, go back to [Section II](https://3ds.hacks.guide/installing-boot9strap-(ssloth-browser).html#section-ii---ssloth). If the proxy is correct, then your device has been cart-updated, which means an alternate exploit will need to be used.

## Method 1
If the two numbers before the region in the system version string is equal to or less than 36 (e.g. Ver. 11.14.0-**36**U), you can follow [Soundhax](https://3ds.hacks.guide/installing-boot9strap-(soundhax)). When prompted to select a firmware to generate the sound file, use:

* 1.x - 2.1 if the number is between 0 and 2
* 2.1 - 2.2 if the number is between 3 and 4
* 3.x - 4.x if the number is between 5 and 10
* 5.x - 11.3 if the number is between 11 and 36

## Method 2 (Old 3DS only)
If you have an Old 3DS / Old 3DS XL / 2DS, you can try a Safe Mode update, which will trigger an alternate exploit:

1. Ensure that the proxy that you used for SSLoth is still actively applied to your internet connection
1. With your device powered off, hold the following buttons: (Left Shoulder) + (Right Shoulder) + (D-Pad Up) + (A), and while holding these buttons together, power on your device
  + Keep holding the buttons until the device boots into Safe Mode (a "system update" menu)
1. Press "OK" to accept the update
1. If everything worked correctly, the update will fail and the 3DS will boot into SafeB9SInstaller. If it did, then continue from [Section IV](https://3ds.hacks.guide/installing-boot9strap-(ssloth-browser)#section-iv---installing-boot9strap).
  + If you are now encountering an issue with SafeB9SInstaller, continue troubleshooting from [here](/troubleshoot/guide/sb9si).
  + If the update ended up *actually* updating your console to the latest firmware, continue from [Seedminer](https://3ds.hacks.guide/seedminer).

{% include-markdown "../../../includes/support.md" %}
