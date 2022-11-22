# Fujitsu Lifebook AH46/w EFI OpenCore

Base ACPI Data: [OpenCore EFI for Asus X555UA](https://github.com/trinhdvt/OpenCore-EFI)

To prepare this EFI for work, it was necessary use the DSDT.aml from the Asus X555UA

#### System Information:

- Laptop model: Fujitsu Lifebook AH46/w
- CPU: Core i5-6300HQ
- iGPU: Intel HD Graphic 530
- Audio: ALC255
- Trackapd: I2C-ELAN500
- Wifi: BCM94360NG ( BCM4360 ) (I buy this)
- Ethernet: RTL8111 (Realtek)

#### Hakintosh:

- OpenCore bootloader v0.8.6
- **Monterey** (12.6) single boot

#### What's works:

- Adjust Brightness
- Audio (alcid=3)
- iGPU
- Trackpad with no gestures
- Keyboard Japanese KANA (fn key still working only for sound control)

#### What's not works:

- Fn key
- The Qualcomm Wifi Adapter (QCA64xA)
