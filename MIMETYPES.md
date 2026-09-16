## Using custom MIME types
Skittles comes with a custom icon and MIME type for the following filetypes:
- Compressed Wii/GameCube Discs (`.RVZ`)

In order to use these custom MIME types, you need to install the included files to either your local user or system manually.

### For all users on the system
1. Copy the contents of `mimes` to `/usr/share/mime/packages` .
2. Run `sudo update-mime-database /usr/share/mime`

### For just your local user
1. Copy the contents of `mimes` to `~/.local/share/mimes/packages`
2. Run `update-mime-database ~/.local/share/mime`


## Future plans
Alongside packaging to `.rpm` and `.deb`, I plan to automatically install the required MIME types via an installation script. For now, this must be done manually though.