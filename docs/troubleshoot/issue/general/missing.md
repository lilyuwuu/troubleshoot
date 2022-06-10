# Missing "boot.firm"

!!! info "Relax!"
	You aren't bricked.

The file `boot.firm` is missing from the root of your SD card. A 3DS with custom firmware requires the file `boot.firm` on SD card or on internal memory (CTRNAND) in order to boot. If you were directed here, at least of one of the following is probably happening:

- The blue light turns off by itself 
- The notification LED displays a certain color (often white)

To fix this issue, just download the latest release of [Luma3DS](https://github.com/LumaTeam/Luma3DS/releases/latest) and copy `boot.firm` and `boot.3dsx` to the root of the SD card, replacing any existing files.

!!! tip "Additional notes"
	If it still isn't working, you should check the following things:

	- Is the SD card formatted as FAT32? The 3DS can't read any other format.
	- The 3DS may have trouble reading an SD card if it was formatted with MiniTool Partition Wizard or the HP formatting tool. Try formatting it with one of the recommended tools ([Windows](https://3ds.hacks.guide/formatting-sd-(windows)), [macOS](https://3ds.hacks.guide/formatting-sd-(mac)), [Linux](https://3ds.hacks.guide/formatting-sd-(linux))).
	- Is there dust or moisture in the 3DS SD card slot?
	- Do you see a RED or MAGENTA notification LED? These colors indicate file corruption of some sort, meaning that your SD card may be unreliable. In this case, you should check it for errors ([Windows](https://3ds.hacks.guide/h2testw-(windows)), [macOS](https://3ds.hacks.guide/f3xswift-(mac)), [Linux](https://3ds.hacks.guide/f3-(linux))).

[It worked!](/troubleshoot/issue/success){ .md-button }
[It didn't work :(](/troubleshoot/issue/failure){ .md-button }