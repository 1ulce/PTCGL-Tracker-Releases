[English](README.md) | [日本語](README.ja.md) | [简体中文](README.zh-CN.md) | [Français](README.fr.md) | [Deutsch](README.de.md) | [Bahasa Indonesia](README.id.md) | [Italiano](README.it.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Español](README.es.md) | [ภาษาไทย](README.th.md)

# PTCGL Tracker

Ein Tool, das die nach Kämpfen in Pokémon Trading Card Game Live (PTCGL) angezeigten Kampf-Logs automatisch speichert.

## Download

[Neueste Version herunterladen](https://github.com/1ulce/PTCGL-Tracker-Releases/releases/latest)

| OS | Datei |
|---|---|
| Windows | `PTCGL Tracker.exe` |
| macOS | `PTCGL Tracker.app.zip` |

## Installation

### Windows

1. `PTCGL Tracker.exe` herunterladen
2. In einen beliebigen Ordner legen und ausführen
3. Die Installation ist abgeschlossen, wenn das Symbol im System-Tray erscheint

### macOS

1. `PTCGL Tracker.app.zip` herunterladen
2. Entpacken und `PTCGL Tracker.app` in den Programme-Ordner verschieben
3. Beim ersten Start mit Rechtsklick → „Öffnen" ausführen

## ⚠️ PTCGL-Einstellungen (Wichtig)

Damit die Replay-Analyse korrekt funktioniert, nehmen Sie bitte die folgenden Einstellungen in PTCGL vor.

![PTCGL-Einstellungen](ptcgl-settings.png)

### 1. Fenstermodus aktivieren
`VIDEO OPTIONS` → **„WINDOWED" anhaken**

Erforderlich, damit der Tracker auf Log-Dateien zugreifen kann.

### 2. Sprache auf Englisch einstellen
`LANGUAGE` → **„ENGLISH" auswählen**

Derzeit werden nur englische Logs für die Replay-Analyse unterstützt.

### 3. Karten-IDs anzeigen
`BATTLE LOG SETTINGS` → **Haken bei „HIDE CARD IDS FROM EXPORT" entfernen**

Ohne Karten-IDs werden keine Kartenbilder in den Logs angezeigt.

## Verwendung

1. PTCGL Tracker starten (läuft im System-Tray)
2. Einen Kampf in PTCGL beenden
3. Der „BATTLE LOG"-Knopf auf dem Ergebnisbildschirm wird automatisch geklickt
4. Kampf-Logs werden automatisch in `~/PTCGLLogs/` gespeichert

## Cloud-Upload
Erstellen Sie ein Konto bei PTCGTools und melden Sie sich an, um Ihre Kampf-Logs und Decks auf der [PTCGL Replayer-Website](https://replay.ptcgtools.com) zu verwalten.

## Automatische Aktualisierung

Wenn eine neue Version veröffentlicht wird, erscheint beim Start der App eine Benachrichtigung.
Sie können einfach über das Tray-Menü aktualisieren.

## Unterstützte Sprachen

🇯🇵 日本語 | 🇺🇸 English | 🇨🇳 简体中文 | 🇫🇷 Français | 🇩🇪 Deutsch | 🇮🇩 Bahasa Indonesia | 🇮🇹 Italiano | 🇰🇷 한국어 | 🇧🇷 Português | 🇪🇸 Español | 🇹🇭 ภาษาไทย

## Systemanforderungen

- Windows 10/11
- macOS 12+

## Lizenz

MIT License

## Probleme melden

Bitte melden Sie Fehler und Wünsche über [Issues](https://github.com/1ulce/PTCGL-Tracker-Releases/issues).
