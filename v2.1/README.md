# Version 2.2 Firmware Files

This folder contains the firmware files for version 2.2.

## Required Files

- `bootloader.bin` - Bootloader binary (already included)
- `partitions.bin` - Partition table binary (already included)
- `ogstartracker_v2.2.bin` - Main firmware binary (add your compiled firmware here)

## Adding Firmware

To add the firmware binary for version 2.2:

1. Compile your firmware and generate `ogstartracker_v2.2.bin`
2. Place the file in this directory
3. The manifest.json is already configured to use this file

