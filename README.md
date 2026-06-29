# slzn.github.io

Personal project hub. Here are my projects:

---

## ScreenOnAuto

> Mirror your Android phone screen to Android Auto display, with support for media button controls.

**How to install depends on your Android version:**

- **Android 13 and below** — sideload the APK (see the repository for steps), or join the Play beta.
- **Android 14 and above** — install via the **Play Store beta** by [joining the tester list](https://github.com/slzn/ScreenOnAuto-releases/wiki/Join-the-Beta-Test).

### Features

- **Screen Mirroring** — Real-time phone screen mirroring to the Android Auto head unit
- **Media Session Proxy** — Control any phone media app from Android Auto's native media UI
- **Auto Dim** — Automatically dim phone screen brightness during idle mirroring (15/30/60/120 s delay)
- **Auto Start** — Begin mirroring automatically when Android Auto connects
- **Prevent Sleep** — Prevent the phone screen from sleeping during mirroring
- **Stop on Disconnect** — Automatically stop mirroring when Android Auto disconnects
- **Auto Launch App** — Automatically launch a chosen app on the phone when mirroring starts and Android Auto is connected
- **Force Landscape** — Force the phone into landscape while mirroring; auto-starts on connect, with an on-screen toggle
- **Launch Shortcuts** — Add up to 4 app quick-launch buttons to the Android Auto mirror screen
- **Touch Forwarding** *(Experimental)* — Tap/scroll/fling the AA display to control your phone

### Requirements

- Android 7.0 (API 24) or higher
- Android Auto installed on phone
- A vehicle supporting Android Auto

Free to use. No features require additional payment.

[View Repository](https://github.com/slzn/ScreenOnAuto-releases)

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
