<div align="center">

# OpenUtau DAW

**OpenUtau prosto w Cubase — jak VOCALOID, tylko za darmo**

![Version](https://img.shields.io/badge/version-2.7.1-ff6fa0)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20x64-2b2b2b)
![Formats](https://img.shields.io/badge/VST3%20%7C%20CLAP%20%7C%20ARA2-plugin-6f42c1)
![Languages](https://img.shields.io/badge/languages-14-3aa7e0)

[**⬇ Pobierz instalator**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) · [**📖 Instrukcja**](GUIDE-pl.md)

🌍 [Русский](../README.md) · [English](README.en.md) · [Українська](README.uk.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Português](README.pt.md) · **Polski** · [Čeština](README.cs.md) · [Türkçe](README.tr.md) · [简体中文](README.zh.md) · [한국어](README.ko.md)

![OpenUtau w oknie wtyczki Cubase](cubase-pianoroll.png)

</div>

> [!NOTE]
> Ta strona została przetłumaczona tłumaczem maszynowym: autor nie zna języka polskiego. Poprawki mile widziane w [Issues](https://github.com/BoBeR76/OpenUtau-DAW/issues).

## Co to jest

OpenUtau DAW to wtyczka do Cubase, która otwiera edytor śpiewu [OpenUtau](https://github.com/stakira/OpenUtau) bezpośrednio w oknie wtyczki. Wokal pisze się i brzmi wewnątrz projektu Cubase, bez eksportowania plików WAV tam i z powrotem.

- 🎤 **OpenUtau w oknie wtyczki.** Dodaj ścieżkę instrumentu — edytor już tam jest.
- ⏱ **Tempo i metrum z Cubase.** OpenUtau sam dopasowuje się do projektu. Do zmian tempa w trakcie utworu służy rozszerzenie ARA **OpenUtau DAW Bridge**.
- ▶ **Wspólny transport.** Odtwarzaj, Stop i „na początek” w OpenUtau sterują Cubase.
- 🎹 **Nuty w obie strony.** Przeciągnij partię MIDI z Cubase do OpenUtau, a partię z OpenUtau na ścieżkę Cubase. Nuty grane na klawiaturze MIDI podświetlają się w OpenUtau.
- 👥 **Kilka głosów.** Każda ścieżka „OpenUtau DAW” to osobny głos; „+” w OpenUtau dodaje ścieżkę także w Cubase. 8 osobnych wyjść.
- 💾 **Wszystko zapisuje się z projektem Cubase,** plus 10 kopii zapasowych wokalu.
- 🌍 **14 języków:** русский, English, українська, 日本語, español, Deutsch, français, italiano, português, polski, čeština, Türkçe, 简体中文, 한국어.

| | |
|---|---|
| ![Wtyczka na ścieżce instrumentu](cubase-plugin.png) | ![Okna OpenUtau otwierają się nad wtyczką](settings-inside.png) |
| Wtyczka na ścieżce instrumentu | Okna OpenUtau otwierają się nad wtyczką |
| ![Wbudowana instrukcja](guide.png) | ![Instalator z wyborem języka](media/en/installer-welcome.png) |
| Wbudowana instrukcja | Instalator z wyborem języka |

## Instalacja

1. Pobierz `OpenUtauDAW-Setup-2.7.1.exe` (lub archiwum zip z nim) z [**Releases**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest).
2. **Zamknij Cubase** — inaczej plik wtyczki będzie zajęty.
3. Uruchom instalator, wybierz język, zaakceptuj umowę licencyjną.
4. Otwórz Cubase i dodaj ścieżkę instrumentu z wtyczką **OpenUtau DAW**.

Jeśli wtyczki nie ma na liście: *Studio → VST Plug-in Manager → skanuj ponownie*.
Nowa wersja instaluje się na starej; ustawienia OpenUtau, banki głosów i projekty pozostają bez zmian.

**Wymagania:** Windows 10/11 64-bit, Cubase 15 (sprawdzone). Wtyczka w formatach VST3 i CLAP; most tempa — ARA2.

## Szybki start

1. Wybierz śpiewaka w nagłówku ścieżki OpenUtau. Banki głosów (.zip) po prostu przeciągnij do okna OpenUtau.
2. Pisz nuty i tekst w OpenUtau — dźwięk idzie przez ścieżkę Cubase.
3. Przed eksportem poczekaj na **zieloną kropkę** na pasku wtyczki.

**[📖 Pełna instrukcja](GUIDE-pl.md)** — z obrazkami, w 14 językach. Instaluje się też razem z programem i otwiera w OpenUtau: *Pomoc → „Instrukcja OpenUtau DAW”*.

## Sprawdzanie plików

Sumy kontrolne SHA-256 są w pliku `SHA256SUMS.txt` przy każdym wydaniu.

## Licencja i podziękowania

OpenUtau DAW jest darmowy. Warunki są w umowie licencyjnej wyświetlanej przez instalator (oraz w `LICENSE.txt` w folderze programu).

Projekt opiera się na świetnej pracy innych osób:

- [OpenUtau](https://github.com/stakira/OpenUtau) — stakira i współtwórcy (MIT)
- [openutau-vst-bridge](https://github.com/KakaruHayate/openutau-vst-bridge) — KakaruHayate i współtwórcy (MPL-2.0), podstawa wtyczki
- VST 3 SDK — Steinberg (MIT), [CLAP](https://github.com/free-audio/clap), [clap-wrapper](https://github.com/free-audio/clap-wrapper) (MIT), ARA SDK — Celemony (Apache 2.0)

Kod źródłowy części na licencji MPL-2.0 instaluje się z programem w folderze `source`. Pełne teksty licencji są w `THIRD-PARTY-NOTICES.txt`.

OpenUtau DAW nie jest powiązany ze Steinbergiem, Yamahą, Celemony ani autorami OpenUtau. Cubase i VST to znaki towarowe Steinberg Media Technologies GmbH, ARA — Celemony Software GmbH. Banki głosów są rozpowszechniane przez ich autorów na ich własnych warunkach.

<div align="center"><sub>.Борислав(BoBeR 76)</sub></div>
