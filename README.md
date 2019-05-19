# Trackpad in a Keycap for Corne/CrKbd Keyboard

This is a Trackpad add-on for the [Corne](https://github.com/foostan/crkbd) keyboard.

This add-on consists of two main parts:
- an adapter PCB that goes between Elite-C and the main keyboard
- a connector PCB that links trackpad with the adapter

There are two different options available for the Trackpad sensor mount (connector PCB)
- on the 'H' button keycap via flex cable (Connector V1)
- no-flex mount directly on the connector PCB (Connector V2)

Both options compatible with the main adapter PCB, see photos below.

Schematics and PCB design included in this repository.
[Trackpad.c](https://github.com/vlukash/qmk_firmware/blob/master/keyboards/crkbd/keymaps/vlukash_trackpad_right/trackpad.c) reads the trackpad data and sends it to QMK.

Please find more information in my [blogpost](https://vlukash.com/2019/01/15/trackpad-in-keycap-corne-crkbd-keyboard/).

## Video
Turn on the subtitles option :)

https://www.youtube.com/watch?v=eY_9cieYMEQ

## Build Guide
https://github.com/vlukash/corne-trackpad/blob/master/build-guide.md

## Photos
Trackpad sensor mounted directly on the connector PCB (Connector V2):
![Corne with no-flex trackpad](https://user-images.githubusercontent.com/8005242/55286180-b9b86480-534c-11e9-8c8a-0b9ddae888fb.JPG)
Trackpad sensor mounted on 'H' button keycap via flex cable (Connector V1):
![Corne with trackpad](https://vlukashevych.files.wordpress.com/2019/01/img_4735.jpg)

![All parts](https://vlukashevych.files.wordpress.com/2019/01/img_4709.jpg)

![Adapter](https://vlukashevych.files.wordpress.com/2019/01/trackpad-controller.jpg)

![Adapter](https://vlukashevych.files.wordpress.com/2019/01/img_4769.jpg)

![Adapter](https://vlukashevych.files.wordpress.com/2019/01/img_4760.jpg)

![Connector](https://vlukashevych.files.wordpress.com/2019/01/trackpad-connector.jpg)

![Connector](https://vlukashevych.files.wordpress.com/2019/01/img_4774.jpg)

![Connector](https://vlukashevych.files.wordpress.com/2019/01/img_4777.jpg)

![Button](https://vlukashevych.files.wordpress.com/2019/01/img_4715.jpg)

