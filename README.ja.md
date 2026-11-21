<div align="center">

# OpenUtau DAW

**OpenUtau を Cubase の中で — VOCALOID のように、しかも無料**

![Version](https://img.shields.io/badge/version-2.7.1-ff6fa0)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20x64-2b2b2b)
![Formats](https://img.shields.io/badge/VST3%20%7C%20CLAP%20%7C%20ARA2-plugin-6f42c1)
![Languages](https://img.shields.io/badge/languages-14-3aa7e0)

[**⬇ インストーラーをダウンロード**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) · [**📖 ガイド**](docs/GUIDE-ja.md)

🌍 [Русский](README.md) · [English](README.en.md) · [Українська](README.uk.md) · **日本語** · [Español](README.es.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Português](README.pt.md) · [Polski](README.pl.md) · [Čeština](README.cs.md) · [Türkçe](README.tr.md) · [简体中文](README.zh.md) · [한국어](README.ko.md)

![Cubase のプラグインウィンドウ内の OpenUtau](docs/cubase-pianoroll.png)

</div>

> [!NOTE]
> このページは機械翻訳で作成しました。作者は日本語を話せません。不自然な箇所があれば [Issues](https://github.com/BoBeR76/OpenUtau-DAW/issues) でお知らせください。

## 概要

OpenUtau DAW は、歌声エディター [OpenUtau](https://github.com/stakira/OpenUtau) をプラグインウィンドウの中で直接開く Cubase 用プラグインです。WAV を書き出してやり取りすることなく、Cubase のプロジェクト内でボーカルを作り、鳴らせます。

- 🎤 **プラグインウィンドウの中に OpenUtau。** Instrument トラックを追加するだけで、エディターがそこにあります。
- ⏱ **テンポと拍子は Cubase から。** OpenUtau が自動でプロジェクトに合わせます。曲の途中のテンポ変更には ARA 拡張 **OpenUtau DAW Bridge** があります。
- ▶ **共通のトランスポート。** OpenUtau の再生・停止・先頭へ戻るで Cubase を操作できます。
- 🎹 **ノートを双方向に。** Cubase の MIDI パートを OpenUtau へ、OpenUtau のパートを Cubase のトラックへドラッグできます。MIDI キーボードで弾いた音は OpenUtau の鍵盤で光ります。
- 👥 **複数の声。** 「OpenUtau DAW」トラックごとに別の声。OpenUtau の「+」で Cubase にもトラックが追加されます。個別出力は 8 つ。
- 💾 **すべて Cubase のプロジェクトと一緒に保存**され、ボーカルのバックアップも 10 個残ります。
- 🌍 **14 言語:** русский, English, українська, 日本語, español, Deutsch, français, italiano, português, polski, čeština, Türkçe, 简体中文, 한국어.

| | |
|---|---|
| ![Instrument トラック上のプラグイン](docs/cubase-plugin.png) | ![OpenUtau のウィンドウはプラグインの上に開きます](docs/settings-inside.png) |
| Instrument トラック上のプラグイン | OpenUtau のウィンドウはプラグインの上に開きます |
| ![内蔵ガイド](docs/guide.png) | ![言語を選べるインストーラー](docs/media/en/installer-welcome.png) |
| 内蔵ガイド | 言語を選べるインストーラー |

## インストール

1. [**Releases**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) から `OpenUtauDAW-Setup-2.7.1.exe`（またはそれを含む zip）をダウンロードします。
2. **Cubase を終了します。** 起動中だとプラグインのファイルが使用中になります。
3. インストーラーを実行し、言語を選んで使用許諾契約に同意します。
4. Cubase を開き、**OpenUtau DAW** プラグインを挿した Instrument トラックを追加します。

プラグインが一覧にない場合: *Studio → VST Plug-in Manager → 再スキャン*。
新しいバージョンは古いものに上書きでインストールされます。OpenUtau の設定、音源、プロジェクトはそのまま残ります。

**動作環境:** Windows 10/11 64 ビット、Cubase 15（動作確認済み）。プラグイン形式は VST3 と CLAP、テンポブリッジは ARA2。

## クイックスタート

1. OpenUtau のトラックのヘッダーで歌手を選びます。音源（.zip）は OpenUtau のウィンドウにドラッグするだけです。
2. OpenUtau でノートと歌詞を書きます。音は Cubase のトラックから出ます。
3. 書き出しの前に、プラグインバーの**緑の丸**を待ちます。

**[📖 詳しいガイド](docs/GUIDE-ja.md)** — 画像付き、14 言語。プログラムと一緒にもインストールされ、OpenUtau で開けます: *ヘルプ →「OpenUtau DAW ガイド」*。

## ファイルの確認

SHA-256 チェックサムは各リリースの `SHA256SUMS.txt` にあります。

## ライセンスと謝辞

OpenUtau DAW は無料です。条件はインストーラーが表示する使用許諾契約（およびプログラムフォルダーの `LICENSE.txt`）にあります。

このプロジェクトは、他の方々のすばらしい成果の上に成り立っています:

- [OpenUtau](https://github.com/stakira/OpenUtau) — stakira とコントリビューター (MIT)
- [openutau-vst-bridge](https://github.com/KakaruHayate/openutau-vst-bridge) — KakaruHayate とコントリビューター (MPL-2.0), プラグインの土台
- VST 3 SDK — Steinberg (MIT), [CLAP](https://github.com/free-audio/clap), [clap-wrapper](https://github.com/free-audio/clap-wrapper) (MIT), ARA SDK — Celemony (Apache 2.0)

MPL-2.0 の部分のソースコードは、プログラムと一緒に `source` フォルダーにインストールされます。ライセンスの全文は `THIRD-PARTY-NOTICES.txt` にあります。

OpenUtau DAW は Steinberg、Yamaha、Celemony、OpenUtau の作者とは関係ありません。Cubase と VST は Steinberg Media Technologies GmbH の、ARA は Celemony Software GmbH の商標です。音源はそれぞれの作者が独自の条件で配布しています。

<div align="center"><sub>.Борислав(BoBeR 76)</sub></div>
