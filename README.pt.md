[English](README.md) | [日本語](README.ja.md) | [简体中文](README.zh-CN.md) | [Français](README.fr.md) | [Deutsch](README.de.md) | [Bahasa Indonesia](README.id.md) | [Italiano](README.it.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Español](README.es.md) | [ภาษาไทย](README.th.md)

# PTCGL Tracker

Uma ferramenta que salva automaticamente os logs de batalha exibidos após as partidas no Pokémon Trading Card Game Live (PTCGL).

## Download

[Baixar a versão mais recente](https://github.com/1ulce/PTCGL-Tracker-Releases/releases/latest)

| SO | Arquivo |
|---|---|
| Windows | `PTCGL Tracker.exe` |
| macOS | `PTCGL Tracker.app.zip` |

## Instalação

### Windows

1. Baixe `PTCGL Tracker.exe`
2. Coloque em qualquer pasta e execute
3. A instalação está completa quando o ícone aparece na bandeja do sistema

### macOS

1. Baixe `PTCGL Tracker.app.zip`
2. Extraia e mova `PTCGL Tracker.app` para a pasta Aplicativos
3. Na primeira execução, clique com o botão direito → "Abrir" para executar

## ⚠️ Configurações do PTCGL (Importante)

Para que a análise de replay funcione corretamente, configure as seguintes opções no PTCGL.

![Configurações do PTCGL](ptcgl-settings.png)

### 1. Ativar Modo Janela
`VIDEO OPTIONS` → **Marque "WINDOWED"**

Necessário para que o tracker acesse os arquivos de log.

### 2. Definir Idioma para Inglês
`LANGUAGE` → **Selecione "ENGLISH"**

Atualmente, apenas logs em inglês são suportados para análise de replay.

### 3. Mostrar IDs das Cartas
`BATTLE LOG SETTINGS` → **Desmarque "HIDE CARD IDS FROM EXPORT"**

Sem os IDs das cartas, as imagens das cartas não serão exibidas nos logs.

## Uso

1. Inicie o PTCGL Tracker (roda na bandeja do sistema)
2. Termine uma batalha no PTCGL
3. O botão "BATTLE LOG" na tela de resultado é clicado automaticamente
4. Os logs de batalha são salvos automaticamente em `~/PTCGLLogs/`

## Upload para a Nuvem
Crie uma conta no PTCGTools e faça login para gerenciar seus logs de batalha e decks no [site do PTCGL Replayer](https://replay.ptcgtools.com).

## Atualização Automática

Quando uma nova versão é lançada, uma notificação aparece ao iniciar o app.
Você pode atualizar facilmente pelo menu da bandeja.

## Idiomas Suportados

🇯🇵 日本語 | 🇺🇸 English | 🇨🇳 简体中文 | 🇫🇷 Français | 🇩🇪 Deutsch | 🇮🇩 Bahasa Indonesia | 🇮🇹 Italiano | 🇰🇷 한국어 | 🇧🇷 Português | 🇪🇸 Español | 🇹🇭 ภาษาไทย

## Requisitos do Sistema

- Windows 10/11
- macOS 12+

## Licença

MIT License

## Relatar Problemas

Reporte bugs e solicitações via [Issues](https://github.com/1ulce/PTCGL-Tracker-Releases/issues).
