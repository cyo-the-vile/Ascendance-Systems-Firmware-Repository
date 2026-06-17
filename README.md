# Ascendance Systems Firmware

This repository contains public release firmware for Ascendance Systems devices.

## Choose The Correct UF2

- `NGPC_DV.uf2` - Neo Geo Pocket Color digital-video Consolizer firmware
- `GBA_DV.uf2` - Game Boy Advance digital-video Consolizer firmware
- `DAC.uf2` - DAC firmware

## Update Steps

1. Download the correct `.uf2` file for your device.
2. Unplug the device from USB.
3. Hold the device BOOTSEL button.
4. While holding BOOTSEL, plug the device into USB.
5. A removable drive should appear on your computer.
6. Drag and drop the `.uf2` file onto that drive.
7. Wait for the copy to finish. The device will reboot automatically.

## Notes

- Use only firmware intended for your exact device.
- Do not rename or modify the UF2 before flashing.
- If the device does not reboot after copying, unplug it and plug it back in normally.
- `SHA256SUMS.txt` contains checksums for verifying downloaded files.

These release UF2 files are signed by Ascendance Systems for supported secure-boot devices.
