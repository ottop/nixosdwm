# My DWM and accompanying configs for my NixOS setup

## Example screenshots

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
3. Put the config.h file of slstatus in your slstatus directory.
4. Run ```make clean install``` in the slstatus directory.
5. Install Rofi and place both of the .rasi files inside ~/.config/rofi/.
6. With XTerm installed, place the .Xresources file inside your home directory (or modify an existing .Xresources file with the contents if you already have one that you are using for something else).
7. Set the wallpaper using whatever wallpaper tool you use.
