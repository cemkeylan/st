# Cem Keylan's fork of suckless.org's simple terminal

## Features and Patches
Dracula Theme
Solarized Light Theme
Scrollback
externalpipe (having some issues atm)
alpha

## Keybindings

### Theme
* F6 to switch theme

### Zoom
* Meta+Shift+J to zoom in
* Meta+Shift+K to zoom out
* Meta+Shift+H to reset zoom

### Scroll
* Ctrl+Shift+U to scroll up
* Ctrl+Shift+D to scroll down

### External Pipe
* Meta+Shift+O to open url
* Meta+Shift+C to copy url
* Ctrl+Shift+O to copy output (does not work unless you launch st from another st for some reason)
* Ctrl+Shift+E to get the terminal screen on $EDITOR (broken)

## Installation

### Requirements
+ make
+ libxft

Arch Users can use
AUR: [st-ckyln-git](https://aur.archlinux.org/packages/st-ckyln-git/)

You can also install it via
```
git clone https://git.ckyln.com/st
cd st
sudo make install
```
