# Windows Driver pack for OnePlus 7T Pro based on [SurfaceDuo-Drivers](https://github.com/WOA-Project/SurfaceDuo-Drivers/)
## [Here](https://github.com/woa-msmnile/msmnile-Drivers) is the Full Driver Pack.

This repository contains driver binary files for OnePlus 7T Pro.
All driver binary files form a board support package to be used on OnePlus 7T Pro devices to provide hardware support for the Windows operating system.

These driver files are not perfect, typos may exist, feel free to file an issue on GitHub in case you found any.

| Feature                | Notes                                                                                                                                         | Status         |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|----------------|
| Bluetooth              |                                                                                                                                               | ✅            |
| WiFi                   |                                                                                                                                               | ✅            |
| UFS                    |                                                                                                                                               | ✅            |
| Touch                  | Currently using a temporary driver, will be replaced with a proper one later                                                                  | ✅            |
| GPU                    |                                                                                                                                               | ✅            |
| Battery                |                                                                                                                                               | ✅            |
| Buttons                |                                                                                                                                               | ✅            |
| Light Sensor           |                                                                                                                                               | ❌            |
| Thermal Sensor         |                                                                                                                                               | ❌            |
| Haptic                 |                                                                                                                                               | ❌            |
| Cellular Data          | Only if you copy modemfs files using [this guide](https://github.com/WOA-Project/SurfaceDuo-Guides/blob/main/Status.md#important-information) | ✅            |
| Charge                 |                                                                                                                                               | ✅            |

## Resources

## Copyright, License, Disclaimers and end user license agreement

**Below notice must be present in all redistributed portions of this software**

Copyright (c) 2022-2022 WOA-msmnile

Copyright (c) 2017-2022 WOA-Project

Copyright (c) 2011-2020 Qualcomm Incorporated

Copyright (c) 2019-2022 Microsoft Corporation

This repository contains binary files sourced from Qualcomm Snapdragon 8cx laptops/tablets as well as the Surface Duo original android firmware. As some mistakes may exist, we cannot provide warranty of any kind. 

- By installing this driver pack, you agree that any damage done to your phone or any loss of data is your entire responsibility and we cannot be taken responsible for data loss if it ever happens. We believe however this driver pack is safe to install. Try at your own risk!


The above copyright notice and this permission notice shall be included in all

copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR

IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,

FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE

AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER

LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,

OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE

SOFTWARE.

## Installing manually

For preserving charset encoding, please checkout with using:

```
git clone -c core.autocrlf=false https://github.com/woa-msmnile/msmnile-Drivers
```
