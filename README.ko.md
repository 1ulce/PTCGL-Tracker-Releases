[English](README.md) | [日本語](README.ja.md) | [简体中文](README.zh-CN.md) | [Français](README.fr.md) | [Deutsch](README.de.md) | [Bahasa Indonesia](README.id.md) | [Italiano](README.it.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Español](README.es.md) | [ภาษาไทย](README.th.md)

# PTCGL Tracker

포켓몬 카드 게임 라이브(PTCGL)의 대전 후 표시되는 배틀 로그를 자동으로 저장하는 도구입니다.

## 다운로드

[최신 버전 다운로드](https://github.com/1ulce/PTCGL-Tracker-Releases/releases/latest)

| OS | 파일 |
|---|---|
| Windows | `PTCGL Tracker.exe` |
| macOS | `PTCGL Tracker.app.zip` |

## 설치 방법

### Windows

1. `PTCGL Tracker.exe` 다운로드
2. 임의의 폴더에 배치하고 실행
3. 시스템 트레이에 아이콘이 표시되면 설치 완료

### macOS

1. `PTCGL Tracker.app.zip` 다운로드
2. 압축 해제 후 `PTCGL Tracker.app`을 응용 프로그램 폴더로 이동
3. 첫 실행 시 우클릭 → "열기"로 실행

## ⚠️ PTCGL 설정 (중요)

리플레이 분석이 올바르게 작동하도록 PTCGL에서 다음 설정을 구성하십시오.

![PTCGL 설정](ptcgl-settings.png)

### 1. 창 모드 활성화
`VIDEO OPTIONS` → **"WINDOWED" 체크**

트래커가 로그 파일에 접근하기 위해 필수입니다.

### 2. 언어를 영어로 설정
`LANGUAGE` → **"ENGLISH" 선택**

현재 영어 로그만 리플레이 분석에 대응하고 있습니다.

### 3. 카드 ID 표시
`BATTLE LOG SETTINGS` → **"HIDE CARD IDS FROM EXPORT" 체크 해제**

카드 ID가 없으면 로그에 카드 이미지가 표시되지 않습니다.

## 사용 방법

1. PTCGL Tracker 실행 (시스템 트레이에 상주)
2. PTCGL에서 배틀 종료
3. 결과 화면의 "BATTLE LOG" 버튼이 자동으로 클릭됨
4. 배틀 로그가 `~/PTCGLLogs/`에 자동 저장됨

## 클라우드 업로드
PTCGTools에 계정을 만들고 로그인하면 [PTCGL Replayer 웹사이트](https://replay.ptcgtools.com)에서 대전 로그와 덱을 관리할 수 있습니다.

## 자동 업데이트

새 버전이 출시되면 앱 실행 시 알림이 표시됩니다.
트레이 메뉴에서 간단히 업데이트할 수 있습니다.

## 지원 언어

🇯🇵 日本語 | 🇺🇸 English | 🇨🇳 简体中文 | 🇫🇷 Français | 🇩🇪 Deutsch | 🇮🇩 Bahasa Indonesia | 🇮🇹 Italiano | 🇰🇷 한국어 | 🇧🇷 Português | 🇪🇸 Español | 🇹🇭 ภาษาไทย

## 시스템 요구 사항

- Windows 10/11
- macOS 12+

## 라이선스

MIT License

## 문제 신고

버그 및 요청은 [Issues](https://github.com/1ulce/PTCGL-Tracker-Releases/issues)에서 부탁드립니다.
