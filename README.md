## [eurkey](https://eurkey.steffen.bruentjen.eu/)

Adding this here, as it's not available yet for my distro (fedora xfce spin). I got it working as follows:

````sh
sudo cp eurkey /usr/share/X11/xkb/symbols/
sudo setxkbmap -v 10 -layout eurkey
````

This works but the layout doesn't show up in `xfce4-keyboard-settings`.
Also the change is lost after logout. Any help much appreciated.
