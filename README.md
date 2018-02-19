
## GTA:SA
The `GTASA.CT` contains:

* A GTASA Utility with some useful features (a Lua script with a GUI), which should work for most GTASA versions
* A list of not very well sorted memory addresses, usually for v1.0

### Getting Started
To use the GTASA Utility, you can either open the `GTASA.CT` in CheatEngine and say "Yes" to running the included script, or run the `GTASA_Util.EXE`, which is a Standalone CheatEngine Trainer based on the script (so you don't need CheatEngine installed).

Once the script is loaded, a window should come up. Just click on "Attach to gta_sa.exe" to open the game process. You can choose to "Enable Auto Attach" to detect the game automatically.

### Usage
Use the "Configure Output" tab to determine what is output. Depending on the type of info it is displayed on either the "Output" (50ms refresh interval) or "Output 2" (1000ms) tab.

You can choose to write some activated values to file by enabling "Writing to file enabled". This can be useful if you want to overlay the values on a video, for example by adding it as a text layer in OBS.

Output:

* Duping Debug Values (50ms): Shows the OnMission variable, if the call holding button is pressed and call info (timer/caller)
* Current Active/Inactive Threads (50ms): Shows what threads the game is currently running
* Some Skills/Stats (1sec): Shows the values for some Skills and Stats (but not all of them)
* Some Skills/Stats Exp (1sec): Shows the progress values for those Skills and Stats, the increase per second and what percentage is completed until the next Skill/Stat upgrade
* Update Other Values (Script defined): What this does may be different per version

Some other features:

* To be able to toggle the ONMISSION variable, enable the appropriate checkbox on the Util tab.
* The "Player Vehicle" shows what vehicle the player is in or was last in. If this is anything other than a bike or empty, then it's an indiciation for the AI weapon accuracy being increased.
