# T480s EFI

OpenCore EFI folder for a ThinkPad T480s running macOS Sequoia.

## Status

- Camera: works
- IR camera: works
- Speakers: working
- Bluetooth: working
- Wi-Fi: working
- Trackpoint and trackpad: working
- Touchscreen: not configured yet
- Fingerprint: not available, because macOS does not support the fingerprint reader on this laptop

## Before using

`EFI/OC/config.plist` contains placeholders for the machine identity values: `MLB`, `SystemSerialNumber`, `SystemUUID`, and `ROM`. Replace them with your own values before booting. You can generate them with GenSMBIOS or a similar tool.

Do not use values from someone else.

## Notes

This config was built for one machine and is not guaranteed to work on every T480s. Adjust it before use.
