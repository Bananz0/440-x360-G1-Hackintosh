## HP ProBook 440 x360 G1 OpenCore EFI Folder

![HP ProBook 440 x360 G1](https://support.hp.com/doc-images/183/c06062614.jpg)

### Overview

This repository contains the OpenCore EFI folder tailored for the HP ProBook 440 x360 G1 laptop. OpenCore is a boot loader that enables macOS and other operating systems to run on non-Apple hardware. This EFI configuration aims to provide a stable and optimized boot environment for macOS on the HP ProBook 440 x360 G1.

### Features

- **Compatibility:** Designed and tested for HP ProBook 440 x360 G1 laptops. 

- **macOS Support:** Provides a somewhat smooth boot process for macOS Ventura

- **Stability:** Carefully crafted to offer a stable and reliable boot experience.

- **Optimized:** Optimized ACPI, kexts, and configurations for better performance and compatibility.

- **Easy Setup:** Detailed instructions on how to set up OpenCore on your HP ProBook 440 x360 G1.

### Hardware Specifications

| Specifications      | Detail                                      |
| ------------------- | ------------------------------------------- |
| Computer model      | HP ProBook x360 440 G1			    |
| Processor           | Intel Core i5-8250U Processor               |
| HDD		      | Western Digital CL SN520 NVMe SSD.          |
| Integrated Graphics | Intel® HD Graphics 620                      |
| Monitor             | FHD 1920x1080 (14 inch)                     |
| Sound Card          | Conexant CX8200				    |
| Wireless Card       | Intel® Wireless-AC 8265 802.11b/g/n/ac      |
| Ethernet/LAN        | Realtek RTL8168/8111 PCI-E Gigabit Ethernet |
| Card Reader         | Realtek Semiconductor RTS5129 Card Reader   |

### Kexts

| Kext                 | Description                                                                                                                         |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| AirportItlwm.kext    | Provides Wi-Fi support for Intel® Wireless-AC 8265 802.11b/g/n/ac cards, enabling Wi-Fi connectivity on macOS.                    |
| AppleALC.kext        | Enables audio support for the Conexant CX8200 sound card, allowing sound output and input on macOS.                                 |
| BlueToolFixup.kext   | Fixes Bluetooth-related issues on some Intel-based Hackintosh systems, providing essential patches for Bluetooth support.           |
| BrightnessKeys.kext  | Enables brightness control using function keys on the HP ProBook 440 x360 G1, allowing adjustment of display brightness on macOS.  |
| DebugEnhancer.kext   | Enhances debugging capabilities on macOS, providing additional logging and debugging features for troubleshooting.                   |
| ECEnabler.kext       | Enables the Embedded Controller (EC) on certain laptops, ensuring proper communication between hardware and the operating system.    |
| IntelBTPatcher.kext  | Patches Intel Bluetooth firmware on specific Wi-Fi/BT combo cards, enhancing Bluetooth compatibility and stability.                   |
| IntelBluetoothFirmware.kext | Provides firmware support for Intel-based Bluetooth cards, enabling macOS to recognize and use Intel Bluetooth hardware.           |
| Lilu.kext            | Serves as a platform for other kexts, essential for proper functioning of many other kexts in the EFI configuration.                |
| RTCMemoryFixup.kext  | Fixes RTC (Real-Time Clock) memory-related issues, ensuring accurate timekeeping and preventing macOS installation problems.            |
| RealtekCardReader.kext | Provides support for Realtek RTS5129 Card Reader functionality on macOS, enabling SD card reading capabilities.                     |
| RealtekCardReaderFriend.kext | Enhances RealtekCardReader.kext support, ensuring smooth functioning of the card reader.                                        |
| RealtekRTL8111.kext  | Provides support for the Realtek RTL8168/8111 PCI-E Gigabit Ethernet controller, enabling Ethernet connectivity on macOS.             |
| SMCBatteryManager.kext | Manages laptop battery information and power management, ensuring accurate battery status reporting.                               |
| SMCProcessor.kext    | Handles System Management Controller (SMC) data related to the processor, ensuring proper CPU monitoring and control.                |
| VirtualSMC.kext      | Emulates the SMC found in genuine Apple hardware, providing essential system information for macOS to work on non-Apple hardware. |
| VoodooI2C.kext       | Supports I2C trackpad functionality on the HP ProBook 440 x360 G1, enabling multitouch gestures and improving trackpad responsiveness. |
| VoodooI2CHID.kext    | Provides support for I2C-based touchpad input devices, enhancing touchpad functionality on macOS.                                 |
| VoodooI2CSynaptics.kext | Supports Synaptics I2C-based touchpads, ensuring proper functionality and multitouch support on compatible touchpad hardware.        |
| VoodooPS2Controller.kext | Provides support for PS/2 input devices, including keyboards and mice, ensuring proper functionality of the built-in keyboard and trackpad. |
| VoodooRMI.kext       | Handles I2C-based touchpad devices, enhancing touchpad support on certain laptop models.                                           |
| WhateverGreen.kext   | Handles graphics-related patching and fixes for Intel integrated graphics, ensuring proper graphics acceleration and compatibility.   |

Please note that these kexts, along with their proper configuration in the config.plist file, are crucial for a stable and fully functional macOS experience on your HP ProBook 440 x360 G1. Ensure that you have the correct versions of these kexts and that they are compatible with your macOS version.

If you encounter any issues or plan to customize your EFI configuration further, it is essential to refer to the respective kext documentation or online forums for troubleshooting and additional information.

Remember that while these kexts enhance the macOS experience on your non-Apple hardware, using them may potentially violate Apple's End User License Agreement (EULA). Proceed at your own risk and adhere to the respective kexts' licenses and usage terms.



### How to Use

1. Clone or download this repository to your local machine.
2. Follow the setup guide in the [Wiki](link_to_wiki_or_setup_guide) to install and configure OpenCore for your HP ProBook 440 x360 G1.
3. Customize the configuration as needed for your specific system setup.
4. Enjoy running macOS on your HP ProBook 440 x360 G1!

### Contributions

Contributions to improve and optimize this EFI configuration are welcome. If you have tested it on different hardware or found ways to enhance its performance, feel free to open an issue or submit a pull request.

### Disclaimer

Using this EFI configuration and installing macOS on non-Apple hardware may violate Apple's End User License Agreement (EULA). The maintainers of this repository are not responsible for any potential issues, data loss, or damage that may occur during the installation process. Users are advised to proceed at their own risk.

### Credits

@Apple for macOS 
Give credit to any contributors, inspirations, or sources of information that helped create this EFI configuration.

