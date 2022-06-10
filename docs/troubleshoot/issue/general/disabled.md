# An error has occurred. Hold down the POWER button to turn off the power...

ARM11 exception handlers are disabled, or you don't have custom firmware installed.

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

If you don't have custom firmware installed, you are probably bricked and can only attempt to unbrick your device with [ntrboot](https://3ds.hacks.guide/ntrboot).

[Go to Nintendo Homebrew (Discord)](https://discord.gg/MWxPgEp){ .md-button }

[Back to "Error on boot"](/troubleshoot/noboot/error){ .md-button }


