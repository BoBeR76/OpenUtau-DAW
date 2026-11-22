<div align="center">

# OpenUtau DAW

**OpenUtau direttamente dentro Cubase — come VOCALOID, ma gratis**

![Version](https://img.shields.io/badge/version-2.7.3-ff6fa0)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20x64-2b2b2b)
![Formats](https://img.shields.io/badge/VST3%20%7C%20CLAP%20%7C%20ARA2-plugin-6f42c1)
![Languages](https://img.shields.io/badge/languages-14-3aa7e0)

[**⬇ Scarica l'installer**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) · [**📖 Guida**](GUIDE-it.md)

🌍 [English](../README.md) · [Русский](README.ru.md) · [Українська](README.uk.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · **Italiano** · [Português](README.pt.md) · [Polski](README.pl.md) · [Čeština](README.cs.md) · [Türkçe](README.tr.md) · [简体中文](README.zh.md) · [한국어](README.ko.md)

![OpenUtau nella finestra del plugin di Cubase](cubase-pianoroll.png)

</div>

> [!NOTE]
> Questa pagina è stata tradotta con un traduttore automatico: l’autore non parla italiano. Le correzioni sono benvenute nelle [Issues](https://github.com/BoBeR76/OpenUtau-DAW/issues).

## Che cos'è

OpenUtau DAW è un plugin per Cubase che apre l'editor di canto [OpenUtau](https://github.com/stakira/OpenUtau) direttamente nella finestra del plugin. La voce si scrive e suona dentro il progetto di Cubase, senza esportare file WAV avanti e indietro.

- 🎤 **OpenUtau nella finestra del plugin.** Aggiungi una traccia instrument: l'editor è già lì.
- ⏱ **Tempo e metro da Cubase.** OpenUtau si adegua da solo al progetto. Per i cambi di tempo durante il brano c'è l'estensione ARA **OpenUtau DAW Bridge**.
- ▶ **Trasporto condiviso.** Play, Stop e «all'inizio» in OpenUtau controllano Cubase.
- 🎹 **Note in entrambe le direzioni.** Trascina una parte MIDI da Cubase in OpenUtau e una parte da OpenUtau su una traccia di Cubase. Le note suonate su una tastiera MIDI si illuminano in OpenUtau.
- 👥 **Più voci.** Ogni traccia «OpenUtau DAW» è una voce a sé; «+» in OpenUtau aggiunge una traccia anche in Cubase. 8 uscite separate.
- 💾 **Tutto viene salvato con il progetto di Cubase,** più 10 backup della voce.
- 🌍 **14 lingue:** русский, English, українська, 日本語, español, Deutsch, français, italiano, português, polski, čeština, Türkçe, 简体中文, 한국어.

| | |
|---|---|
| ![Il plugin su una traccia instrument](cubase-plugin.png) | ![Le finestre di OpenUtau si aprono sopra il plugin](settings-inside.png) |
| Il plugin su una traccia instrument | Le finestre di OpenUtau si aprono sopra il plugin |
| ![Guida integrata](guide.png) | ![Installer con scelta della lingua](media/en/installer-welcome.png) |
| Guida integrata | Installer con scelta della lingua |

## Installazione

1. Scarica `OpenUtauDAW-Setup-2.7.3.exe` (o lo zip che lo contiene) da [**Releases**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest).
2. **Chiudi Cubase**, altrimenti il file del plugin è in uso.
3. Avvia l'installer, scegli la lingua, accetta il contratto di licenza.
4. Apri Cubase e aggiungi una traccia instrument con il plugin **OpenUtau DAW**.

Se il plugin non è nell'elenco: *Studio → VST Plug-in Manager → ripeti la scansione*.
La nuova versione si installa sopra la precedente; impostazioni di OpenUtau, voicebank e progetti restano invariati.

**Requisiti:** Windows 10/11 a 64 bit, Cubase 15 (testato). Plugin nei formati VST3 e CLAP; il ponte del tempo è ARA2.

## Avvio rapido

1. Scegli un cantante nell'intestazione della traccia di OpenUtau. Trascina i voicebank (.zip) nella finestra di OpenUtau.
2. Scrivi note e testo in OpenUtau: il suono passa per la traccia di Cubase.
3. Prima di esportare, attendi il **punto verde** nella barra del plugin.

**[📖 Guida completa](GUIDE-it.md)**, con immagini, in 14 lingue. Viene anche installata con il programma e si apre in OpenUtau: *Aiuto → «Guida di OpenUtau DAW»*.

## Verifica dei file

I checksum SHA-256 sono in `SHA256SUMS.txt` di ogni release.

## Licenza e ringraziamenti

OpenUtau DAW è gratuito. Le condizioni sono nel contratto di licenza mostrato dall'installer (e in `LICENSE.txt` nella cartella del programma).

Il progetto si basa sull'ottimo lavoro di altre persone:

- [OpenUtau](https://github.com/stakira/OpenUtau) — stakira e collaboratori (MIT)
- [openutau-vst-bridge](https://github.com/KakaruHayate/openutau-vst-bridge) — KakaruHayate e collaboratori (MPL-2.0), la base del plugin
- VST 3 SDK — Steinberg (MIT), [CLAP](https://github.com/free-audio/clap), [clap-wrapper](https://github.com/free-audio/clap-wrapper) (MIT), ARA SDK — Celemony (Apache 2.0)

Il codice sorgente delle parti sotto MPL-2.0 viene installato con il programma nella cartella `source`. I testi completi delle licenze sono in `THIRD-PARTY-NOTICES.txt`.

OpenUtau DAW non è affiliato a Steinberg, Yamaha, Celemony né agli autori di OpenUtau. Cubase e VST sono marchi di Steinberg Media Technologies GmbH, ARA di Celemony Software GmbH. I voicebank sono distribuiti dai loro autori alle loro condizioni.

<div align="center"><sub>.Борислав(BoBeR 76)</sub></div>
