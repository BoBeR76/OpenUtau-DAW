<div align="center">

# OpenUtau DAW

**OpenUtau direkt in Cubase — wie VOCALOID, nur kostenlos**

![Version](https://img.shields.io/badge/version-2.7.1-ff6fa0)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20x64-2b2b2b)
![Formats](https://img.shields.io/badge/VST3%20%7C%20CLAP%20%7C%20ARA2-plugin-6f42c1)
![Languages](https://img.shields.io/badge/languages-14-3aa7e0)

[**⬇ Installer herunterladen**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) · [**📖 Anleitung**](docs/GUIDE-de.md)

🌍 [Русский](README.md) · [English](README.en.md) · [Українська](README.uk.md) · [日本語](README.ja.md) · [Español](README.es.md) · **Deutsch** · [Français](README.fr.md) · [Italiano](README.it.md) · [Português](README.pt.md) · [Polski](README.pl.md) · [Čeština](README.cs.md) · [Türkçe](README.tr.md) · [简体中文](README.zh.md) · [한국어](README.ko.md)

![OpenUtau im Cubase-Plug-in-Fenster](docs/cubase-pianoroll.png)

</div>

> [!NOTE]
> Diese Seite wurde maschinell übersetzt: Der Autor spricht kein Deutsch. Korrekturen sind in den [Issues](https://github.com/BoBeR76/OpenUtau-DAW/issues) willkommen.

## Was ist das

OpenUtau DAW ist ein Plug-in für Cubase, das den Gesangseditor [OpenUtau](https://github.com/stakira/OpenUtau) direkt im Plug-in-Fenster öffnet. Der Gesang wird im Cubase-Projekt geschrieben und abgespielt — ohne WAV-Dateien hin und her zu exportieren.

- 🎤 **OpenUtau im Plug-in-Fenster.** Instrumentenspur hinzufügen — der Editor ist schon da.
- ⏱ **Tempo und Taktart aus Cubase.** OpenUtau passt sich dem Projekt selbst an. Für Tempowechsel im Lied gibt es die ARA-Erweiterung **OpenUtau DAW Bridge**.
- ▶ **Gemeinsamer Transport.** Abspielen, Stopp und „zum Anfang“ in OpenUtau steuern Cubase.
- 🎹 **Noten in beide Richtungen.** Einen MIDI-Part aus Cubase in OpenUtau ziehen und einen Part aus OpenUtau auf eine Cubase-Spur. Auf einem MIDI-Keyboard gespielte Noten leuchten in OpenUtau auf.
- 👥 **Mehrere Stimmen.** Jede „OpenUtau DAW“-Spur ist eine eigene Stimme; „+“ in OpenUtau legt auch eine Cubase-Spur an. 8 separate Ausgänge.
- 💾 **Alles wird mit dem Cubase-Projekt gespeichert,** dazu 10 Sicherungen des Gesangs.
- 🌍 **14 Sprachen:** русский, English, українська, 日本語, español, Deutsch, français, italiano, português, polski, čeština, Türkçe, 简体中文, 한국어.

| | |
|---|---|
| ![Das Plug-in auf einer Instrumentenspur](docs/cubase-plugin.png) | ![OpenUtau-Dialoge öffnen sich über dem Plug-in](docs/settings-inside.png) |
| Das Plug-in auf einer Instrumentenspur | OpenUtau-Dialoge öffnen sich über dem Plug-in |
| ![Integrierte Anleitung](docs/guide.png) | ![Installer mit Sprachauswahl](docs/media/en/installer-welcome.png) |
| Integrierte Anleitung | Installer mit Sprachauswahl |

## Installation

1. Laden Sie `OpenUtauDAW-Setup-2.7.1.exe` (oder das ZIP damit) unter [**Releases**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) herunter.
2. **Schließen Sie Cubase** — sonst ist die Plug-in-Datei belegt.
3. Starten Sie den Installer, wählen Sie die Sprache, akzeptieren Sie den Lizenzvertrag.
4. Öffnen Sie Cubase und fügen Sie eine Instrumentenspur mit dem Plug-in **OpenUtau DAW** hinzu.

Wenn das Plug-in nicht in der Liste steht: *Studio → VST Plug-in Manager → neu scannen*.
Eine neue Version wird über die alte installiert; OpenUtau-Einstellungen, Stimmbanken und Projekte bleiben erhalten.

**Voraussetzungen:** Windows 10/11 64-bit, Cubase 15 (getestet). Plug-in als VST3 und CLAP; die Tempo-Brücke ist ARA2.

## Schnellstart

1. Wählen Sie im Kopf der OpenUtau-Spur einen Sänger. Stimmbanken (.zip) einfach in das OpenUtau-Fenster ziehen.
2. Schreiben Sie Noten und Text in OpenUtau — der Klang läuft über die Cubase-Spur.
3. Warten Sie vor dem Export auf den **grünen Punkt** in der Plug-in-Leiste.

**[📖 Vollständige Anleitung](docs/GUIDE-de.md)** — mit Bildern, in 14 Sprachen. Sie wird auch mit dem Programm installiert und öffnet sich in OpenUtau: *Hilfe → „OpenUtau DAW Anleitung“*.

## Dateien prüfen

SHA-256-Prüfsummen stehen in `SHA256SUMS.txt` bei jedem Release.

## Lizenz und Dank

OpenUtau DAW ist kostenlos. Die Bedingungen stehen im Lizenzvertrag, den der Installer zeigt (und in `LICENSE.txt` im Programmordner).

Das Projekt baut auf großartiger Arbeit anderer auf:

- [OpenUtau](https://github.com/stakira/OpenUtau) — stakira und Mitwirkende (MIT)
- [openutau-vst-bridge](https://github.com/KakaruHayate/openutau-vst-bridge) — KakaruHayate und Mitwirkende (MPL-2.0), Grundlage des Plug-ins
- VST 3 SDK — Steinberg (MIT), [CLAP](https://github.com/free-audio/clap), [clap-wrapper](https://github.com/free-audio/clap-wrapper) (MIT), ARA SDK — Celemony (Apache 2.0)

Der Quellcode der MPL-2.0-Teile wird mit dem Programm im Ordner `source` installiert. Vollständige Lizenztexte stehen in `THIRD-PARTY-NOTICES.txt`.

OpenUtau DAW steht in keiner Verbindung zu Steinberg, Yamaha, Celemony oder den Autoren von OpenUtau. Cubase und VST sind Marken der Steinberg Media Technologies GmbH, ARA der Celemony Software GmbH. Stimmbanken werden von ihren Autoren zu deren eigenen Bedingungen verbreitet.

<div align="center"><sub>.Борислав(BoBeR 76)</sub></div>
