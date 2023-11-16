# iTerm2GermanKeyboardFix

The default keymapping in iTerm2 is frustrating for those who use a Macbook with a physical German keyboard layout.
There, many key bindings produce counterintuitive effects.

The mapping in this repository changes the following key combinations:

- **Option + Left/Right Arrow**: Move Cursor one word left/right (same as in the native MacOS terminal)
- **Option + Backspace**: Delete word left of cursor
- **Cmd + Backspace**: Delete current line
- **Cmd + Left/Right Arrow**: Move cursor to beginning/end of line
- **Cmd + Z**: Undo

If you're forgetful like me, there is also a reference for common keyboard shortcuts included.

## How to use

In iTerm, press `Cmd + ,` to open settings. Go to the Profiles pane and select `Keys`, then select the `Key Mappings` pane.
At the bottom of the window go to `Presets...`, click `Import...` and select `GermanKeyboardLayoutFix.itermkeymap`.

