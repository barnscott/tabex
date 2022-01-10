# TabEx - Tablet Extension for convertible devices using Gnome desktop

THIS PROJECT IS A PLACEHOLDER FOR A FUTURE PROJECT.
IT IS NOT A WORKING EXTENSION.

## TLDR
This extension does the following:

- Provides an Indicator Icon next to QuickControls menu, with drop-down menu to quickly enable/disable Tablet-mode

Tablet-mode does the following:
- Move top bar on bottom
- Activities and date are swapped
- Activities button is an icon
- Thumbnails in show-all-apps-view are set to 50% of view, and are scrollable out of view
- Launches new app windows in a new workspace

Other featues:
- Settings applet can change many of the defaults
- Indicator Icon-Menu includes:
  - On\Off toggle
  - Auto-enable on portrait orientation
  - Sub-menu with lock landscape / portrait / portrait-left
  - Open settings

## Purpose

This extension is intended for small convertible laptops can can be use in portrait mode. The idea is that after you rotate the screen into tablet-mode and hold the device in the portrait orientation, this extension will make the device more usable for touch input.

## Prereqs

Currenlty, this extention is only tested on the following releases

- Gnome 41

## How to use

Placeholder.

## How to install

### GNOME Extensions Website

Waiting till extension is stable.

### Manual Installation

Use the following commands to install this extension:

```
# change-directory to your home, or your prefered directory
cd ~ 

# copy down the source code repository
git clone git@github.com:barnscott/tabex.git

# symbolic-link the extention-code to the extension directory
ln -s $PWD/tabex/tabex@barnix.io ~/.local/share/gnome-shell/extensions/tabex@barnix.io

# if on X11, reset shell with ALT-F2 and enter "r". On Wayland, see note below.
# then, enable the extension. 
gnome-extensions enable tabex@barnix.io
```
If you are on Wayland, after you complete the  installation, you may need to log-out and log-in for the shell to register the key-bindings.

## To do

I would like to add the following features, but don't have any priority on doing so:

- [ ] Code cleanup / optimization
  