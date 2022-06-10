# An error has occurred. Hold down the POWER button...

Your `00000001.sav` and/or `otherapp.bin` files may be misplaced. Ensure that `00000001.sav` is in `Nintendo 3DS` -> `<ID0>` -> `<ID1>` -> `title` -> `00040000` -> `0017c100` -> `data` and that `otherapp.bin` is on the root of your SD card.
	
- For reference, the root of the SD card is the directory where you can see the `Nintendo 3DS` folder, but aren't inside of it.


If your files are in the correct locations, then:

- Re-create the save using the [PicHaxx Save Tool](https://3ds.nhnarwhal.com/3dstools/pichaxx.php), then place it in `Nintendo 3DS` -> `<ID0>` -> `<ID1>` -> `title` -> `00040000` -> `0017c100` -> `data`. Ensure that the file is named exactly `00000001.sav` and that you used your console's `movable.sed` to create it. 
- Re-download the latest release of [universal-otherapp](https://github.com/TuxSH/universal-otherapp/releases/latest) and place it on the root of your SD card. Do not add the `.bin` extension if you do not already see it.

[It worked!](/troubleshoot/issue/success){ .md-button }
[It didn't work :(](/troubleshoot/issue/failure){ .md-button }