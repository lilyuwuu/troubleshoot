# Black screen forever

Oh, that sucks. Could be anything, really. Let's try some things one by one (easiest to hardest).

## Before we start: Luma3DS Check

You should make sure you have the latest version of Luma3DS before trying these steps. Having an old custom firmware might be the reason you're having this issue, too.

[Go to Checking for CFW](https://3ds.hacks.guide/checking-for-cfw){ .md-button }

## Solution 1: SD Card Slot

Your SD card may have just gotten knocked out of place.

1. Power off your device
1. Eject your SD card
1. Reinsert your SD card, ensuring no dust is in the SD slot

## Solution 2: RTC Bug

You may be encountering the RTC bug (otherwise known as "Luma bug", despite having nothing to do with Luma3DS). On new installations, due to a bug with the real-time clock, the 3DS may take an exceptionally long time to boot.

1. Power off your device
1. Eject any inserted game cartridge (if one is inserted)
1. Power on your device
1. Wait up to ten minutes

If your 3DS is now booting, the issue is resolved and shouldn't occur again unless your RTC battery dies.

## Solution 3: Nintendo 3DS folder

It is possible that there is something weird with your `Nintendo 3DS` folder that's causing you to be unable to boot.

1. Power off your device and insert your SD card into your computer
1. Rename the `Nintendo 3DS` folder to `Nintendo 3DS_BACKUP`
1. Insert your SD card into your device and attempt to boot

If your 3DS is now booting, there is probably an issue with your `Nintendo 3DS` folder. Try deleting HOME Menu extdata:

1. Power off your device and insert your SD card into your compter
1. Navigate to `Nintendo 3DS` -> `<ID0>` -> `<ID1>` -> `extdata` -> `00000000`
1. Delete the folder corresponding to your 3DS region:
	- USA: `0000008f`
	- EUR: `00000098`
	- JPN: `00000082`
	- KOR: `000000A9`
	- TWN: `000000B1`
	- CHN: `000000A1`
1. Insert your SD card into your device and attempt to boot

## Solution 4: Check ARM11 exception handlers

If ARM11 exception handlers are disabled, they may be hiding an on-boot error. Make sure they are enabled.

### Luma3DS v11.0 and newer

1. Power off your device and insert your SD card into your computer
1. Navigate to the `luma` folder and open `config.ini` with a text editor
1. Scroll to the bottom of the file
1. If `disable_arm11_exception_handlers` is set to `1`, change it to `0`

### Luma3DS v10.3 and older

1. Power off your device
1. Hold (Select)
1. Power on your device, while still holding (Select)
1. If you see a `(x)` next to `Disable ARM11 exception handlers`, uncheck it

If you are now able to see an error on boot, click the button below.

[Error on boot](/troubleshoot/noboot/error){ .md-button }

## Solution 5: Recovery Mode

It probably won't work, but you can try updating your device using Recovery Mode.

1. Power off your device
1. Hold (Left Shoulder) + (Right Shoulder) + (D-Pad Up) + (A)
1. Power on your device while still holding those four buttons
1. Follow the prompts to update your device

## Solution 6: CTRTransfer

Performing a CTRTransfer will replace your system files with known clean versions.

[Go to CTRTransfer](https://3ds.hacks.guide/ctrtransfer){ .md-button }

---

[Issue was resolved](/troubleshoot/issue/success){ .md-button }

[Issue not resolved](/troubleshoot/issue/failure){ .md-button }

