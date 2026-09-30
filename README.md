# slzn.github.io

Personal project hub. Here are my projects:

---

## ScreenOnAuto

> Mirror your Android phone screen to the Android Auto display, with media controls, touch forwarding and auto-start. Free — no paid features.

- **Android 14 and above** — install through Google Play: [sign up for a half-hourly round](https://screenonauto.lzn.idv.tw/join/), then install within 25 minutes.
- **Android 13 and below** — sideload the APK with KingInstaller, or use Google Play.

Features, requirements and install steps: [Official site](https://screenonauto.lzn.idv.tw/) · [Repository](https://github.com/slzn/ScreenOnAuto-releases)

---

## TshockLogs\_Explosives

> A TShock server plugin for Terraria that monitors and logs explosive item usage by players.

Useful for server administrators who want to track griefing or suspicious activity involving explosives.

### Features

- **Explosive Tracking** — Monitors bombs, dynamite, sticky/bouncy variants, bomb fish, and more
- **Timestamped Logs** — All usage events are written to the TShock log file with player name and coordinates
- **Configurable** — JSON config file lets you toggle console output and customize the list of tracked items

### Example Log Entries

```
UserB throws Dynamite at (66483.73, 2534)
UserA throws Bomb at (67192.53, 6445.662)
```

### Installation

1. Download the latest release
2. Extract all `.dll` files to the `Tshock/ServerPlugins` folder
3. Restart the TShock server

[View Repository](https://github.com/slzn/TshockLogs_Explosives)
