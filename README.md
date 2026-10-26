# LocalConnect

Secure local-network file sharing and user-approved remote control for Windows, Linux and Android.

## Download

| Platform | Package | Direct download |
|---|---|---|
| Windows 10/11 · x64 | Installer · 0.2.1 | [Download Windows installer](https://github.com/TakbirZaman/LocalConnect-Downloads/releases/download/v0.2.1-beta.2/LocalConnect-Windows-x64-Setup-0.2.1.exe) |
| Linux · x64 | Archive · 0.2.1 · Ubuntu 24.04 build | [Download Linux archive](https://github.com/TakbirZaman/LocalConnect-Downloads/releases/download/v0.2.1-beta.2/LocalConnect-Linux-x64-0.2.1.tar.gz) |
| Android 8+ · ARM64 | Release-signed APK · 0.2.0 | [Download Android APK](https://github.com/TakbirZaman/LocalConnect-Downloads/releases/download/v0.2.1-beta.2/LocalConnect-Android-arm64-Signed-0.2.0.apk) |

[All packages and release notes](https://github.com/TakbirZaman/LocalConnect-Downloads/releases/tag/v0.2.1-beta.2) · [SHA-256 checksums](https://github.com/TakbirZaman/LocalConnect-Downloads/releases/download/v0.2.1-beta.2/SHA256SUMS.txt)

These links download the packages directly. No GitHub account is required.

## Get started

1. Install LocalConnect on both devices.
2. Connect both devices to the same trusted Wi-Fi/LAN.
3. Open the app, select the other device, and follow the pairing prompts.
4. Select files to send. Remote control requires separate approval on the controlled device.

**Windows:** install once, then open LocalConnect from the Start menu. Use **Open received files** inside the app to find received files. Close the running app before upgrading.

**Linux:** extract the archive, then run `./LocalConnect/localconnect`. This x64 package was built on Ubuntu 24.04 and requires compatible GTK 3/runtime libraries. Capture/input support depends on the desktop session and its permissions.

**Android:** install the APK using Android's normal installation flow. Screen sharing requires fresh system capture consent; remote input requires the user to enable the supported Accessibility service. Follow permission prompts inside the app.

## Beta status

- These packages are for testing and are not a certified production release.
- Windows publisher signing is not configured. Android is release-signed; Google approval is not established.
- Screen streaming currently uses PNG at up to 4 fps with one desktop display.
- LocalConnect operates over the local network. Internet relay connections are not provided.
- Resumable transfer and cryptographic verification protect file integrity; connections can still fail.

This repository distributes packages and download documentation. Application source code and signing keys are not included.

Developed by Takbir Zaman Bhuiyan.
