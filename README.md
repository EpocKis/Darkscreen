# Darkscreen <br>
Screen dimmer for Linux. <br>

Lets u set a hotkey and to <br>
choose which monitor/monitors <bra>
are affected. <br>
Default: Ctrl+Alt+D

Works for KDE PLASMA 6+ <br>
Tested on CachyOS <br>


# Install instructions <br>
chmod +x ~/downloads/darkscreen.py <br>
sudo mv ~/Downloads/darkscreen.py /usr/local/bin/darkscreen <br>

sudo nano /usr/share/applications/darkscreen.desktop <br>

Paste this: <br>

[Desktop Entry] <br>
Type=Application <br>
Name=Darkscreen <br>
Comment=Screen dimmer overlay <br>
Exec=/usr/local/bin/darkscreen <br>
Icon=preferences-desktop-display <br>
Categories=Utility; <br>

Ctrl+O, then ENTER <br>
Ctrl+X to close it <br>
