# StegoLab — Android APK

Prebuilt Android app for **StegoLab** (source: https://github.com/UnknownEng/StegoLab).

LSB image steganography on your phone — hide data/text/Python code in a PNG,
reveal and (optionally) auto-run it.

## Download & install

1. Download **`StegoLab-arm64.apk`** to your Android phone.
2. Tap it; if prompted, allow **"install from unknown sources"** for your file manager/browser.
3. Open **StegoLab**.

- **Architecture:** arm64-v8a (covers essentially all phones from the last ~7 years)
- **Min Android:** 7.0 (API 24) · **Built with:** Python 3.11.9, Kivy 2.3.0
- **Verified running on:** Pixel 6 (Android 17)
- **SHA-256:** `be1ccec8f105ebb91bb84cbdec013657d92f6fcc5d26dc569dfd3fb69961c8b6`

## Safety

Educational tool. The "auto-run revealed code" feature runs Python hidden in
an image. Only reveal images you trust, and never put this app on someone
else's device to run code they can't see.
