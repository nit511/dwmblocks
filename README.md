# Dwmblocks
Dwmbar is a very simple and modular status bar written for dwm in C. You can also add and remove blocks by editing the config.h file.

# Preview
![2022-04-07-141057_532x40_scrot_cropped](https://user-images.githubusercontent.com/82656244/162159059-e5c0ca1d-6e22-4db5-981b-f00a9b5d76e4.jpg)

# Requirements
- ttf-font-awesome

# Installation
```
git clone https://github.com/nitinsagarsoni/dwmblocks/
cd dwmblocks/
sudo make install
```
- You need to put scripts in your ```/usr/local/bin/``` directory (or any other bin directory, if you uses scripts locally) and give them executable permission.
- Add the line ```dwmblocks &``` to your .xinitrc file to run on startup. You can also run ```dwmblocks``` in terminal for testing purposes.

# Notes:-
- Font used in preview is ttf-jetbrains-mono.
- Dwmblocks is installed in the ```/usr/local/bin/``` directory by default, if you want to install it locally you can change prefix path in Makefile file.
