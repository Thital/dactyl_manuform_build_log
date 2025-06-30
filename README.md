# Dactyl-manuform keyboard Build log 🪵 🪵 🪵 
![Imgur](https://i.imgur.com/44uUhTd.jpeg)
## Assembly
### Printing
Right side uses [this](https://thangs.com/designer/ZackFreedman/3d-model/Dactyl-ManuForm%205x6%20Mechanical%20Keyboard-10466) stl.

However i realized it doesn't have a nice place to put the microcontroller.

So for the left side i generated it using https://ryanis.cool/dactyl/#manuform because it comes with a nice holder

I had to modify the holder because i used a clone pro micro so be mindful of your microcontroller footprint.

Keycaps were generated using [riskable's keycap playground](https://github.com/riskable/keycap_playground)

### Wiring
Here are materials I used for wiring.

* Two Arduino Pro Micros
* M3 Heat set inserts
* M3x5mm Philips screw
* Silicone wire
* 1N4148 diodes
* 2 3.5mm female jack connectors

I wired the row columns by using the legs of the diodes and then running a wire to the necessary pins.

For the columns i stripped a length of wire among the points where it meets the leg of the switch.
![Imgur](https://i.imgur.com/V7yX76L.jpeg)

Wiring diagram i used 
![](https://miro.medium.com/max/2400/1*Q7xYKNrfMr8au7zUipBlGg.jpeg)

### Firmware 
For firmware it just uses [QMK](https://github.com/tshort/qmk_firmware/tree/master/keyboards/dactyl-manuform)
