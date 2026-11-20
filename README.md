# Swarasync

An aesthetic music app for Android with a liquid-glass interface.
**Made by Purva Panchal.**

## Highlights
- Liquid-glass look: translucent surfaces, blur and refraction
- Glass Controls in Settings: adjust Blur, Tint and Refraction, with a reset button
- New "S" logo and app icon
- All the features of the original app

## Built on BitChord
Swarasync is a fork of [BitChord](https://github.com/kushagrasinghx/BitChord) by kushagrasinghx.
It is rebranded and restyled, and all original copyright notices are kept.

## Get the APK
1. Open the **Actions** tab and choose **Build Swarasync APK**.
2. Open the latest green run and scroll to **Artifacts**.
3. Download **Swarasync-debug-apk**, extract the zip, and install the `.apk`.

## How it is built
This repo holds `swarasync-changes.patch`. The workflow in `.github/workflows/build-apk.yml`
fetches BitChord at a fixed commit, applies the patch, and builds the APK with Gradle.

## License
Swarasync is free software under the GNU General Public License v3.0 (GPLv3),
the same license as BitChord. If you share this app, you must also share its source
under the same license.
