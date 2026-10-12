# XNotify

Shows your Xiaomi phone's notifications on your Xiaomi tablet, **for every app**, on the **HyperOS 4 China ROM**.

## Features
- Every app: HyperOS only syncs a few Chinese apps; pick any phone app on the tablet (Telegram, WhatsApp, Instagram, SMS, calls…)
- Unlocks the Receive screen the CN tablet ROM hides (Settings → Interconnectivity → Notifications)
- App picker with icons sent from the phone, plus "Refresh from phone"
- Big app icon, source device and app name in the title
- Works while the phone is in use, not only when locked
- Non-China Xiaomi accounts (EU, US, UA…) on CN ROMs supported
- Skips apps also installed on the tablet (no duplicates)
- UI languages: English, Türkçe, Русский, Español, 简体中文

## Requirements
- Xiaomi phone and tablet on HyperOS 4 China ROM (Android 17), same Xiaomi account, Wi-Fi and Bluetooth on
- Root and LSPosed (API 102) on **both** devices

## Install
1. Install on **both** the phone and the tablet, enable in LSPosed (scope: `com.milink.service`).
2. Reboot both devices.
3. On the tablet: Settings → Interconnectivity → Notifications → Receive → your phone, then turn on the apps you want.

No app icon or settings screen: the tablet's own notification screen controls everything.

## Source code and support
- Source: https://github.com/Leekin2/XNotify (GPL-3.0)
- Telegram channel: https://t.me/xioamifetiscisi
- Feedback and suggestions: [@emcleek](https://t.me/emcleek)
