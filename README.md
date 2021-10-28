# dwm-build

my simple build of dwm.

## Requirements

* Run the following commands before compiling dwm. 
* Installing the font used requires an AUR helper like *yay*.

```
sudo pacman -S pamixer xorg-xbacklight
yay -S ttf-menlo-powerline-git
```

## Installation

Cloning and compiling dwm.

```
git clone <this-repo>
cd dwm-build
make && sudo make clean install
```
