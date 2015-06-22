#Install Instructions for LINUX

1. `xmodmap -pke > $HOME/.Xmodmap.backup` will generate a backup
2. `cp $HOME/.Xmodmap.backup $HOME/.Xmodmap` will make an editable copy
3. Manually configure it by switching the key codes of the keys
4. If you want to have 'Caps Lock' and 'Ctrl' switched by default, copy the contents of `switch-caps-ctrl` to the end of your new `Xmodmap`. (run `cat $HOME/asert/switch-caps-ctrl >> $HOME/.Xmodmap`)
