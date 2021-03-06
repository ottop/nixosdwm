# My DWM and accompanying configs for my NixOS setup

## Example screenshots
![Screenshot from 2021-10-25 02-59-14](https://user-images.githubusercontent.com/60475104/138618216-9e550e21-82c8-4213-a281-7c6542d0b45d.png)
![Screenshot from 2021-10-25 02-59-54](https://user-images.githubusercontent.com/60475104/138618219-229119ac-63fb-4412-863e-609a8179a889.png)


## What my configuration uses:
- [DWM](https://dwm.suckless.org/)
- The following patches:
  - [actualfullscreen](https://dwm.suckless.org/patches/actualfullscreen/)
  - [fancybar](https://dwm.suckless.org/patches/fancybar/) 
  - [gaplessgrid](https://dwm.suckless.org/patches/gaplessgrid/)
  - [layoutscroll](https://dwm.suckless.org/patches/layoutscroll/)
 - [Rofi](https://github.com/davatorium/rofi)
 - [slstatus](https://tools.suckless.org/slstatus/)
 - [XTerm](https://invisible-island.net/xterm/)

## How to use this configuration
1. Put the config.h file of dwm in your dmenu directory along with the .diff patch files linked above. 
2. Run ```make clean install``` in the dwm directory.
3. Put the config.h file of slstatus in your slstatus directory and modify any sensor locations and such to match your system.
4. Run ```make clean install``` in the slstatus directory.
5. Install Rofi and place both of the .rasi files inside ~/.config/rofi/.
6. With XTerm installed, place the .Xresources file inside your home directory (or modify an existing .Xresources file with the contents if you already have one that you are using for something else).
7. Set the wallpaper using whatever wallpaper tool you use.
