Installation:
sudo apt install feh autorandr openbox lxpanel lxrandr pcmanfm lxterminal
sudo ./install
cp -r "userRoot/." "~"
echo "me.fier.de" >"~/.xinitrc"

Start:
startx

Uninstallation:
sudo /opt/me.fier.de/uninstall
rm "~/.xinitrc"