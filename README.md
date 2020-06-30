# reascript
A free collection of scripts for use in [Reaper](https://www.reaper.fm/).

See the source files for details and instructions.

## Included Scripts
- [Select MIDI items on selected tracks](https://github.com/chkhld/reascript/blob/master/scripts/select-track-midi-items.eel): Adds all media items with active MIDI takes on all selected tracks to current media item selection
- [Track to SRT](https://github.com/chkhld/reascript/blob/master/scripts/track-to-srt.eel): Run this on a selected track to convert its text items to SRT subtitle data for your videos

_(There may be more in the future)_

## Installation
- The important stuff is in the [scripts](https://github.com/chkhld/reascript/blob/master/scripts/) folder, so download what you want from there. Open a specific script, click the "Raw" button, copy all text.
- Open Reaper and go into the "Actions" menu, select the "Show action list" menu entry. (This may also be mapped to the "?" key on your system.)
- In the Actions menu dialog, click the "ReaScript: New" button.
- In the "New Action" dialog, first switch the file type to ".eel" or ".lua", depending on the extension of the script here.
- Then pick a fitting name and a place to store the new script, it should be somewhere inside the "Scripts" folder in your Reaper resource path, and click the "Save" button. This will bring up an empty ReaScript editor window.
- Paste all the text copied from the Raw GitHub script into the ReaScript editor.
- Press Ctrl-S (Windows, Linux) or CMD-S (macOS) to save the script.
- The new script is now available in the Actions menu, you could create keyboard shortcuts or toolbar buttons for it.

## Support
This is just a fun project for me, I do this on the side to waste time, so don't expect too much of an effort. But if you find any bugs, or if you have any suggestions for improvements, feel free to report them in the [issue tracker](https://github.com/chkhld/reascript/issues), I'll have a look there every now and then.

Have fun! <3
