# NAND backup fail

![Image](/images/finalize/backupfail.png)

Make sure you have at least 1.3GB available in your SD card. If you don't have enough space, follow these steps:

1. Power off your console
1. Remove the SD card and insert it into your computer
1. Copy the `Nintendo 3DS` folder from the root of your SD card to your computer
1. Delete the Nintendo 3DS folder from the SD card
1. Power off your console, hold START and power on still holding START to boot on GodMode9
1. Perform a [NAND Backup](https://3ds.hacks.guide/godmode9-usage#creating-a-nand-backup)
1. Copy the files in `gm9/out` on your SD to a safe location on your computer
1. Delete the `<date>_<serialnumber>_sysnand_##.bin` and `<date>_<serialnumber>_sysnand_##.bin.sha` files from the SD card, keeping essential.exefs in `/gm9/out/`
1. Copy the `Nintendo 3DS` folder from your computer to the root of your SD card
1. Delete the `Nintendo 3DS` folder from your computer

If you have enough space on your SD card, your SD might be corrupted or faulty. Check your SD card for any errors by following the guide according to your computer's operating system: [Windows](https://3ds.hacks.guide/h2testw-(windows)), [Linux](https://3ds.hacks.guide/f3-(linux)), [macOS](https://3ds.hacks.guide/f3xswift-(mac)).

{% include-markdown "../../../includes/support.md" %}