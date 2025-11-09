# Shell Auto Execute (Arduino Leonardo HID Emulator)

## Overview

This repository demonstrates how to use an **Arduino Leonardo / Micro** as a USB Human Interface Device (HID) to emulate keyboard input. The project is intended **only** for legitimate uses such as automation, hardware testing, accessibility research, or controlled lab experiments where you have explicit permission to test the target system.

> **Important:** Do **not** use this project to access, modify, or execute code on systems without the owner’s express consent. Unauthorized use is illegal and unethical.

## What this project is

This project provides:

* Example firmware to emulate keyboard input with an Arduino Leonardo / Micro (ATmega32U4).
* A configurable framework to map different keyboard layouts and select presets.
* A simple hardware interface for selecting modes and starting/stopping the emulation.

It is presented as an educational demonstration of HID emulation and USB device behavior for researchers, students, and developers.

## Features

* Emulates keyboard input via the Arduino’s native USB capability.
* Supports multiple keyboard layouts (configurable).
* Simple physical controls for selecting configuration and initiating a test sequence.
* Designed for offline, authorized testing in isolated environments.

## Supported Keymaps

The code includes support for several common keyboard layouts. Use these only for legitimate testing and adapt layouts to match your test environment.

## Hardware

Hardware used for demonstration (typical example; may be substituted depending on your design):

* Arduino Leonardo or Arduino Micro (ATmega32U4)
* 3 × momentary push buttons (e.g., 12×12 mm)
* 3 × 1 kΩ resistors (pull-down / pull-up depending on wiring)
* Breadboard and jumper wires (male–male, male–female)
* Optional battery / power source (for pre‑configuration before deployment)
* USB cable (Micro‑USB)

> Note: The exact components and wiring are intentionally not provided here. Use components safely and follow electronics best practices.

## Safety & Legal

* Use this project **only** in environments where you have clear permission to connect USB devices and run tests.
* Never use it to deploy or execute code on systems you do not own or administer.
* Always test in a controlled, offline environment (virtual machines or isolated test hardware).
* Be aware of local laws and organizational policies regarding security testing and device emulation.

## Getting started (high level)

1. Clone the repository to your local machine.
2. Open the Arduino `.ino` sketch in the Arduino IDE.
3. Review the code and replace any placeholder values with safe, authorized test inputs relevant to your environment.
4. Compile and upload the sketch to your Arduino Leonardo / Micro.
5. Perform tests only on systems for which you have permission, preferably in an isolated test lab or virtual machine.

> The repository intentionally omits automated payload distribution examples and remote download URLs. If you need help structuring safe test scripts or configuring keyboard layouts for accessibility/automation, describe your authorized test environment and I can provide guidance tailored to that.

## Contribution

Contributions are welcome as long as they align with the project’s ethical use guidelines. When submitting changes, please:

* Provide a clear description of the intended, authorized use case.
* Avoid adding examples that facilitate unauthorized access.
* Include tests demonstrating safe operation in an isolated environment.

## License

This project is released under the MIT License — see `LICENSE` for details.
