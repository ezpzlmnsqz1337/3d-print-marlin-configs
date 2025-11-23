# 3D Printer Marlin Configurations

This repository holds configuration files for Marlin firmware used to drive my 3D printers.

## Repository Structure

Each folder corresponds to a specific printer and contains:
- `Configuration.h`: The main configuration settings for Marlin.
- `Configuration_adv.h`: Advanced configuration settings.
- Pinout image: An image file showing the control board pinout for that printer.

## Assets

The `assets/` folder contains necessary drivers and libraries:
- **FAT 232 driver**: Required to flash the firmware to the 3D printer via USB.
- **U8glib**: A library required for Marlin display support.
