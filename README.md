# tabbed - generic tabbed interface

`tabbed` is a simple tabbed X window container.


## Features & Patches

- [alpha](https://tools.suckless.org/tabbed/patches/alpha/): Allows to handle windows with transparency.

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
