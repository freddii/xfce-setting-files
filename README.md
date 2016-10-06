# xfce-setting-files
my personal xfce files for xubuntu or debian with xfce


get the git repo files:
-------
```
cd ~
git clone https://github.com/freddii/xfce-setting-files.git
```

copy over the search shortcuts for whiskermenu that work in xubuntu and debian:
-------
```
cp ~/xfce-setting-files/whiskermenu-1.rc ~/.config/xfce4/panel/whiskermenu-1.rc
xfce4-panel --restart
```

only for xubuntu:
-------
```
rightclick on the whiskermenu > panel > panel settings > backup and restore > 
import > ~/xfce-setting-files/xfce-whisker-backup.tar.bz2.tar.bz2 > set configuration
```