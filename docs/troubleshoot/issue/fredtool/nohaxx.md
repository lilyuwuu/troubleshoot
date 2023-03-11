# "Haxxxxxxxxx!" does not appear

![Image](/images/fredtool/nohaxx.png)

There is an issue with your `42383821.bin` file (it is incorrect, missing, misplaced, or corrupted). Specifically:

- If you see "No accessible software data", you don't have `42383841.bin` in `Nintendo 3DS` -> `<ID0>` -> `<ID1>` -> `Nintendo DSiWare`
- If you see the question mark, your file is corrupted and/or you used the wrong `movable.sed` file when creating it
- If you see "Nintendo DSi", you copied the `42383841.bin` from the "clean" folder instead of the "hax" folder

Re-follow [Section III of Fredtool](https://3ds.hacks.guide/installing-boot9strap-(fredtool)#section-iii---prep-work). Make sure that you now only have the `42383841.bin` file from the `hax` folder in the `Nintendo 3DS` -> `<ID0>` -> `<ID1>` -> `Nintendo DSiWare` directory:

![Image](/images/fredtool/dsiware-location-4.png) 

{% include-markdown "../../../includes/successfail.md" %}