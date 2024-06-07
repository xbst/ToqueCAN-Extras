# ToqueCAN Pi 4 USB C PCB

This is a PCB for connecting a ToqueCAN to a Raspberry Pi 4 (only) without needing a USB cable. This connects to the USB C connector on the ToqueCAN and the Pi 4.

You need to be able to SSH into your Raspberry Pi 4 and edit some files to be able to use this. Instructions:

1. SSH into your Raspberry Pi.
2. Edit the `config.txt` file in `/boot` by using `sudo nano /boot/config.txt`. You may need to enter your password again for sudo.
3. Add `dtoverlay=dwc2,dr_mode=host` to the bottom of the file in a new line.
4. Press `CTRL + X`, then `Y`, then `ENTER` to save and exit.
5. Reboot your Raspberry Pi (`reboot now`)
6. Plug in the PCB. It's ready to use.

## Purchase Links
### United States
- [Isik's Tech](https://store.isiks.tech/products/toquecan-raspberry-pi-4-usb-c-pcb) (Me)
