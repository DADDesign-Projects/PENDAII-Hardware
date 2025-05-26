# PENDAII: Platform for Effects oN DAisy

Welcome to the **PENDAII** project! This repository contains the schematics and PCB layouts created with **KiCad 9.0** for a digital audio effects platform based on the **Daisy-Seed** board from **ElectroSmith**.

## Author

**DAD Design**

## Overview / Features

**PENDAII** is the second version of the PENDA platform. It introduces stereo processing and improved management of signal paths and power supplies.

**What’s New in PENDAII**:

- **Stereo processing**: a second audio channel has been added for a wider and more immersive sound experience.
- **Digital input volume control**: the input gain is now precisely adjustable via a digital potentiometer.
- **Digital Dry/Wet mix control**: the ratio between the processed (wet) and original (dry) signal is digitally managed.
- **100% analog Dry path**: although controlled digitally, the dry signal remains fully analog to preserve audio quality.

**General Features**:

- **Mono or Stereo Audio Input/Output**: flexible integration into various audio setups.
- **Two momentary footswitches**: for hands-free activation of effects.
- **2-inch SPI display**: clean and compact user interface (compatible with most ST7789 displays).
- **MIDI input**: allows control via external MIDI devices.
- **User controls**:
  - **4 encoders with push-button**: for parameter navigation and adjustment.
  - **3 analog potentiometers**: for direct control of parameters such as input level or Dry/Wet mix.

## Content

- The **Fab** directory contains all necessary files for fabrication.
- The **PENDAII-Hardware** directory contains the source files for the KiCad 9.0 project.

## Software

**PENDAII-Software** is a collection of audio effects built on an advanced software architecture, specifically designed for the PENDAII hardware platform.

[GitHub Repository](https://github.com/DADDesign-Projects/PENDAII-Software)

## Contributing

Contributions are welcome! If you'd like to suggest an improvement or fix an issue, feel free to open an *issue* or a *pull request*.

## License

This project is licensed under the **MIT License**.
