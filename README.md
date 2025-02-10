<img src="icon.png" width="128" />

# Cut & Paste

This workflow attempts to emulate Windows' <kbd>Ctrl-X</kbd> and <kbd>Ctrl-V</kbd> feature to "cut" and "paste" files and folders in the Finder. It integrates as much as possible with Alfred's native File Buffer feature.

You can use <kbd>Shift-Ctrl-X</kbd> to "stack" additional files to the cut queue. You can also manipulate the File Buffer directly using Alfred's native hotkeys for doing so.

There are a couple of Workflow Configuration options that can be set, namely the trigger keyword (which is an alternate entrypoint for the "paste" function, instead of the <kbd>Ctrl-V</kbd> hotkey) and the mode for duplicate file handling if the destination directory contains an identically-named file or folder. The default in that case is "Skip". Change it to "Rename" to have Alfred automatically rename the file, adding a suffix based on the epoch timestamp.

Please report any issues you encounter!
