[English](README.md) | [日本語](README.ja.md) | [简体中文](README.zh-CN.md) | [Français](README.fr.md) | [Deutsch](README.de.md) | [Bahasa Indonesia](README.id.md) | [Italiano](README.it.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Español](README.es.md) | [ภาษาไทย](README.th.md)

# PTCGL Tracker

A tool that automatically saves battle logs displayed after matches in Pokémon Trading Card Game Live (PTCGL).

## Download

[Download the latest version](https://github.com/1ulce/PTCGL-Tracker-Releases/releases/latest)

| OS | File |
|---|---|
| Windows | `PTCGL Tracker.exe` |
| macOS | `PTCGL Tracker.app.zip` |

## Installation

### Windows

1. Download `PTCGL Tracker.exe`
2. Place it in any folder and run it
3. Setup is complete when the icon appears in the system tray

### macOS

1. Download `PTCGL Tracker.app.zip`
2. Extract it and move `PTCGL Tracker.app` to the Applications folder
3. On first launch, right-click → "Open" to run it

## ⚠️ PTCGL Settings (Important)

To make replay analysis work correctly, please configure the following settings in PTCGL.

![PTCGL Settings](ptcgl-settings.png)

### 1. Enable Window Mode
`VIDEO OPTIONS` → **Check "WINDOWED"**

Required for the tracker to access log files.

### 2. Set Language to English
`LANGUAGE` → **Select "ENGLISH"**

Currently, only English logs are supported for replay analysis.

### 3. Show Card IDs
`BATTLE LOG SETTINGS` → **Uncheck "HIDE CARD IDS FROM EXPORT"**

Card images will not display in logs without card IDs.

## Usage

1. Launch PTCGL Tracker (it runs in the system tray)
2. Finish a battle in PTCGL
3. The "BATTLE LOG" button on the result screen is automatically clicked
4. Battle logs are saved automatically to `~/PTCGLLogs/`

## Cloud Upload
Create an account on PTCGTools and log in to manage your battle logs and decks on the [PTCGL Replayer website](https://replay.ptcgtools.com).

## Auto Update

When a new version is released, a notification will appear at app launch.
You can easily update from the tray menu.

## Supported Languages

🇯🇵 日本語 | 🇺🇸 English | 🇨🇳 简体中文 | 🇫🇷 Français | 🇩🇪 Deutsch | 🇮🇩 Bahasa Indonesia | 🇮🇹 Italiano | 🇰🇷 한국어 | 🇧🇷 Português | 🇪🇸 Español | 🇹🇭 ภาษาไทย

## System Requirements

- Windows 10/11
- macOS 12+

## License

MIT License

## Report Issues

Please report bugs and requests via [Issues](https://github.com/1ulce/PTCGL-Tracker-Releases/issues).
