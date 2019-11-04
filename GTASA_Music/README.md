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

You can download the `.EXE` and simply execute that, which doesn't require CheatEngine to run (it basicially comes with CheatEngine included, but only runs this tool).

The `.CT` file contains the uncompiled script, which you can open in CheatEngine and view/edit at your leisure. You can also `File - Save as..` and then select type `.EXE` to compile it yourself. (*Note:* `local standalone = true` at the top of the Lua script forces CheatEngine to exit when the trainer window is closed, you can change that to `false` for testing, but should keep it at `true` for saving a standalone trainer.)

Some UI elements have tooltips when you hover over them, so check that for more info.

### Settings

You can set separate **hotkeys** for muting/unmuting. If you want/need to use the same hotkey for both (toggle), you'll have to make sure the actual mute status is synced with what the tool expects. Triggering a hotkey with key modifiers is currently not supported. Depending on how the program that is supposed to act on the hotkey (e.g. OBS/XSplit) handles this, you may need to enable the **Modifier Wait** setting, so when you hold Ctrl/Shift/Alt ingame it doesn't look like it's sending the hotkey e.g. Shift+F14, but instead waits until you release the modifier.

*Note:* Make sure you choose a hotkey that doesn't interfere with anything and test e.g. that it doesn't interrupt holding calls or whatever.

You can enable playing **audio cues** when it mutes and unmutes. The audio is played after muting/before unmuting, so that it won't appear in a recording/on stream (assuming the hotkey mutes Desktop Audio in the recording software).

Use the "Test"-buttons to test what would happen on mute/unmute with the current settings.

CheatEngine stores the settings in the registry, search for `gtasa_music`.

### Debug

Enabling the "Debug" checkbox outputs some more information and outputs some debug messages in a separate window.

Don't enable this unless you do actual debugging, since it can cause issues.
