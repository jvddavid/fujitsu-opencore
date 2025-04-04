# Fujitsu Lifebook AH46/w EFI OpenCore

To prepare this EFI for work, it was necessary fix the original DSDT.aml

#### System Information:

- Laptop model: Fujitsu Lifebook AH46/w
- CPU: Core i5-6300HQ
- iGPU: Intel HD Graphic 530
- Audio: ALC255
- Trackapd: I2C-ELAN500
- Wifi: BCM94360NG ( BCM4360 ) (I buy this)
- Ethernet: RTL8111 (Realtek)

#### Hakintosh:

- OpenCore bootloader v1.0.4
- **Monterey** (13.7.5) single boot

#### What's works:

- Adjust Brightness
- Audio (alcid=3)
- iGPU
- Trackpad
- Keyboard Japanese KANA (fn works only for sound and brightness)
- Detect battery info (detect only if state change at least once)

#### What's not works:

- Fn key
- The Qualcomm Wifi Adapter (QCA64xA)
