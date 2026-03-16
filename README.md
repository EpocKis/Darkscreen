# Screendark
Screen dimmer for Linux.

Works for KDE PLASMA 6+
Tested on CachyOS


# Install instructions
chmod +x ~/downloads/darkscreen.py
sudo mv ~/Downloads/darkscreen.py /usr/local/bin/darkscreen

sudo nano /usr/share/applications/darkscreen.desktop
Paste this:
[Desktop Entry]
Type=Application
Name=Darkscreen
Comment=Screen dimmer overlay
Exec=/usr/local/bin/darkscreen
Icon=preferences-desktop-display
Categories=Utility;
