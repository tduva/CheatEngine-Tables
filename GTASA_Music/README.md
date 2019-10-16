This CheatEngine Lua script reads memory to automatically trigger a hotkey when CJ enters/leaves certain areas that forcibly play music.

Should support all GTA:SA versions that the autosplitter also supports.

Areas muted are:

* Beach Dance (during Life's A Beach)
* Lowrider Dance (during Cesar Vialpando)
* Bloodbowl
* LS Stadium
* Four Dragons Casino
* Caligulas Casino
* Saint Mark's Bistro

## Usage
You can either download the `.CT` file and load it into CheatEngine (and press "Yes" when it asks to run the script) or download the `.EXE` and just execute that (which is the script as a standalone CheatEngine trainer).

### Settings

You can set separate **hotkeys** for muting/unmuting. If you want/need to use the same hotkey for both (toggle), you'll have to make sure the actual mute status is synced with what the tool expects. Key modifiers are currently not supported.

*Note:* Make sure you choose a hotkey that doesn't interfere with anything and test e.g. that it doesn't interrupt holding calls or whatever.

You can enable it making a **beep** sound when it mutes (once) and unmutes (twice), to get an audible feedback that it's working.

The beeps should be played after muting/before unmuting, so that they won't appear in a recording/on stream (assuming your using the tool to mute Desktop Audio in the recording software).

Use the "Test"-buttons to test what would happen on mute/unmute with the current settings. CheatEngine stores the settings in the registry, search for `gtasa_music`.

### GUI

In addition to the settings, the GUI shows the current mute status and some debug output. Some GUI items have tooltips when you hover over them, so check that for more info.
