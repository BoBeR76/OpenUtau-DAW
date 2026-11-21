<div align="center">

# OpenUtau DAW

**OpenUtau прямо внутри Cubase — как VOCALOID, только бесплатно**

![Версия](https://img.shields.io/badge/версия-2.7.0-ff6fa0)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20x64-2b2b2b)
![Форматы](https://img.shields.io/badge/VST3%20%7C%20CLAP%20%7C%20ARA2-plugin-6f42c1)
![Языки](https://img.shields.io/badge/языков-14-3aa7e0)

[**⬇ Скачать установщик**](../../releases/latest) · [**📖 Инструкция**](docs/GUIDE.md) · [English](#english)

![OpenUtau в окне плагина Cubase](docs/cubase-pianoroll.png)

</div>

## Что это

OpenUtau DAW — плагин для Cubase, который открывает редактор пения [OpenUtau](https://github.com/stakira/OpenUtau) прямо в окне плагина. Вокал пишется и звучит внутри проекта Cubase, без экспорта WAV туда-обратно.

- 🎤 **OpenUtau в окне плагина.** Добавили Instrument-дорожку — и редактор уже там. Все окна OpenUtau (настройки, певцы, экспорт) открываются поверх него, а не отдельно.
- ⏱ **Темп и размер из Cubase.** OpenUtau сам подстраивается под проект. Для смены темпа по ходу песни есть ARA-мост **OpenUtau DAW Bridge**.
- ▶ **Общий транспорт.** Play, Stop и «в начало» в OpenUtau управляют Cubase.
- 🎹 **Ноты туда и обратно.** MIDI-партию из Cubase можно перетащить в OpenUtau, а часть из OpenUtau — на дорожку Cubase.
- 👥 **Несколько голосов.** Каждая дорожка «OpenUtau DAW» — свой голос; «+» в OpenUtau добавляет дорожку и в Cubase. Есть 8 отдельных выходов.
- 💾 **Всё сохраняется с проектом Cubase,** плюс 10 резервных копий вокала.
- 🌍 **14 языков:** русский, English, українська, 日本語, español, Deutsch, français, italiano, português, polski, čeština, Türkçe, 简体中文, 한국어.

| | |
|---|---|
| ![Плагин на дорожке Cubase](docs/cubase-plugin.png) | ![Настройки поверх окна](docs/settings-inside.png) |
| Плагин на Instrument-дорожке | Окна OpenUtau открываются поверх плагина |
| ![Инструкция внутри OpenUtau](docs/guide.png) | ![Установщик](docs/installer-welcome.png) |
| Встроенная инструкция | Установщик с выбором языка |

## Установка

1. Скачайте `OpenUtauDAW-Setup-2.7.0.exe` (или zip-архив с ним) из раздела [**Releases**](../../releases/latest).
2. **Закройте Cubase** — иначе файл плагина будет занят.
3. Запустите установщик, выберите язык, примите лицензионное соглашение.
4. Откройте Cubase и добавьте Instrument-дорожку с плагином **OpenUtau DAW**.

Если плагина нет в списке: *Studio → VST Plug-in Manager → пересканировать*.
Новая версия ставится поверх старой; настройки OpenUtau, голосовые банки и проекты не трогаются.

**Требования:** Windows 10/11 64-bit, Cubase 15 (проверено). Плагин в форматах VST3 и CLAP; мост темпа — ARA2.

## Быстрый старт

1. Выберите певца в заголовке дорожки OpenUtau. Голосовые банки (.zip) просто перетащите в окно OpenUtau.
2. Пишите ноты и текст в OpenUtau — звук идёт через дорожку Cubase.
3. Перед экспортом дождитесь **зелёной точки** на панели плагина.

**[📖 Полная инструкция](docs/GUIDE.md)** — с картинками, на 14 языках. Она же ставится вместе с программой и открывается в OpenUtau: *Справка → «Инструкция OpenUtau DAW»*.

## Проверка файлов

Контрольные суммы SHA-256 — в файле `SHA256SUMS.txt` у каждого релиза.

## Лицензия и благодарности

OpenUtau DAW бесплатен. Условия — в лицензионном соглашении, которое показывает установщик (и `LICENSE.txt` в папке программы).

Проект построен на чужой отличной работе:

- [OpenUtau](https://github.com/stakira/OpenUtau) — stakira и участники (MIT)
- [openutau-vst-bridge](https://github.com/KakaruHayate/openutau-vst-bridge) — KakaruHayate и участники (MPL-2.0), основа плагина
- VST 3 SDK — Steinberg (MIT), [CLAP](https://github.com/free-audio/clap) и [clap-wrapper](https://github.com/free-audio/clap-wrapper) (MIT), ARA SDK — Celemony (Apache 2.0)

Исходный код частей под MPL-2.0 устанавливается вместе с программой в папку `source`. Полные тексты лицензий — в `THIRD-PARTY-NOTICES.txt`.

OpenUtau DAW не связан со Steinberg, Yamaha, Celemony или авторами OpenUtau. Cubase и VST — товарные знаки Steinberg Media Technologies GmbH, ARA — Celemony Software GmbH. Голосовые банки распространяются их авторами на их условиях.

---

<a name="english"></a>

## English

**OpenUtau DAW** puts the [OpenUtau](https://github.com/stakira/OpenUtau) singing editor right inside a Cubase plug-in window — like VOCALOID, but free.

- OpenUtau opens inside the plug-in; all of its dialogs open over it, not as separate windows.
- Follows Cubase's tempo and time signature; the **OpenUtau DAW Bridge** ARA extension handles tempo changes.
- OpenUtau's Play / Stop / Home drive Cubase.
- Drag MIDI parts from Cubase into OpenUtau and parts from OpenUtau back to Cubase.
- One voice per "OpenUtau DAW" track, 8 extra outputs, saved with the Cubase project plus 10 vocal backups.
- 14 languages.

**Install:** download the installer from [Releases](../../releases/latest), close Cubase, run it, then add an Instrument track with **OpenUtau DAW**. Requires Windows 10/11 x64; tested with Cubase 15. **[📖 Full guide](docs/GUIDE-en.md)**.

Built on OpenUtau (MIT), openutau-vst-bridge (MPL-2.0), the VST 3 SDK, CLAP, clap-wrapper and the ARA SDK — see the license page of the installer and `THIRD-PARTY-NOTICES.txt`. Not affiliated with Steinberg, Yamaha, Celemony or the OpenUtau authors.

<div align="center"><sub>.Борислав(BoBeR 76)</sub></div>
