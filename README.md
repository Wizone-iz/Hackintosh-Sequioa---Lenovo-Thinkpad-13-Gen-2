# Hackintosh-Sequioa -Lenovo-Thinkpad-13-Gen-2

Custom Boot Entry Using RefindPlus system: Dual BOOT EFI using Windows 11 & Hackintosh Sequioa

Brand : Lenovo ThinkPad 13 Gen 2  
Processor : Intel® Core™ i5-7200U / i7-7500U (Kaby Lake)  
iGPU : Intel HD Graphics 620  
dGPU : None (iGPU only)  
RAM : 8GB / 16GB DDR4 (soldered)  
Audio Codec : Realtek ALC3246 (ALC256) – typically alcid=13 or 56  
Trackpad : Synaptics / ELAN I2C Precision Touchpad  
Storage : M.2 SATA / NVMe SSD  
Wireless LAN : Intel 8260 / 8265 (requires AirportItlwm)  
Ethernet : Not available (ThinkPad 13 Gen 2 has no LAN port)  
Bootloader : OpenCore 1.0.6  
OS Version : macOS Sequoia

## What's Working
- Intel HD Graphics 620 with full acceleration  
- Audio (Realtek ALC256)  
- Keyboard  
- Trackpad (I2C)  
- USB ports  
- Sleep / Wake  
- Battery status  
- HDMI out  
- SSD (NVMe / SATA)  
- All sensors (with SMC kexts)  
- Wi-Fi (using **AirportItlwm + HeliPort**)  

## Not Working
- **Bluetooth** (Intel Bluetooth unsupported on macOS Sequoia)  
- **Brightness control** (requires additional ACPI patch or driver mapping)

https://www.mediafire.com/file/m1ton942rpx5j31/EFI.zip/file
