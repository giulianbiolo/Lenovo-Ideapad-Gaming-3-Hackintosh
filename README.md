# Lenovo-Ideapad-Gaming-3-Hackintosh

### Supported Devices
> - **Lenovo Ideapad Gaming 3**
### MacOs supported versions
> - MacOs `10.5` Catalina
> - MacOS `11.6` Big Sur
> - MacOS `12.0` Monterey
### IMPORTANT:
**Remember to change `AirportItlwm.kext` according to your OS X version. \
If you're upgrading to `Monterey` from older OS's remember to follow the OC guide to fix your bluetooth kexts. \
Alternatively you can just download the right release.**

## Laptop Configuration

| Hardware    | Additional Information                                                         |
| ----------- | ------------------------------------------------------------ |
| CPU         | Intel(R) Core(TM) i7-10750H（UHD Graphics 630）               |
| Memory      | 16 GB SO-DIMM DDR4 3200MHz                                   |
| DISK        | PCIe M.2 NVMe SSD 500GB + 1TB 5400 HDD                       |
| Graphics    | UHD Graphics 630                                             |
| Monitor     | FHD 1920x1080 IPS 250nits 60Hz                               |
| Network     | Realtek 8822CE 11AC (2x2) & Bluetooth® 5.0                   |
| Trackpad    | Intel I2C HID MSFT0001                                       |

## Compatibility Status:

| Status | Name                 | Additional Information                                                         |
| :----: | -------------------- | ------------------------------------------------------------ |
|   ✅   | WiFi                | I'm using AirportItlwm Kext, make sure to change it accordingly to your OS X version downloading it from https://github.com/OpenIntelWireless/itlwm |
|   ✅    | Bluetooth          | Works flawlessly with almost every device, even tought I couldn't make it work with my cheap bluetooth mouse, it's probably the mouse's fault |
|   ✅    | USB's                 | All USB's work just fine, they've been mapped with USBMap   |
|   ✅    | Keyboard + Backlight  | Works just like on Windows, using the Fn key to power on/off the backlight |
|   ✅    | Speakers                 | Here I'm using AppleALC Kext, make sure to keep it updated   |
|   ✅    | Microphone                 |   |
|   ✅    | Webcam                |                                    |
|   ✅    | Trackpad + Gestures      | Here I'm using SSDT-GPIO.aml in combination with VooDooI2C and VooDooI2CHID Kexts   |
|   ✅    | Battery + Status               |                                    |
|   ❌    | HDMI               |    |
|   ❌    | Nvidia GTX 1650 Ti               |  Unfortunately Nvidia Drivers for OS X 10.5 or greater don't exist  |
