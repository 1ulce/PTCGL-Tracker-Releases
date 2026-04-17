[English](README.md) | [日本語](README.ja.md) | [简体中文](README.zh-CN.md) | [Français](README.fr.md) | [Deutsch](README.de.md) | [Bahasa Indonesia](README.id.md) | [Italiano](README.it.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Español](README.es.md) | [ภาษาไทย](README.th.md)

# PTCGL Tracker

Uno strumento che salva automaticamente i log delle battaglie mostrati dopo le partite in Pokémon Trading Card Game Live (PTCGL).

## Download

[Scarica l'ultima versione](https://github.com/1ulce/PTCGL-Tracker-Releases/releases/latest)

| OS | File |
|---|---|
| Windows | `PTCGL Tracker.exe` |
| macOS | `PTCGL Tracker.app.zip` |

## Installazione

### Windows

1. Scarica `PTCGL Tracker.exe`
2. Posizionalo in una cartella qualsiasi ed eseguilo
3. L'installazione è completata quando l'icona appare nella tray di sistema

### macOS

1. Scarica `PTCGL Tracker.app.zip`
2. Estrai e sposta `PTCGL Tracker.app` nella cartella Applicazioni
3. Al primo avvio, fai clic destro → «Apri» per eseguirlo

## ⚠️ Impostazioni PTCGL (Importante)

Affinché l'analisi dei replay funzioni correttamente, configura le seguenti impostazioni in PTCGL.

![Impostazioni PTCGL](ptcgl-settings.png)

### 1. Abilita la modalità finestra
`VIDEO OPTIONS` → **Spunta «WINDOWED»**

Necessario affinché il tracker possa accedere ai file di log.

### 2. Imposta la lingua su inglese
`LANGUAGE` → **Seleziona «ENGLISH»**

Attualmente sono supportati solo i log in inglese per l'analisi dei replay.

### 3. Mostra gli ID delle carte
`BATTLE LOG SETTINGS` → **Togli la spunta da «HIDE CARD IDS FROM EXPORT»**

Senza gli ID delle carte, le immagini delle carte non verranno visualizzate nei log.

## Uso

1. Avvia PTCGL Tracker (viene eseguito nella tray di sistema)
2. Termina una battaglia in PTCGL
3. Il pulsante «BATTLE LOG» nella schermata dei risultati viene cliccato automaticamente
4. I log delle battaglie vengono salvati automaticamente in `~/PTCGLLogs/`

## Caricamento sul cloud
Crea un account su PTCGTools e accedi per gestire i tuoi log delle battaglie e mazzi sul [sito PTCGL Replayer](https://replay.ptcgtools.com).

## Aggiornamento automatico

Quando viene rilasciata una nuova versione, al lancio dell'app apparirà una notifica.
Puoi aggiornare facilmente dal menu della tray.

## Lingue supportate

🇯🇵 日本語 | 🇺🇸 English | 🇨🇳 简体中文 | 🇫🇷 Français | 🇩🇪 Deutsch | 🇮🇩 Bahasa Indonesia | 🇮🇹 Italiano | 🇰🇷 한국어 | 🇧🇷 Português | 🇪🇸 Español | 🇹🇭 ภาษาไทย

## Requisiti di sistema

- Windows 10/11
- macOS 12+

## Licenza

MIT License

## Segnalazione problemi

Segnala bug e richieste tramite [Issues](https://github.com/1ulce/PTCGL-Tracker-Releases/issues).
