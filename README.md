# Darkscreen <br>
Screen dimmer for Linux. <br>
Turns the screen(s) black. <br> 
Adds a black overlay over selected minotor(s) to give the illusion that they are turned off. <br>
Usefull when you temporarly want to turn the screens off, while actually not turning them off. <br>

Lets you set a hotkey and to <br>
choose which monitor/monitors <bra>
are affected. <br>
Default: Ctrl+Alt+D

Works for KDE PLASMA 6+ <br>
Tested on CachyOS <br>

<img src="https://raw.githubusercontent.com/EpocKis/Darkscreen/refs/heads/main/Screenshot_20260316_224427.png" alt="description">

# Dependencies <br>
python-pyqt6 python-pynput

Arch: paru -S python-pyqt6 python-pynput
# Install instructions <br>
chmod +x ~/Downloads/Darkscreen.py <br>
sudo mv ~/Downloads/Darkscreen.py /usr/local/bin/Darkscreen <br>

sudo nano /usr/share/applications/Darkscreen.desktop <br>

Paste this: <br>

[Desktop Entry] <br>
Type=Application <br>
Name=Darkscreen <br>
Comment=Screen dimmer overlay <br>
Exec=/usr/local/bin/Darkscreen <br>
Icon=preferences-desktop-display <br>
Categories=Utility; <br>

Ctrl+O, then ENTER <br>
Ctrl+X to close it <br>
