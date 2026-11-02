# Barcode Generator

Official desktop downloads for macOS, Windows, and Linux.

## Download

**[Download the latest version](https://github.com/Samolevsky/Barcode-Generator-Releases/releases/latest)**

Choose the installer for your platform:

| Platform | Download filename |
| --- | --- |
| macOS — Apple Silicon (M-series) | `BarcodeGenerator-VERSION-mac-arm64.dmg` |
| macOS — Intel | `BarcodeGenerator-VERSION-mac-intel.dmg` |
| Windows — x64 | `BarcodeGenerator-VERSION-win-x64.exe` |
| Linux — x64 | `BarcodeGenerator-VERSION-linux-x86_64.AppImage` |

[All versions and release notes](https://github.com/Samolevsky/Barcode-Generator-Releases/releases)

### Verify a download

Download `SHA256SUMS.txt` from the same release and compare the checksum of your installer:

- macOS: `shasum -a 256 path/to/installer.dmg`
- Linux: `sha256sum path/to/installer.AppImage`
- Windows PowerShell: `Get-FileHash path/to/installer.exe -Algorithm SHA256`

### Signing notice

Current installers are unsigned, and macOS builds are not notarized. macOS Gatekeeper and Windows SmartScreen may warn or block installation. Download only from this official repository. Automated tests and installer builds have passed; manual installation smoke tests have not been performed for version 0.2.3.

## About

Barcode Generator creates and scans barcodes, supports customizable colors and appearance, and offers PNG and SVG export. Some export features require a Pro license.

This repository distributes release installers and download documentation only. It does not contain the application source code. The application is proprietary and distributed under its EULA; public downloads do not grant an open-source license.

[Product and support](https://samolevsky.com/)
