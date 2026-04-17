[English](README.md) | [日本語](README.ja.md) | [简体中文](README.zh-CN.md) | [Français](README.fr.md) | [Deutsch](README.de.md) | [Bahasa Indonesia](README.id.md) | [Italiano](README.it.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Español](README.es.md) | [ภาษาไทย](README.th.md)

# PTCGL Tracker

Un outil qui enregistre automatiquement les journaux de combat affichés après les matchs dans Pokémon Trading Card Game Live (PTCGL).

## Téléchargement

[Télécharger la dernière version](https://github.com/1ulce/PTCGL-Tracker-Releases/releases/latest)

| OS | Fichier |
|---|---|
| Windows | `PTCGL Tracker.exe` |
| macOS | `PTCGL Tracker.app.zip` |

## Installation

### Windows

1. Téléchargez `PTCGL Tracker.exe`
2. Placez-le dans n'importe quel dossier et exécutez-le
3. L'installation est terminée lorsque l'icône apparaît dans la barre d'état système

### macOS

1. Téléchargez `PTCGL Tracker.app.zip`
2. Extrayez-le et déplacez `PTCGL Tracker.app` dans le dossier Applications
3. Au premier lancement, faites un clic droit → « Ouvrir » pour l'exécuter

## ⚠️ Paramètres PTCGL (Important)

Pour que l'analyse de replay fonctionne correctement, veuillez configurer les paramètres suivants dans PTCGL.

![Paramètres PTCGL](ptcgl-settings.png)

### 1. Activer le mode fenêtré
`VIDEO OPTIONS` → **Cocher « WINDOWED »**

Nécessaire pour que le tracker puisse accéder aux fichiers de log.

### 2. Définir la langue sur anglais
`LANGUAGE` → **Sélectionner « ENGLISH »**

Actuellement, seuls les logs en anglais sont pris en charge pour l'analyse de replay.

### 3. Afficher les ID des cartes
`BATTLE LOG SETTINGS` → **Décocher « HIDE CARD IDS FROM EXPORT »**

Sans les ID des cartes, les images des cartes ne s'afficheront pas dans les logs.

## Utilisation

1. Lancez PTCGL Tracker (il s'exécute dans la barre d'état système)
2. Terminez un combat dans PTCGL
3. Le bouton « BATTLE LOG » de l'écran de résultat est automatiquement cliqué
4. Les journaux de combat sont enregistrés automatiquement dans `~/PTCGLLogs/`

## Envoi vers le cloud
Créez un compte sur PTCGTools et connectez-vous pour gérer vos journaux de combat et decks sur le [site PTCGL Replayer](https://replay.ptcgtools.com).

## Mise à jour automatique

Lorsqu'une nouvelle version est publiée, une notification apparaît au lancement de l'application.
Vous pouvez facilement mettre à jour depuis le menu de la barre d'état.

## Langues prises en charge

🇯🇵 日本語 | 🇺🇸 English | 🇨🇳 简体中文 | 🇫🇷 Français | 🇩🇪 Deutsch | 🇮🇩 Bahasa Indonesia | 🇮🇹 Italiano | 🇰🇷 한국어 | 🇧🇷 Português | 🇪🇸 Español | 🇹🇭 ภาษาไทย

## Configuration requise

- Windows 10/11
- macOS 12+

## Licence

MIT License

## Signalement de problèmes

Veuillez signaler les bugs et les demandes via [Issues](https://github.com/1ulce/PTCGL-Tracker-Releases/issues).
