<div align="center">

# OpenUtau DAW

**Cubase 안에서 바로 OpenUtau — VOCALOID처럼, 하지만 무료**

![Version](https://img.shields.io/badge/version-2.7.1-ff6fa0)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20x64-2b2b2b)
![Formats](https://img.shields.io/badge/VST3%20%7C%20CLAP%20%7C%20ARA2-plugin-6f42c1)
![Languages](https://img.shields.io/badge/languages-14-3aa7e0)

[**⬇ 설치 프로그램 내려받기**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) · [**📖 사용 설명서**](docs/GUIDE-ko.md)

🌍 [Русский](README.md) · [English](README.en.md) · [Українська](README.uk.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Português](README.pt.md) · [Polski](README.pl.md) · [Čeština](README.cs.md) · [Türkçe](README.tr.md) · [简体中文](README.zh.md) · **한국어**

![Cubase 플러그인 창 안의 OpenUtau](docs/cubase-pianoroll.png)

</div>

> [!NOTE]
> 이 페이지는 기계 번역으로 작성되었습니다. 작성자는 한국어를 하지 못합니다. 어색한 부분은 [Issues](https://github.com/BoBeR76/OpenUtau-DAW/issues)에서 알려 주세요.

## 소개

OpenUtau DAW는 노래 편집기 [OpenUtau](https://github.com/stakira/OpenUtau)를 플러그인 창 안에서 바로 여는 Cubase용 플러그인입니다. WAV 파일을 주고받으며 내보낼 필요 없이 Cubase 프로젝트 안에서 보컬을 만들고 재생합니다.

- 🎤 **플러그인 창 안의 OpenUtau.** Instrument 트랙을 추가하면 편집기가 이미 그 안에 있습니다.
- ⏱ **템포와 박자표는 Cubase에서.** OpenUtau가 프로젝트에 맞춰 스스로 조정됩니다. 곡 중간의 템포 변화에는 ARA 확장 **OpenUtau DAW Bridge**가 있습니다.
- ▶ **공유 트랜스포트.** OpenUtau의 재생, 정지, “처음으로”가 Cubase를 제어합니다.
- 🎹 **음표를 양방향으로.** Cubase의 MIDI 파트를 OpenUtau로, OpenUtau의 파트를 Cubase 트랙으로 끌어다 놓을 수 있습니다. MIDI 키보드로 연주한 음은 OpenUtau에서 켜집니다.
- 👥 **여러 목소리.** “OpenUtau DAW” 트랙마다 별도의 목소리이며, OpenUtau의 “+”는 Cubase에도 트랙을 추가합니다. 개별 출력 8개.
- 💾 **모든 것이 Cubase 프로젝트와 함께 저장되며,** 보컬 백업도 10개 남습니다.
- 🌍 **14개 언어:** русский, English, українська, 日本語, español, Deutsch, français, italiano, português, polski, čeština, Türkçe, 简体中文, 한국어.

| | |
|---|---|
| ![Instrument 트랙 위의 플러그인](docs/cubase-plugin.png) | ![OpenUtau 창은 플러그인 위에 열립니다](docs/settings-inside.png) |
| Instrument 트랙 위의 플러그인 | OpenUtau 창은 플러그인 위에 열립니다 |
| ![내장 사용 설명서](docs/guide.png) | ![언어를 고를 수 있는 설치 프로그램](docs/media/en/installer-welcome.png) |
| 내장 사용 설명서 | 언어를 고를 수 있는 설치 프로그램 |

## 설치

1. [**Releases**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest)에서 `OpenUtauDAW-Setup-2.7.1.exe`(또는 이를 담은 zip)를 내려받습니다.
2. **Cubase를 종료합니다** — 그렇지 않으면 플러그인 파일이 사용 중입니다.
3. 설치 프로그램을 실행하고 언어를 고른 뒤 사용권 계약에 동의합니다.
4. Cubase를 열고 **OpenUtau DAW** 플러그인을 넣은 Instrument 트랙을 추가합니다.

목록에 플러그인이 없으면: *Studio → VST Plug-in Manager → 다시 검색*.
새 버전은 이전 버전 위에 덮어서 설치됩니다. OpenUtau 설정, 음원, 프로젝트는 그대로 유지됩니다.

**요구 사항:** Windows 10/11 64비트, Cubase 15(테스트 완료). 플러그인 형식은 VST3와 CLAP, 템포 브리지는 ARA2입니다.

## 빠른 시작

1. OpenUtau 트랙 헤더에서 가수를 고릅니다. 음원(.zip)은 OpenUtau 창에 끌어다 놓기만 하면 됩니다.
2. OpenUtau에서 음표와 가사를 씁니다. 소리는 Cubase 트랙으로 나옵니다.
3. 내보내기 전에 플러그인 바의 **초록 점**을 기다리세요.

**[📖 전체 사용 설명서](docs/GUIDE-ko.md)** — 그림 포함, 14개 언어. 프로그램과 함께 설치되며 OpenUtau에서 열 수 있습니다: *도움말 → “OpenUtau DAW 사용 설명서”*.

## 파일 확인

SHA-256 체크섬은 각 릴리스의 `SHA256SUMS.txt`에 있습니다.

## 라이선스와 감사의 말

OpenUtau DAW는 무료입니다. 조건은 설치 프로그램이 보여 주는 사용권 계약(그리고 프로그램 폴더의 `LICENSE.txt`)에 있습니다.

이 프로젝트는 다른 분들의 훌륭한 작업 위에 만들어졌습니다:

- [OpenUtau](https://github.com/stakira/OpenUtau) — stakira와 기여자들 (MIT)
- [openutau-vst-bridge](https://github.com/KakaruHayate/openutau-vst-bridge) — KakaruHayate와 기여자들 (MPL-2.0), 플러그인의 기반
- VST 3 SDK — Steinberg (MIT), [CLAP](https://github.com/free-audio/clap), [clap-wrapper](https://github.com/free-audio/clap-wrapper) (MIT), ARA SDK — Celemony (Apache 2.0)

MPL-2.0 부분의 소스 코드는 프로그램과 함께 `source` 폴더에 설치됩니다. 라이선스 전문은 `THIRD-PARTY-NOTICES.txt`에 있습니다.

OpenUtau DAW는 Steinberg, Yamaha, Celemony 또는 OpenUtau 작성자와 관련이 없습니다. Cubase와 VST는 Steinberg Media Technologies GmbH의, ARA는 Celemony Software GmbH의 상표입니다. 음원은 각 작성자가 자체 조건으로 배포합니다.

<div align="center"><sub>.Борислав(BoBeR 76)</sub></div>
