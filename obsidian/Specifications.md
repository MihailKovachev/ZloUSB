An HID keyboard emulator for keystroke injection like USB Rubber Ducky or MalDuino



Both USB A and USB C

Firmware directly programmable via USB. Done using a second switch. Default is to boot into operation mode, but holding the switch while plugging in will boot into firmware flashing mode.

Payloads stored on a flash chip

Boot mode controlled via a switch – defaults to injection but if the button is pressed during insertion, the controller enters script upload mode and payloads can be uploaded by dragging and dropping them as if on a normal USB flash drive

2 LEDs – one red and one green. Red means injection mode, green means script upload mode. No LED means firmware flashing mode

USB-C and USB-A protection to prevent flow from one port to the other is not strictly necessary because the mechanical casing is supposed to prevent this.

Surge protections on both USB-C and USB-A

