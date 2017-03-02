
## Dark Souls 1 Deathcounter

I just quickly wrote this automatic death counter for my own stream. It reads the deaths from the game memory.
I found the pointer path in another death counter ([DS1DC](https://github.com/numberkruncher/DS1DC)) but preferred
to write my own little script which writes it to a file.
I haven't tested this much, so it may or may not work for you. Use it at your own discretion. :)

* The `DarkSoulsDC.CT` contains a Lua Script/Form for use in CheatEngine. Just open it in CheatEngine and say "Yes" to running the script.
* The `DarkSoulsDC.EXE` is a Standalone CheatEngine Trainer (so you don't need CheatEngine installed) based on the script.

Once the script is loaded, a window should come up and it should detect Dark Souls 1 automatically.

* Make sure to select the file to save to before enabling "Write to file"
* The "Output" is what is written to the textfile, with `$d` being replaced with the number of deaths
* The "Force Refresh" button writes to the file immediately (otherwise it only does it on a timer and when the output changes)
* Close the window (or CheatEngine when using the script) to stop the program
* CheatEngine handles saving the settings (I believe they are stored in the Registry, search the Registry for "dsdcform" if you're looking for it for some reason)
