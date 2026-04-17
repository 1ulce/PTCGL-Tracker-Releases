[English](README.md) | [日本語](README.ja.md) | [简体中文](README.zh-CN.md) | [Français](README.fr.md) | [Deutsch](README.de.md) | [Bahasa Indonesia](README.id.md) | [Italiano](README.it.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Español](README.es.md) | [ภาษาไทย](README.th.md)

# PTCGL Tracker

一款自动保存宝可梦集换式卡牌游戏Live（PTCGL）对战后显示的战斗日志的工具。

## 下载

[下载最新版本](https://github.com/1ulce/PTCGL-Tracker-Releases/releases/latest)

| 操作系统 | 文件 |
|---|---|
| Windows | `PTCGL Tracker.exe` |
| macOS | `PTCGL Tracker.app.zip` |

## 安装方法

### Windows

1. 下载 `PTCGL Tracker.exe`
2. 放置到任意文件夹并运行
3. 系统托盘中出现图标即表示启动完成

### macOS

1. 下载 `PTCGL Tracker.app.zip`
2. 解压后将 `PTCGL Tracker.app` 移至应用程序文件夹
3. 首次启动时请右键 → “打开” 来运行

## ⚠️ PTCGL 设置（重要）

为了让回放分析正常工作，请在 PTCGL 中进行以下设置。

![PTCGL 设置](ptcgl-settings.png)

### 1. 启用窗口模式
`VIDEO OPTIONS` → **勾选 “WINDOWED”**

追踪器访问日志文件所必需。

### 2. 将语言设置为英语
`LANGUAGE` → **选择 “ENGLISH”**

目前仅支持英语日志的回放分析。

### 3. 显示卡牌 ID
`BATTLE LOG SETTINGS` → **取消勾选 “HIDE CARD IDS FROM EXPORT”**

没有卡牌 ID 时，日志中不会显示卡牌图片。

## 使用方法

1. 启动 PTCGL Tracker（常驻系统托盘）
2. 在 PTCGL 中结束一场对战
3. 结果画面的 “BATTLE LOG” 按钮会被自动点击
4. 战斗日志会自动保存到 `~/PTCGLLogs/`

## 上传到云端
在 PTCGTools 创建账号并登录后，您可以在 [PTCGL Replayer 网站](https://replay.ptcgtools.com) 管理您的对战日志和卡组。

## 自动更新

发布新版本时，应用启动时会显示通知。
可以通过托盘菜单轻松更新。

## 支持的语言

🇯🇵 日本語 | 🇺🇸 English | 🇨🇳 简体中文 | 🇫🇷 Français | 🇩🇪 Deutsch | 🇮🇩 Bahasa Indonesia | 🇮🇹 Italiano | 🇰🇷 한국어 | 🇧🇷 Português | 🇪🇸 Español | 🇹🇭 ภาษาไทย

## 运行环境

- Windows 10/11
- macOS 12+

## 许可证

MIT License

## 问题报告

Bug 和需求请通过 [Issues](https://github.com/1ulce/PTCGL-Tracker-Releases/issues) 提交。
