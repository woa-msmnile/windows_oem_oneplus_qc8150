# Windows Driver pack for OnePlus 7T Pro based on [SurfaceDuo-Drivers](https://github.com/WOA-Project/SurfaceDuo-Drivers/)
## [Here](https://github.com/woa-msmnile/msmnile-Drivers) is the Full Driver Pack.

![OnePlus 7T Pro Windows](https://user-images.githubusercontent.com/13377926/206026203-99d11de4-5669-467d-9085-95916beca1dc.png)

This repository contains driver binary files for OnePlus 7T Pro.
All driver binary files form a board support package to be used on OnePlus 7T Pro devices to provide hardware support for the Windows operating system.

These driver files are not perfect, typos may exist, feel free to file an issue on GitHub in case you found any.

## Current status

| Feature                | Notes                                               | Status         |
|------------------------|-----------------------------------------------------|----------------|
| 🔊 Audio              |                                                     | ✅            |
| Bluetooth              |                                                     | ✅            |
| Wifi                   |                                                     | ✅            |
| UFS                    |                                                     | ✅            |
| Touch                  |                                                     | ✅            |
| GPU                    |                                                     | ✅            |
| Battery                | Currently windows reports two batteries             | ⚠️            |
| Buttons                |                                                     | ✅            |
| Location               |                                                     | ✅            |
| Cellular Data          | Need to dump modem every sim card change.           | ⚠️            |
| Charge                 |                                                     | ⚠️            |
| 🛡️ TPM                 | Only supports Windows 11 22H2 and above.            | ⚠️            |
| 🧭 Light Sensor       |                                                     | ❌            |
| 🧭 Thermal Sensor     |                                                     | ❌            |
| Haptic                 |                                                     | ❌            |

## Resources

## Copyright, License, Disclaimers and end user license agreement

**Below notice must be present in all redistributed portions of this software**

Please see [LICENSE](LICENSE.md)

## Installing manually

For preserving charset encoding, please checkout with using:

```
git clone -c core.autocrlf=false https://github.com/woa-msmnile/msmnile-Drivers
```
