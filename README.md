<p align="center">
       <img height="256px" src="app/src/main/assets/XenDroid_foreground.png"/>
    </a>
</p>

<h1 align="center">Xendroid Ludashi - Android Xbox 360 Emulator</h1>

## History
Xendroid Ludashi was initially forked from XenDroid, which was based off xa360e and [Xenia Canary](https://github.com/xenia-canary/xenia-canary).
However, a complete rebase was made on [Xenia Edge](https://github.com/has207/xenia-edge) with a new Kotlin backend.
We are looking forward to keeping the project updated alongside the Edge fork,
and keeping the code compatible with Xenia licenses.

## Be aware of scams
- Xendroid Ludashi is a free project. If you paid for this, then you got scammed.
- The ONLY reliable source for the apk is in the [releases](https://github.com/talya9141-cmyk/Xendroid-Ludashi/releases/latest) section, along with the distributed source code.
  - We cannot be held responsible for edited apks by unknown users, you have been warned.

## Issue Policy
To avoid unnecessary toxicity, issues have been limited to contributors only. If you want to report issues,
you can use the `xenia-android` channel on Xenia's discord and reach out to us. Only detailed reports will be
taken into consideration. Generic and repeated complaints will be ignored.

In order to give detailed reports, you must compare the android port with `Xenia Edge` using `Vulkan` as a backend. Make sure that the
issues can be reproduced only on Android. If the issues are on Edge too, then we wait for the developers to fix
them, and align the port as a consequence.


## Building

See [BUILD.md](BUILD.md) for build instructions.

## LICENSE

Please check the LICENSE file under the appropriate file header and directory for detailed information.

## Device Requirements
- Snapdragon SoC, GEN 2 or higher
- Adreno GPU 740 or higher. Lower 7xx have not been tested.
- I tried to use UHD Intel graphics and I3 gen 10th cpu as i dont have powerful android device so i use emulation but nearest gpu to uhd using emulation is The Nearest Equivalent: It performs close to a Qualcomm Adreno 512 / Adreno 508 or an older ARM Mali-G71 MP2 found in mid-range smartphones from the 2017–2018 era (like chips used in older Snapdragon 6-series processors).
  
## Recommended Drivers
- You can get the drivers for your GPU from two sources
  - [Whitebelyash upstream drivers](https://github.com/whitebelyash/AdrenoToolsDrivers/releases)
    - This is an All-In-One driver for a wide range of GPUs
  - [StevenMXZ forked drivers](https://github.com/StevenMXZ/Adreno-Tools-Drivers/releases)
    - This one has different drivers for each GPU series

# Applying the driver
- Check your device specs with [CPU X](https://play.google.com/store/apps/details?id=com.abs.cpu_z_advance&hl=it) to get the matching driver.
- To apply the drivers go to **Settings** > **Vulkan** > **Custom Vulkan Driver**, then select the zip file.

## About Donations
I would like to take this opportunity to help a friend out. If you are willing to make donations, please consider donating to
[Bitshifter's Kofi](https://ko-fi.com/bitsh1ft3r/goal?g=0). He's the maintainer of the [Xenon Project](https://github.com/xenon-emu/xenon)
and every donation can help making a difference for the maintainer.
Thank you - talya9141-cmyk
