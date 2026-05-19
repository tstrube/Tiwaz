# Tiwaz

Tiwaz is a split keyboard with gasket mounted plate and hot-swappable switches. Each half works standalone as a one-handed controller or macro pad. QMK and VIA support allow button remapping in the browser without manual reflashing.

The defining feature are the joysticks. They can operate as regular analog gampead sticks or digital buttons and use ribbon cables to connect to the PCB.

There are multiple options including solder pads that allow access to the joysticks pins for custom applications.

![Tiwaz](Images/Tiwaz.jpg)

[More Images](Images/README.md)

## Features

- Each half usable standalone as a one-handed controller or macro pad
- Two joystick options (Alps Alpine [RKJX21224001](https://tech.alpsalpine.com/e/products/detail/RKJX21224001/) / [PSP3000-style RKJXU1210006](https://tech.alpsalpine.com/e/products/detail/RKJXU1210006/))
- 6 separate media keys
- all switches and buttons are RGB backlit
- FN + lowest media key switch Joystick input mode (analog gamepad, digital buttons)
- Gasket mounted plate for a dampened typing feel
- Dapening material between Plate and PCB, as well as PCB and case
- ~~[QMK firmware](https://github.com/qmk/qmk_firmware/tree/master/keyboards/tsc/tiwaz) with [VIA support](http://usevia.app)~~ *(pull-request pending)*

## PCB details

- RP2040 CPU
- 2MB flash
- 38 hot-swap connectors for MX type switches
- 6 auxiliary buttons (intended as media keys, but remappable, of course)
- WS2812 RGB LED for each switch and button
- AUX connector for power and data transmission to the other half (only one half should be connected to the PC at any time)
- Ideal diode to protect against accidentally plugging in both halves while they are connect to each other
- Self-resetting fuse to to protect against high power draw of the LEDs (though limited in firmware)
- ESD protection on the USB data pins
- Solder points for joystick pins (ADC (2x), GPIO, GND, 3V3) 

## Bill of Materials

- PCB available on *(coming soon)*
- Case on [Printables](https://www.printables.com/model/1715647-tiwaz-split-gaming-keyboard-gasket-mounted)
- Ergo Keycaps (not affiliated, just recommendations. There are very few backlit 1u sets available)
  - [Custom set](https://fkcaps.com/custom/PEWRWF)
  - [LPF Glow Legended Low Profile MX Keycaps](https://splitkb.com/products/lpf-glow-legended-mx-keycaps)
  - [THT (Tai-Hao Thins) Low Profile Keycaps - 98 PCS](https://shop.tai-hao.com/products/98black)
  - [THT (Tai-Hao Thins) Low Profile Keycaps - 65 Keys](https://shop.tai-hao.com/products/black-low-profile-keycaps)
  - [THT (Tai-Hao Thins) Low Profile Keycaps - Blanks](https://shop.tai-hao.com/products/taihao-black-low-profile-keycap-1u-dot-pbt-backlit)

## Assembly video *(coming soon)*
