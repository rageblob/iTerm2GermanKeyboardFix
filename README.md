# iTerm2GermanKeyboardFix

The default keymapping in iTerm2 is frustrating for those who use a Macbook with a physical German keyboard layout.
There, many key bindings produce counterintuitive effects.

The mappings in this repository adjust iTerms behavior such that:

- **Option + Left/Right Arrow**: Moves Cursor one word left/right (same as in the native MacOS terminal)
- **Option + Backspace**: Deletes word left of cursor
- **Cmd + Backspace**: Deletes current line
- **Cmd + Left/Right Arrow**: Moves cursor to beginning/end of line
- **Cmd + Z**: Undo

If you're forgetful like me, I also included a reference cheat sheet for common terminal keyboard shortcuts.

## How to use

In iTerm, press `Cmd + ,` to open settings. Go to the Profiles pane and select `Keys`, then select the `Key Mappings` pane.
At the bottom of the window go to `Presets...`, click `Import...` and select `GermanKeyboardLayoutFix.itermkeymap`.

