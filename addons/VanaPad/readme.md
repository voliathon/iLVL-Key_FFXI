# VanaPad

NotePad for Vana'diel!

![VanaPad_demo](https://github.com/user-attachments/assets/1af708e4-c2df-469c-923f-5cdccd5b258c)

## Features
- Mouse interface!
- Type directly into VanaPad without using the games chatlog.
- Save up to 10 notes, organized into tabs.
- Copy a note to the clipboard to be able to paste into your chat log or anywhere on your PC!
- Wordwrap!
- Save a custom title to a note if you may want to keep it around for a while.
- Shrink down to just the bar when you don't need it.
- Auto-fades when shrunk and not being used.
- Pin the VanaPad bar in place using the button, or unpin it to move it around

## Commands
All commands must be preceded with `//vanapad` or `//vp` (ex: `//vp show`)  
- `show/hide` - Show/hide the VanaPad window
- `copy/c` - Copy the current note to the clipboard.
- `edit/e` - Edit the current note.
- `delete/d` - Delete the current note.
- `title/t` - Add a custom title to the current note.
 - `help` - Display a list of commands and addon info.

## Limitations
- While there is a cursor to make it easier to see your typing, you cannot move the cursor to type in the middle of a note.
- Using the Enter Key will create a new line in your note. However, Windower seems unable to prevent the action of hitting the Enter Key from being sent to the game like it does with other keys.

## Version History
Version 1.0 (Full Release)
- Added the ability to copy the contents of a note to the clipboard.
- Added Copy and Delete text commands.
- Adjusted accuracy of button detection to be much more precise. Now uses the exact width of the text box to determine the spacing of buttons.
- Code cleanup.

Version 1.0 BETA-4
- Adjusted Help text.

Version 1.0 BETA-3
- Fix text shifting when changing colors (you can see it doing it with the edit button in the example gif).

Version 1.0 BETA-2
- Fix Windower double-click bug on the hide button
- Fix un-hiding after zone when hidden.

Version 1.0 BETA-1
- First version
