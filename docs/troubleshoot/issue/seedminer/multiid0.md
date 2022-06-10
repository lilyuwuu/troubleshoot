# Multiple ID0s in Nintendo 3DS folder

This occurs when you use your SD card in multiple 3DS devices and is intended to prevent inadvertently merging data that would not be valid on other devices. To figure out which long folder name is correct for your 3DS, follow these instructions:

1. Rename the `Nintendo 3DS` folder to `BACKUP_Nintendo 3DS`
1. Reinsert your SD card into your device and power on your device
1. Wait for the device to generate the SD card data
	- Your applications will have disappeared. This is normal and will be resolved shortly
1. Power off your device and reinsert your SD card into your computer
1. Navigate to the Nintendo 3DS folder on your SD card
1. Copy the 32 character long name of the folder you see
	- This is your true ID0 that you will use in Section II of Seedminer
1. Delete the `Nintendo 3DS` folder
1. Rename the `BACKUP_Nintendo 3DS` folder to `Nintendo 3DS`

[It worked!](/troubleshoot/issue/success){ .md-button }
[It didn't work :(](/troubleshoot/issue/failure){ .md-button }