
## Dark Souls 1 Deahtcounter

I just quickly wrote this automatic death counter for my own stream. It reads the deaths from the game memory.
I found the pointer path in another death counter ([DS1DC](https://github.com/numberkruncher/DS1DC)) but preferred
to write my own little script which writes it to a file.
I haven't tested this much, so it may or may not work for you. Use it at your own discretion. :)

* The `DarkSoulsDC.CT` contains a Lua Script/Form for use in CheatEngine. Just open it in CheatEngine and say "Yes" to running the script.
* The `DarkSoulsDC.EXE` is a Standalone CheatEngine Trainer (so you don't need CheatEngine installed) based on the script.

Once the script is loaded, a window should come up and it should detect Dark Souls 1 automatically.

* Make sure to select the file to save to before enabling "Write to file"
* The Prefix is put before the number of deaths (for example enter "Deaths: ")
* The "Force Refresh" button writes to the file immediately (otherwise it only does it when the number of deaths change)
* Just close the window (or CheatEngine when using the script) to stop the program
* CheatEngine handles saving the settings (I believe they are stored in the Registry, search it for "dsdcform" if you're looking for it for some reason)
