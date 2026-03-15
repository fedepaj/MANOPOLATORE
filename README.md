# MANOPOLATORE

A super cheap 16-encoder MIDI controller based on the RP2040-Zero.

## Documentation

All hardware documentation (Schematics, BOM, Interactive BOM, 3D Model, and Gerber viewer) is available on the GitHub Page:

👉 **[MANOPOLATORE Documentation](https://fedepaj.github.io/MANOPOLATORE/)**

## Hardware Specs

* **Microcontroller:** RP2040-Zero
* **Inputs:** 16x EC11 rotary encoders
* **Visual Feedback:** 16x 8-LED WS2812B NeoPixel rings (mounted on top of the encoders and soldered to the PCB via pin headers). [AliExpress link](https://it.aliexpress.com/item/1005002313192735.html)
* **Design Goal:** Minimal components, extremely cheap to manufacture and assemble.

## TODO

* [ ] **Firmware:** Develop and release a pre-compiled MIDI firmware (e.g., using Arduino IDE, CircuitPython/MicroPython, or KMK).
* [ ] **Enclosure:** Design and release a 3D-printable case.

## License

Distributed under the MIT License. See the `LICENSE` file for more information.
