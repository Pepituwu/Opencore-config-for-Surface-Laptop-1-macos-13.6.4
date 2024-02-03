# Opencore config for Surface Laptop 1 macos 13.6.4
Inspired by [MattKC](https://github.com/itsmattkc/OpenCore-SL3-BigSur/blob/master/README.md)

Made possible by [BigSurface](https://github.com/Xiashangning/BigSurface)

I upgraded to ventura from bigsur with the apple updater directly so idk if the drivers will work with a classic instaler from a usb key

## What work : 
From my experience, here is what works : 
- Audio
- keyboard (+ backlight)
- touchpad
- GPU Acceleration
- brightness controls and volume control
- battery readout
- USB

## What doesn't work:
- Touchscreen, [though BigSurface apparently has a fix](https://github.com/Xiashangning/BigSurface)
- Caps lock LED [I don't think this can be fixed]
- Webcam [Currently impossible]
- Built-in Wi-Fi + Bluetooth [Currently impossible] but can get around with a wifi usb key and some other drivers (fun fact : drivers like AirportBrcmFixup for wifi made my hackintosh super lagy and disable some fonctionality like the keyboard (???))

- Unsure if MiniDP-out works, un-tested

## Config of my surface : 
- i5 7300u 
- 8g of ram 
- 256g ssd
- and other classic stuffs you can expect from a surface

## Installation :
Simply drag and drop the efi folder on the root of your efi partition and let the magie happen! 
