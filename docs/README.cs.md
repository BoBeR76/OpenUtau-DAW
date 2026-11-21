<div align="center">

# OpenUtau DAW

**OpenUtau přímo v Cubase — jako VOCALOID, jen zdarma**

![Version](https://img.shields.io/badge/version-2.7.1-ff6fa0)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20x64-2b2b2b)
![Formats](https://img.shields.io/badge/VST3%20%7C%20CLAP%20%7C%20ARA2-plugin-6f42c1)
![Languages](https://img.shields.io/badge/languages-14-3aa7e0)

[**⬇ Stáhnout instalátor**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) · [**📖 Návod**](GUIDE-cs.md)

🌍 [Русский](../README.md) · [English](README.en.md) · [Українська](README.uk.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Português](README.pt.md) · [Polski](README.pl.md) · **Čeština** · [Türkçe](README.tr.md) · [简体中文](README.zh.md) · [한국어](README.ko.md)

![OpenUtau v okně pluginu Cubase](cubase-pianoroll.png)

</div>

> [!NOTE]
> Tato stránka byla přeložena strojovým překladačem: autor neumí česky. Opravy jsou vítány v [Issues](https://github.com/BoBeR76/OpenUtau-DAW/issues).

## Co to je

OpenUtau DAW je plugin pro Cubase, který otevírá editor zpěvu [OpenUtau](https://github.com/stakira/OpenUtau) přímo v okně pluginu. Zpěv se píše a zní uvnitř projektu Cubase, bez exportu WAV souborů tam a zpět.

- 🎤 **OpenUtau v okně pluginu.** Přidejte stopu nástroje — editor už tam je.
- ⏱ **Tempo a takt z Cubase.** OpenUtau se projektu přizpůsobí sám. Pro změny tempa během písně je tu ARA rozšíření **OpenUtau DAW Bridge**.
- ▶ **Společný transport.** Přehrát, Stop a „na začátek“ v OpenUtau ovládají Cubase.
- 🎹 **Noty oběma směry.** Přetáhněte MIDI part z Cubase do OpenUtau a part z OpenUtau na stopu Cubase. Noty zahrané na MIDI klávesnici se rozsvítí v OpenUtau.
- 👥 **Více hlasů.** Každá stopa „OpenUtau DAW“ je samostatný hlas; „+“ v OpenUtau přidá stopu i v Cubase. 8 samostatných výstupů.
- 💾 **Vše se ukládá s projektem Cubase,** navíc 10 záloh zpěvu.
- 🌍 **14 jazyků:** русский, English, українська, 日本語, español, Deutsch, français, italiano, português, polski, čeština, Türkçe, 简体中文, 한국어.

| | |
|---|---|
| ![Plugin na stopě nástroje](cubase-plugin.png) | ![Okna OpenUtau se otevírají nad pluginem](settings-inside.png) |
| Plugin na stopě nástroje | Okna OpenUtau se otevírají nad pluginem |
| ![Vestavěný návod](guide.png) | ![Instalátor s volbou jazyka](media/en/installer-welcome.png) |
| Vestavěný návod | Instalátor s volbou jazyka |

## Instalace

1. Stáhněte `OpenUtauDAW-Setup-2.7.1.exe` (nebo zip s ním) z [**Releases**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest).
2. **Zavřete Cubase** — jinak bude soubor pluginu používán.
3. Spusťte instalátor, zvolte jazyk, přijměte licenční smlouvu.
4. Otevřete Cubase a přidejte stopu nástroje s pluginem **OpenUtau DAW**.

Pokud plugin v seznamu není: *Studio → VST Plug-in Manager → znovu prohledat*.
Nová verze se instaluje přes starou; nastavení OpenUtau, hlasové banky a projekty zůstanou zachovány.

**Požadavky:** Windows 10/11 64-bit, Cubase 15 (vyzkoušeno). Plugin ve formátech VST3 a CLAP; most tempa je ARA2.

## Rychlý start

1. Vyberte zpěváka v záhlaví stopy OpenUtau. Hlasové banky (.zip) stačí přetáhnout do okna OpenUtau.
2. Pište noty a text v OpenUtau — zvuk jde přes stopu Cubase.
3. Před exportem počkejte na **zelenou tečku** na liště pluginu.

**[📖 Úplný návod](GUIDE-cs.md)** — s obrázky, ve 14 jazycích. Instaluje se i s programem a otevírá se v OpenUtau: *Help → „Návod k OpenUtau DAW“*.

## Kontrola souborů

Kontrolní součty SHA-256 jsou v souboru `SHA256SUMS.txt` u každého vydání.

## Licence a poděkování

OpenUtau DAW je zdarma. Podmínky jsou v licenční smlouvě, kterou zobrazí instalátor (a v `LICENSE.txt` ve složce programu).

Projekt stojí na skvělé práci jiných lidí:

- [OpenUtau](https://github.com/stakira/OpenUtau) — stakira a přispěvatelé (MIT)
- [openutau-vst-bridge](https://github.com/KakaruHayate/openutau-vst-bridge) — KakaruHayate a přispěvatelé (MPL-2.0), základ pluginu
- VST 3 SDK — Steinberg (MIT), [CLAP](https://github.com/free-audio/clap), [clap-wrapper](https://github.com/free-audio/clap-wrapper) (MIT), ARA SDK — Celemony (Apache 2.0)

Zdrojový kód částí pod MPL-2.0 se instaluje s programem do složky `source`. Úplné texty licencí jsou v `THIRD-PARTY-NOTICES.txt`.

OpenUtau DAW není spojen se společnostmi Steinberg, Yamaha, Celemony ani s autory OpenUtau. Cubase a VST jsou ochranné známky Steinberg Media Technologies GmbH, ARA Celemony Software GmbH. Hlasové banky šíří jejich autoři za vlastních podmínek.

<div align="center"><sub>.Борислав(BoBeR 76)</sub></div>
