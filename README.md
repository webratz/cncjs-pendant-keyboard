# cncjs-pendant-gamepad
Using a simple and cheap wireless gamepad

[SNES wireless gamepad](https://www.amazon.de/gp/product/B07FTCWBSY/ref=ppx_yo_dt_b_asin_title_o07_s01?ie=UTF8&psc=1)

## Installation
After cloning the repository to your work directory, change into this directory and run
```
npm install
```

Make sure you have installed the following packages
```
libusb-1.0-0-dev
libudev-dev
```
These can be installed with apt.

## Usage
Run `bin/cncjs-pendant-keyboard` to start. Pass --help to `cncjs-pendant-keyboard` for more options.

```
bin/cncjs-pendant-keyboard --help
```

Ensure to put the  `udev-keyboard.rules` file into `/etc/udev/rules.d/` and reload with `sudo udevadm control --reload-rules`.

Hotkeys:


