<div align="center">

# OpenUtau DAW

**OpenUtau directement dans Cubase — comme VOCALOID, mais gratuit**

![Version](https://img.shields.io/badge/version-2.7.2-ff6fa0)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20x64-2b2b2b)
![Formats](https://img.shields.io/badge/VST3%20%7C%20CLAP%20%7C%20ARA2-plugin-6f42c1)
![Languages](https://img.shields.io/badge/languages-14-3aa7e0)

[**⬇ Télécharger l'installateur**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) · [**📖 Guide**](GUIDE-fr.md)

🌍 [English](../README.md) · [Русский](README.ru.md) · [Українська](README.uk.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Deutsch](README.de.md) · **Français** · [Italiano](README.it.md) · [Português](README.pt.md) · [Polski](README.pl.md) · [Čeština](README.cs.md) · [Türkçe](README.tr.md) · [简体中文](README.zh.md) · [한국어](README.ko.md)

![OpenUtau dans la fenêtre du plugin Cubase](cubase-pianoroll.png)

</div>

> [!NOTE]
> Cette page a été traduite avec un traducteur automatique : l’auteur ne parle pas français. Les corrections sont les bienvenues dans les [Issues](https://github.com/BoBeR76/OpenUtau-DAW/issues).

## Qu'est-ce que c'est

OpenUtau DAW est un plugin pour Cubase qui ouvre l'éditeur de chant [OpenUtau](https://github.com/stakira/OpenUtau) directement dans la fenêtre du plugin. La voix s'écrit et sonne dans le projet Cubase, sans exporter de fichiers WAV dans un sens puis dans l'autre.

- 🎤 **OpenUtau dans la fenêtre du plugin.** Ajoutez une piste d'instrument : l'éditeur est déjà là.
- ⏱ **Tempo et mesure depuis Cubase.** OpenUtau s'adapte tout seul au projet. Pour les changements de tempo au cours d'une chanson, il y a l'extension ARA **OpenUtau DAW Bridge**.
- ▶ **Transport partagé.** Lecture, Stop et « retour au début » dans OpenUtau pilotent Cubase.
- 🎹 **Notes dans les deux sens.** Glissez un conteneur MIDI de Cubase vers OpenUtau, et une partie d'OpenUtau vers une piste Cubase. Les notes jouées sur un clavier MIDI s'allument dans OpenUtau.
- 👥 **Plusieurs voix.** Chaque piste « OpenUtau DAW » est une voix à part ; « + » dans OpenUtau ajoute aussi une piste dans Cubase. 8 sorties séparées.
- 💾 **Tout est enregistré avec le projet Cubase,** plus 10 sauvegardes de la voix.
- 🌍 **14 langues :** русский, English, українська, 日本語, español, Deutsch, français, italiano, português, polski, čeština, Türkçe, 简体中文, 한국어.

| | |
|---|---|
| ![Le plugin sur une piste d'instrument](cubase-plugin.png) | ![Les fenêtres d'OpenUtau s'ouvrent au-dessus du plugin](settings-inside.png) |
| Le plugin sur une piste d'instrument | Les fenêtres d'OpenUtau s'ouvrent au-dessus du plugin |
| ![Guide intégré](guide.png) | ![Installateur avec choix de la langue](media/en/installer-welcome.png) |
| Guide intégré | Installateur avec choix de la langue |

## Installation

1. Téléchargez `OpenUtauDAW-Setup-2.7.2.exe` (ou le zip qui le contient) depuis [**Releases**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest).
2. **Fermez Cubase**, sinon le fichier du plugin est utilisé.
3. Lancez l'installateur, choisissez la langue, acceptez le contrat de licence.
4. Ouvrez Cubase et ajoutez une piste d'instrument avec le plugin **OpenUtau DAW**.

Si le plugin n'est pas dans la liste : *Studio → VST Plug-in Manager → relancer l'analyse*.
La nouvelle version s'installe par-dessus l'ancienne ; les réglages d'OpenUtau, les banques de voix et les projets sont conservés.

**Configuration requise :** Windows 10/11 64 bits, Cubase 15 (testé). Plugin aux formats VST3 et CLAP ; le pont de tempo est ARA2.

## Démarrage rapide

1. Choisissez un chanteur dans l'en-tête de la piste OpenUtau. Glissez simplement les banques de voix (.zip) dans la fenêtre d'OpenUtau.
2. Écrivez les notes et les paroles dans OpenUtau : le son passe par la piste Cubase.
3. Avant d'exporter, attendez le **point vert** dans la barre du plugin.

**[📖 Guide complet](GUIDE-fr.md)** — avec images, en 14 langues. Il est aussi installé avec le programme et s'ouvre dans OpenUtau : *Aide → « Guide d'OpenUtau DAW »*.

## Vérifier les fichiers

Les sommes SHA-256 se trouvent dans `SHA256SUMS.txt` de chaque version.

## Licence et remerciements

OpenUtau DAW est gratuit. Les conditions figurent dans le contrat de licence affiché par l'installateur (et dans `LICENSE.txt` dans le dossier du programme).

Le projet repose sur l'excellent travail d'autres personnes :

- [OpenUtau](https://github.com/stakira/OpenUtau) — stakira et contributeurs (MIT)
- [openutau-vst-bridge](https://github.com/KakaruHayate/openutau-vst-bridge) — KakaruHayate et contributeurs (MPL-2.0), la base du plugin
- VST 3 SDK — Steinberg (MIT), [CLAP](https://github.com/free-audio/clap), [clap-wrapper](https://github.com/free-audio/clap-wrapper) (MIT), ARA SDK — Celemony (Apache 2.0)

Le code source des parties sous MPL-2.0 est installé avec le programme dans le dossier `source`. Les textes complets des licences sont dans `THIRD-PARTY-NOTICES.txt`.

OpenUtau DAW n'est pas affilié à Steinberg, Yamaha, Celemony ni aux auteurs d'OpenUtau. Cubase et VST sont des marques de Steinberg Media Technologies GmbH, ARA de Celemony Software GmbH. Les banques de voix sont distribuées par leurs auteurs selon leurs propres conditions.

<div align="center"><sub>.Борислав(BoBeR 76)</sub></div>
