# Run Fiji "native"-ly on Apple Silicon

This guide provides step-by-step instructions for running Fiji on Apple Silicon as a native process.

![screenshot](https://github.com/nghlt/fiji-launcher-macOS-arm/blob/344c767126733ee118aef403cab8722c29a8b91b/fiji-arm.png)

## Requirements
- Fiji (latest): [Click here to download](https://downloads.imagej.net/fiji/latest/fiji-macosx.zip)
- Fiji ARM: [Click here to download](https://downloads.imagej.net/fiji/archive/<redacted>/fiji-macosx-arm64.zip)
- Universal binary launcher: Download the latest release from [here](https://github.com/nghlt/fiji-launcher-macOS-arm/releases)

## Procedure
1. Download and uncompress both the Fiji packages.
2. Right click on the Fiji ARM package and choose `Show Package Contents` to expand the app folder.
3. Copy the `java` folder and replace the corresponding folder in the latest Fiji package.
4. Copy the `Contents` folder from the latest release of the universal binary launcher and replace the `Contents` folder in the latest Fiji package.

## Credit
- Original repository: [evanheller/fiji-launcher-macOS-arm](https://github.com/evanheller/fiji-launcher-macOS-arm)
- Universal binary launcher: [Universal (x86/arm64) launcher for Mac OS](https://github.com/imagej/imagej-launcher/issues/82)
