![uleaf STM32 devboard](uleaf.png)

# uLEAF

A minimalistic STM32 development board designed to run audio synthesis applications.

## Overview

uLEAF is a KiCad PCB design with a simple bootstrap project to run audio synthesis applications. It is primarily focused on [LEAF (Lightweight Embedded Audio Framework)](https://github.com/spiricom/LEAF), but is not limited to it.

## Hardware Specifications

- **MCU**: STM32G474CCU6 with support for external RAM and Flash
- **PSRAM**: 8 Mb onboard PSRAM for audio buffers
- **Flash**: 16 Mb onboard flash memory for samples
- **Audio Codec**: PCM5102

## Usage

This board can be easily embedded in your applications or used as a reference design.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
