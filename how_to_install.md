#Install Instructions

1. Locate the `xkb` file. (might be at /usr/share/X11/xkb/symbols/us)
2. Run the install script and pipe the output to the file from 1. (`$ sh install >> /usr/share/X11/xkb/symbols/us`)
3. Run the following command: `$ setxkbmap us -variant asert`
