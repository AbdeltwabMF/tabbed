# tabbed - generic tabbed interface

`tabbed` is a simple tabbed X window container.


## Features & Patches

- [alpha](https://tools.suckless.org/tabbed/patches/alpha/): Allows to handle windows with transparency.
- [autohide](https://tools.suckless.org/tabbed/patches/autohide/): Allows to hide tabs when there is only one tab.
- [bar-height](https://tools.suckless.org/tabbed/patches/bar-height/): Allows to set the height of the tab bar.
- [hidetabs](https://tools.suckless.org/tabbed/patches/hidetabs/): Allows to hide tabs.
- [xresources](https://tools.suckless.org/tabbed/patches/xresources/): Allows to set the colors from X resources.

## Requirements

In order to build tabbed you need the `Xlib` header files.

## Installation

Edit `config.mk` to match your local setup (tabbed is installed into the `/usr/local` namespace by default).

Afterwards enter the following command to build and install tabbed
(if necessary as root):

```bash
make clean install
```

## Running

See the man page for details.
