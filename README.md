# zentosh
Hackintosh/OpenCore EFI for MSI B450 Tomahawk MAX
***
### A few words:
This is a copy of the EFI folder I'm using on a Monterey (12.3.1) hackintosh MacOS AMD Ryzen machine. It's specific for the hardware mentioned below. Do NOT use it if you don't have the same hardware or don't know what you're doing as I'm NOT responsible if you break something. This EFI was created by following the guide made by [acidanthera](https://github.com/acidanthera) which can be found [here](https://dortania.github.io/getting-started/).
### Hardware:
- CPU: AMD Ryzen 5 3600 (AM4 - 6-Core, 12-Threads)
- MEM: Patriot Viper 4 Blackout DDR4 (2x8GB) @ 3200MHz
- MOBO: MSI B450 MSI Tomahawk MAX 
- SSD/HDD: Crucial MX500 1TB SSD Drive ~~+ WD RAID Edition (RE) 4TB Enterprise SATA HDD~~
- GFX: Sapphire Nitro+ RX580 8GB GDDR5
### What works:
- Everything, except the USB-C fast charging (will be fixed soon)
### What's NOT included in the EFI/config.plist:
- Wireless/Bluetooth support
- NVMe/M.2 support
### Don't forget to:
- Run GenSMBIOS and update SystemSerialNumber, MLB, ROM and UUID values for your system in PlatformInfo -> Generic
- Create Vault for the EFI folder (or set Misc -> Security -> Vault to Optional in config.plist, if you don't want to use vault)
### Big thanks to:
- [acidanthera](https://github.com/acidanthera)
- [alyxferrari](https://github.com/alyxferrari)
- [Mieze](https://github.com/Mieze)
- AMD OSX Discord community (https://discord.gg/EfCYAJW)
