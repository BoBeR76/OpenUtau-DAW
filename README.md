<div align="center">

# OpenUtau DAW

**OpenUtau right inside Cubase — like VOCALOID, but free**

![Version](https://img.shields.io/badge/version-2.7.1-ff6fa0)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20x64-2b2b2b)
![Formats](https://img.shields.io/badge/VST3%20%7C%20CLAP%20%7C%20ARA2-plugin-6f42c1)
![Languages](https://img.shields.io/badge/languages-14-3aa7e0)

[**⬇ Download the installer**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) · [**📖 Guide**](docs/GUIDE-en.md)

🌍 **English** · [Русский](docs/README.ru.md) · [Українська](docs/README.uk.md) · [日本語](docs/README.ja.md) · [Español](docs/README.es.md) · [Deutsch](docs/README.de.md) · [Français](docs/README.fr.md) · [Italiano](docs/README.it.md) · [Português](docs/README.pt.md) · [Polski](docs/README.pl.md) · [Čeština](docs/README.cs.md) · [Türkçe](docs/README.tr.md) · [简体中文](docs/README.zh.md) · [한국어](docs/README.ko.md)

![OpenUtau in the Cubase plug-in window](docs/cubase-pianoroll.png)

</div>

> [!NOTE]
> This page was translated with a machine translator: the author is a Russian speaker. Corrections are welcome in [Issues](https://github.com/BoBeR76/OpenUtau-DAW/issues).

## What is it

OpenUtau DAW is a plug-in for Cubase that opens the [OpenUtau](https://github.com/stakira/OpenUtau) singing editor right inside the plug-in window. The vocal is written and played inside the Cubase project, with no exporting WAV files back and forth.

- 🎤 **OpenUtau in the plug-in window.** Add an Instrument track — the editor is already there.
- ⏱ **Tempo and time signature from Cubase.** OpenUtau follows the project by itself. For tempo changes during a song there is the **OpenUtau DAW Bridge** ARA extension.
- ▶ **Shared transport.** Play, Stop and "go to start" in OpenUtau control Cubase.
- 🎹 **Notes both ways.** Drag a MIDI part from Cubase into OpenUtau, and a part from OpenUtau onto a Cubase track. Notes played on a MIDI keyboard light up in OpenUtau.
- 👥 **Several voices.** Each "OpenUtau DAW" track is its own voice; "+" in OpenUtau adds a track in Cubase too. 8 separate outputs.
- 💾 **Everything is saved with the Cubase project,** plus 10 vocal backups.
- 🌍 **14 languages:** русский, English, українська, 日本語, español, Deutsch, français, italiano, português, polski, čeština, Türkçe, 简体中文, 한국어.

| | |
|---|---|
| ![The plug-in on an Instrument track](docs/cubase-plugin.png) | ![OpenUtau dialogs open over the plug-in](docs/settings-inside.png) |
| The plug-in on an Instrument track | OpenUtau dialogs open over the plug-in |
| ![Built-in guide](docs/guide.png) | ![Installer with language choice](docs/media/en/installer-welcome.png) |
| Built-in guide | Installer with language choice |

## Installation

1. Download `OpenUtauDAW-Setup-2.7.1.exe` (or the zip with it) from [**Releases**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest).
2. **Close Cubase** — otherwise the plug-in file is in use.
3. Run the installer, choose the language, accept the license agreement.
4. Open Cubase and add an Instrument track with the **OpenUtau DAW** plug-in.

If the plug-in is not in the list: *Studio → VST Plug-in Manager → rescan*.
A new version installs over the old one; OpenUtau settings, voicebanks and projects are kept.

**Requirements:** Windows 10/11 64-bit, Cubase 15 (tested). VST3 and CLAP plug-in; the tempo bridge is ARA2.

## Quick start

1. Choose a singer in the header of the OpenUtau track. Just drag voicebanks (.zip) into the OpenUtau window.
2. Write notes and lyrics in OpenUtau — the sound goes through the Cubase track.
3. Before exporting, wait for the **green dot** in the plug-in bar.

**[📖 Full guide](docs/GUIDE-en.md)** — with pictures, in 14 languages. It is also installed with the program and opens in OpenUtau: *Help → "OpenUtau DAW Guide"*.

## Checking the files

SHA-256 checksums are in `SHA256SUMS.txt` attached to every release.

## License and credits

OpenUtau DAW is free. The terms are in the license agreement shown by the installer (and `LICENSE.txt` in the program folder).

The project is built on other people's great work:

- [OpenUtau](https://github.com/stakira/OpenUtau) — stakira and contributors (MIT)
- [openutau-vst-bridge](https://github.com/KakaruHayate/openutau-vst-bridge) — KakaruHayate and contributors (MPL-2.0), the base of the plug-in
- VST 3 SDK — Steinberg (MIT), [CLAP](https://github.com/free-audio/clap), [clap-wrapper](https://github.com/free-audio/clap-wrapper) (MIT), ARA SDK — Celemony (Apache 2.0)

The source code of the MPL-2.0 parts is installed with the program in the `source` folder. Full license texts are in `THIRD-PARTY-NOTICES.txt`.

OpenUtau DAW is not affiliated with Steinberg, Yamaha, Celemony or the OpenUtau authors. Cubase and VST are trademarks of Steinberg Media Technologies GmbH, ARA of Celemony Software GmbH. Voicebanks are distributed by their authors under their own terms.

<div align="center"><sub>.Борислав(BoBeR 76)</sub></div>
