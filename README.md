# HP-250-G5-OpenCore
This is a preconfigured OpenCore EFI for the (i3-5005u) HP 250 G5 Variant
![Screenshot 2023-03-08 at 11 51 57 AM](https://user-images.githubusercontent.com/83425771/223830789-021e2833-6534-4d70-b51d-f0a1f6de5550.png)
**What Works**:
- Synaptics SMBus Touchpad
- Intel HD 5500 Graphics
- Keyboard
- Camera
- FileVault
- Sleep
- iMessage & Other iCloud Services
- USB Ports
- Battery Status
- Audio: ALC282 (Fixed with ACPI Fixup)
- Headphone Port
- WiFi & Bluetooth: BCM943224PCIEBT2 (If you have an Intel WiFi Chipset, Use AirPortItlwm)

**What's not working**:
- HDMI Audio: Known Issue with this model
- Realtek PCIE Card Reader
- Intel Power Management: CFG Lock must be disabled in order to properly get this working (Bypassed with XCPM Quirks)

**Tested macOS Versions**:
- macOS Catalina
- macOS Big Sur
- macOS Monterey
- macOS Ventura

**Credits**:
- [OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/ "OpenCore Guide"): (**they really helped make this possible**)
- [OpenCore Legacy Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher "OpenCore Legacy Patcher"): (**Helping with Graphics Acceleration**)
- [Acidanthera](https://github.com/acidanthera/ "Acidanthera"): (**For most of the kexts included in this EFI**)
