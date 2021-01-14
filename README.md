# HP-250-G6-Mojave-EFI

##Early Port of OpenCore https://github.com/snajdovski/HP-250-G6-OpenCore

<p align="center">
  EFI folder for macOS Mojave Hackintosh (i3 6006u variant) 250 G6 HP Laptop
<img src="https://i.imgur.com/vDsWHia.png" alt="look">
</p>

## What Works:
```
Almost Everything
Audio
Backlight 
Video Accelariton (1536 Mb Vram)
Touchpad
Keyboard
Sleep (Mojave)
```
## What doesn't work:
```
Built in Wifi but there is hope as a Wifi Intel Driver is already in process of developing, when its ready I will update the EFI folder
Update:
In order to make wifi work you could use the Open Source port of the Intel Wifi driver found here:
https://github.com/OpenIntelWireless/itlwm

```

## What is new with the latest commit:
```
*updated dsdt for newest bios(.65 rev a)
*backlight working now
*fixed audio ( low volume and auto switch)
*fixed intel hd 520 (now works with 1536mb memory)
*newest kexts
*catalina ready (depends on your bios)
and lots more 
```
