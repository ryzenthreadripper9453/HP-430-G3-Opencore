# HP-430-G3-opencore

![](hackintosh-laptop.png)

OpenCore 0.6.4 setup for running Hackintosh on HP ProBook 430 G3

### Laptop Specifications:
- Intel Core i5 6200U CPU (Skylake)
- Intel HD 520 Graphics
- 12GB DDR4-2133MHz RAM
- 13.3 1366x768 Display
- Synaptics PS2 TouchPad
- Intel Dual Band Wi-Fi and Bluetooth Card (Will Replace)
- 2 USB 3.0 Ports, 1 USB 2.0 Ports
- HDMI Port
- SD Card Reader
- Intel SATA SSD 180G+WD M.2 SATA 240G SSD

### BIOS Setup:
- Disable Fast Boot
- Disable Power On when AC Detected
- Disable Power On when Lid is Opened
- Disable Secure Boot
- Disable Legacy Boot
- Enable Turbo Boost
- Enable Hyperthreading
- Enable Multi Processor
- Enable VT-x
- Disable Wake on LAN
- Video Memory Size: 64MB
- Enable Runtime Power Management
- Disable Extended Idle Power States
- Enable Deep Sleep
- Disable Wake when Lid is Opened
- Disable Wake on USB
- Enable Power Control

### What works:
- macOS Catalina 10.15.7
- UEFI booting via OpenCore
- Built-in keyboard (with special function keys)
- Built-in trackpad (basic gestures)
- Brightness Control Hotkeys
- Audio Control Hotkeys
- HDMI Video and Audio
- Native Wifi and Ethernet
- Bluetooth and AirDrop
- Native audio with AppleALC, including headphone
- Built-in mic
- Native power management
- Battery status
- USB 3.0 Ports
- Ethernet
- Audio on internal speaker and headphone
- Sleep and Wake

### What doesn't work:
- FingerPrint Reader
- SD Card Reader
- Integrated Camera (I don't need it)
- Bluetooth and AirDrop (Not replaced Wireless network card)
