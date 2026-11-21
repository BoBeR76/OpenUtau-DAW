<div align="center">

# OpenUtau DAW

**在 Cubase 中直接使用 OpenUtau——像 VOCALOID 一样，而且免费**

![Version](https://img.shields.io/badge/version-2.7.1-ff6fa0)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20x64-2b2b2b)
![Formats](https://img.shields.io/badge/VST3%20%7C%20CLAP%20%7C%20ARA2-plugin-6f42c1)
![Languages](https://img.shields.io/badge/languages-14-3aa7e0)

[**⬇ 下载安装程序**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) · [**📖 使用说明**](docs/GUIDE-zh.md)

🌍 [Русский](README.md) · [English](README.en.md) · [Українська](README.uk.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Português](README.pt.md) · [Polski](README.pl.md) · [Čeština](README.cs.md) · [Türkçe](README.tr.md) · **简体中文** · [한국어](README.ko.md)

![Cubase 插件窗口中的 OpenUtau](docs/cubase-pianoroll.png)

</div>

> [!NOTE]
> 本页由机器翻译完成：作者不懂中文。如有不通顺之处，欢迎在 [Issues](https://github.com/BoBeR76/OpenUtau-DAW/issues) 中指正。

## 这是什么

OpenUtau DAW 是一款 Cubase 插件，可在插件窗口中直接打开歌声编辑器 [OpenUtau](https://github.com/stakira/OpenUtau)。人声在 Cubase 工程内编写和播放，无需来回导出 WAV 文件。

- 🎤 **插件窗口中的 OpenUtau。** 添加一条 Instrument 音轨，编辑器就已经在那里了。
- ⏱ **速度和拍号来自 Cubase。** OpenUtau 会自动适应工程。歌曲中途变速时，可使用 ARA 扩展 **OpenUtau DAW Bridge**。
- ▶ **共享走带。** OpenUtau 中的播放、停止和“回到开头”会控制 Cubase。
- 🎹 **音符双向传递。** 可把 Cubase 的 MIDI 片段拖进 OpenUtau，也可把 OpenUtau 的片段拖到 Cubase 音轨上。在 MIDI 键盘上弹奏的音符会在 OpenUtau 中亮起。
- 👥 **多个声部。** 每条 “OpenUtau DAW” 音轨都是独立的声部；OpenUtau 中的“+”也会在 Cubase 中添加音轨。共有 8 个独立输出。
- 💾 **一切都随 Cubase 工程保存，** 另有 10 份人声备份。
- 🌍 **14 种语言：** русский, English, українська, 日本語, español, Deutsch, français, italiano, português, polski, čeština, Türkçe, 简体中文, 한국어.

| | |
|---|---|
| ![Instrument 音轨上的插件](docs/cubase-plugin.png) | ![OpenUtau 的窗口在插件之上打开](docs/settings-inside.png) |
| Instrument 音轨上的插件 | OpenUtau 的窗口在插件之上打开 |
| ![内置使用说明](docs/guide.png) | ![可选择语言的安装程序](docs/media/en/installer-welcome.png) |
| 内置使用说明 | 可选择语言的安装程序 |

## 安装

1. 从 [**Releases**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) 下载 `OpenUtauDAW-Setup-2.7.1.exe`（或包含它的 zip）。
2. **关闭 Cubase**——否则插件文件会被占用。
3. 运行安装程序，选择语言，接受许可协议。
4. 打开 Cubase，添加一条挂载 **OpenUtau DAW** 插件的 Instrument 音轨。

如果列表中没有该插件：*Studio → VST Plug-in Manager → 重新扫描*。
新版本直接覆盖安装在旧版本上；OpenUtau 的设置、声库和工程都会保留。

**系统要求：** Windows 10/11 64 位，Cubase 15（已测试）。插件格式为 VST3 和 CLAP；速度桥为 ARA2。

## 快速上手

1. 在 OpenUtau 音轨的标题处选择歌手。把声库（.zip）直接拖进 OpenUtau 窗口即可。
2. 在 OpenUtau 中写音符和歌词——声音通过 Cubase 音轨输出。
3. 导出前，请等待插件栏上出现**绿色圆点**。

**[📖 完整使用说明](docs/GUIDE-zh.md)**——带图片，共 14 种语言。它也会随程序一起安装，并可在 OpenUtau 中打开：*帮助 → “OpenUtau DAW 使用说明”*。

## 校验文件

每个版本附带的 `SHA256SUMS.txt` 中有 SHA-256 校验和。

## 许可与致谢

OpenUtau DAW 免费。条款见安装程序显示的许可协议（以及程序文件夹中的 `LICENSE.txt`）。

本项目建立在他人的出色工作之上：

- [OpenUtau](https://github.com/stakira/OpenUtau) — stakira 及贡献者 (MIT)
- [openutau-vst-bridge](https://github.com/KakaruHayate/openutau-vst-bridge) — KakaruHayate 及贡献者 (MPL-2.0), 插件的基础
- VST 3 SDK — Steinberg (MIT), [CLAP](https://github.com/free-audio/clap), [clap-wrapper](https://github.com/free-audio/clap-wrapper) (MIT), ARA SDK — Celemony (Apache 2.0)

MPL-2.0 部分的源代码会随程序安装到 `source` 文件夹。许可证全文见 `THIRD-PARTY-NOTICES.txt`。

OpenUtau DAW 与 Steinberg、Yamaha、Celemony 及 OpenUtau 的作者均无关联。Cubase 和 VST 是 Steinberg Media Technologies GmbH 的商标，ARA 是 Celemony Software GmbH 的商标。声库由其作者按各自的条款发布。

<div align="center"><sub>.Борислав(BoBeR 76)</sub></div>
