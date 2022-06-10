# Game starts normally

Your modified `00000001.sav` file may be misplaced, or you may have used the wrong `movable.sed` when creating it. 

- Re-obtain your `movable.sed` from [Bruteforce Movable](https://seedminer.hacks.guide), making absolutely sure that you have used the correct ID0 (if in doubt, [check](/troubleshooting/issue/seedminer/multiid0))
	- If the website skips to Step 4, it is entirely normal.
- Re-create the save using the [PicHaxx Save Tool](https://3ds.nhnarwhal.com/3dstools/pichaxx.php) and place the resulting file (`00000001.sav`) in `Nintendo 3DS` -> `<ID0>` -> `<ID1>` -> `title` -> `00040000` -> `0017c100` -> `data`.

![PicHaxx save location](/images/pichaxx-save-location.png)

[It worked!](/troubleshoot/issue/success){ .md-button }
[It didn't work :(](/troubleshoot/issue/failure){ .md-button }