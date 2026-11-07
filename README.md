# T480s EFI

Folder EFI OpenCore untuk ThinkPad T480s yang dipasang macOS Sequoia.

## Status

- Kamera: jalan
- IR kamera: jalan
- Speaker: aman
- Bluetooth: aman
- Wifi: aman
- Trackpoint dan trackpad: aman
- Touchscreen: belum disetting
- Fingerprint: tidak tersedia, karena macOS tidak mendukung fingerprint reader di laptop ini

## Sebelum dipakai

File `EFI/OC/config.plist` berisi placeholder untuk nilai identitas mesin: `MLB`, `SystemSerialNumber`, `SystemUUID`, dan `ROM`. Isi dengan nilai milik kamu sendiri sebelum boot. Nilai tersebut bisa dibuat dengan GenSMBIOS atau tool sejenis.

Jangan pakai nilai dari orang lain.

## Catatan

Config ini dibuat untuk satu mesin dan tidak dijamin cocok untuk semua T480s. Sesuaikan dulu sebelum dipakai.
