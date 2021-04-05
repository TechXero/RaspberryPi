![Pi4](https://cdn.redmondpie.com/wp-content/uploads/2019/06/raspberry-pi-4-1200px.jpg)

# -/ Kernel Update :

sudo BRANCH=next<br />
rpi-update eb57df9de3cedf3b1afaa4da54bb50151e55ab56<br />

# -/ Hold EEpROM Update :

echo "rpi-eeprom hold" | sudo dpkg --set-selections<br />
sudo systemctl mask rpi-eeprom-update<br />

# -/ XScreensaver fix :

sudo apt install xscreensaver xscreensaver-gl-extra xscreensaver-data-extra<br />
sudo apt install compiz compizconfig-settings-manager emerald emerald-themes fusion-icon<br />

# -/ Various Links :

https://github.com/richardmidnight/pi-safe<br />
https://github.com/Hexxeh/rpi-firmware/commits/master<br />
https://www.raspberrypi.org/documentation/hardware/raspberrypi/booteeprom.md<br />
https://jamesachambers.com/raspberry-pi-4-bootloader-firmware-updating-recovery-guide/?amp=1<br />
