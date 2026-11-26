# AnimeTV — Developer Builds

Public testing builds for **AnimeTV** (Android TV / Mobile & Windows).
These builds contain early fixes and experimental features before stable releases.

> **Note:** Developer builds may contain bugs. Back up your settings/watch history before updating.

## Downloads

Download the latest build from the **[Releases](../../releases)** page:

| Platform | File | Notes |
|---|---|---|
| **Android / Android TV** | `animetv-<version>-release.apk` | Sideload APK (Android 5.1+ / API 22+) |
| **Windows (Installer)** | `animetv-<version>-setup.exe` | Standard Windows x64 installer |
| **Windows (Portable)** | `AnimeTV-win32-x64-portable.zip` | Extract and run `AnimeTV.exe` |

## Installation

### Android TV / Android
1. Download `animetv-<version>-release.apk` from the latest release.
2. Enable **Install from Unknown Sources** for your file manager or browser.
3. Install the APK (or sideload via `adb install -r animetv-<version>-release.apk`).

### Windows
- **Installer:** Run `animetv-<version>-setup.exe`.
- **Portable:** Extract `AnimeTV-win32-x64-portable.zip` to a folder and launch `AnimeTV.exe`.

## Reporting Bugs
Open an issue using the **Bug Report** template and include:
- Build version (e.g. `v5.15.4-dev`)
- Platform (Android TV model / Windows version)
- Steps to reproduce + screenshots or console/logcat output if available

## Disclaimer
This repository distributes compiled testing builds only.
