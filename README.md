<img src="icon.png" width="128" />

### Finder Cut & Paste

This workflow attempts to emulate Windows' <kbd>⌃ctrl</kbd><kbd>X</kbd> and <kbd>⌃ctrl</kbd><kbd>V</kbd> feature to "cut" and "paste" files and folders in the Finder. It is integrated with, and complements Alfred's native File Buffer feature.

### Usage

Select one or more files / folders in the Finder and press one of the trigger hotkeys:
- <kbd>⌃ctrl</kbd><kbd>X</kbd> will _replace_ whatever is in the buffer with the new selection
- <kbd>⌃ctrl</kbd><kbd>⇧shift</kbd><kbd>X</kbd> will _append_ files to the buffer, preserving the previous contents

Then, navigate to the destination folder and press <kbd>⌃ctrl</kbd><kbd>V</kbd> (or action Alfred using the trigger keyword). Your files will be moved, and the originals will be put in the Trash or deleted, depending on the setting in the workflow configuration.

You can also add or remove files from the File Buffer using Alfred's native method for doing so, or add items via the included File Action.

### Why no "Copy" — why only "Cut"?

The Finder natively supports using <kbd>⌘C</kbd> and <kbd>⌘V</kbd> to copy/paste files and folders. I did not see a need to duplicate that functionality.

### Yes, you can also use ⌥⌘V...

The Finder has a native "Move" function as well, which you can trigger with <kbd>⌥⌘V</kbd>. Still, this workflow has several advantages:

- Integrated with Alfred's File Buffer
- Can pick and choose files from multiple separate source folders
- Arguably, easier-to-remember hotkeys

Of course you are free to mix and match and use whichever features you find most convenient!
