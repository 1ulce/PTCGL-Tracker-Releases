[English](README.md) | [日本語](README.ja.md) | [简体中文](README.zh-CN.md) | [Français](README.fr.md) | [Deutsch](README.de.md) | [Bahasa Indonesia](README.id.md) | [Italiano](README.it.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Español](README.es.md) | [ภาษาไทย](README.th.md)

# PTCGL Tracker

Una herramienta que guarda automáticamente los registros de batalla mostrados después de las partidas en Pokémon Trading Card Game Live (PTCGL).

## Descarga

[Descargar la última versión](https://github.com/1ulce/PTCGL-Tracker-Releases/releases/latest)

| SO | Archivo |
|---|---|
| Windows | `PTCGL Tracker.exe` |
| macOS | `PTCGL Tracker.app.zip` |

## Instalación

### Windows

1. Descarga `PTCGL Tracker.exe`
2. Colócalo en cualquier carpeta y ejecútalo
3. La instalación se completa cuando el icono aparece en la bandeja del sistema

### macOS

1. Descarga `PTCGL Tracker.app.zip`
2. Extráelo y mueve `PTCGL Tracker.app` a la carpeta Aplicaciones
3. En el primer inicio, haz clic derecho → «Abrir» para ejecutarlo

## ⚠️ Configuración de PTCGL (Importante)

Para que el análisis de repeticiones funcione correctamente, configure los siguientes ajustes en PTCGL.

![Configuración de PTCGL](ptcgl-settings.png)

### 1. Habilitar modo ventana
`VIDEO OPTIONS` → **Marcar «WINDOWED»**

Necesario para que el tracker acceda a los archivos de registro.

### 2. Configurar idioma a inglés
`LANGUAGE` → **Seleccionar «ENGLISH»**

Actualmente, solo los registros en inglés son compatibles con el análisis de repeticiones.

### 3. Mostrar IDs de cartas
`BATTLE LOG SETTINGS` → **Desmarcar «HIDE CARD IDS FROM EXPORT»**

Sin los IDs de las cartas, las imágenes de las cartas no se mostrarán en los registros.

## Uso

1. Inicia PTCGL Tracker (se ejecuta en la bandeja del sistema)
2. Termina una batalla en PTCGL
3. El botón «BATTLE LOG» de la pantalla de resultado se hace clic automáticamente
4. Los registros de batalla se guardan automáticamente en `~/PTCGLLogs/`

## Subida a la nube
Crea una cuenta en PTCGTools e inicia sesión para gestionar tus registros de batalla y mazos en el [sitio de PTCGL Replayer](https://replay.ptcgtools.com).

## Actualización automática

Cuando se lance una nueva versión, aparecerá una notificación al iniciar la app.
Puede actualizar fácilmente desde el menú de la bandeja.

## Idiomas compatibles

🇯🇵 日本語 | 🇺🇸 English | 🇨🇳 简体中文 | 🇫🇷 Français | 🇩🇪 Deutsch | 🇮🇩 Bahasa Indonesia | 🇮🇹 Italiano | 🇰🇷 한국어 | 🇧🇷 Português | 🇪🇸 Español | 🇹🇭 ภาษาไทย

## Requisitos del sistema

- Windows 10/11
- macOS 12+

## Licencia

MIT License

## Reportar problemas

Por favor, reporta errores y solicitudes a través de [Issues](https://github.com/1ulce/PTCGL-Tracker-Releases/issues).
