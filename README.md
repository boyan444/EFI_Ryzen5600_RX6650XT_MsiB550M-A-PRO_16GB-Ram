![Image Alt](https://github.com/boyan444/EFI_Ryzen5600_RX6650XT_MsiB550M-A-PRO_16GB-Ram/blob/59bf66326ca70a4dc3f3ab525aef08d6abd68fca/Screenshot%202026-07-27%20at%2018.52.33.png)
# EFI_Ryzen5600_RX6650XT_MsiB550M-A-PRO_16GB-Ram
The EFI is tested and working on macOS Tahoe.It is based on my specific hardware!
## Hardware

| Component | Model |
|----------|----------|
| Motherboard | MSI B550M-A PRO |
| CPU | AMD Ryzen 5 5600 |
| GPU | AMD Radeon RX 6650 XT |
| RAM | 16GB DDR4 3200Mhz |
| Storage | Samsung 860 EVO |
| macOS | Tahoe 26.x |

## Important

**Do NOT use the SMBIOS included in this repository.**

Before booting, generate your own:

- SystemSerialNumber
- MLB
- SystemUUID
- ROM

and update them using OCAT.


## Audio

This EFI uses **VoodooHDA**.

AppleALC did not work on my installation.

If you have problems with the audio, such as no sound or microphone not working, this tutorial may help
https://www.youtube.com/watch?v=2IejYQl3zKc
