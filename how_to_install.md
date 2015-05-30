#Install Instructions for LINUX

1. Select which type of asert you want.
2. Copy the appropriate selected Xmodmap to `$HOME/.Xmodmap`
3. Run `echo "if [ -s ~/.Xmodmap ]; then xmodmap ~/.Xmodmap; fi" >> ~/.xinitrc`
4. Run `xmodmap ~/.Xmodmap`
