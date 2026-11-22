<div align="center">

# OpenUtau DAW

**OpenUtau doğrudan Cubase içinde — VOCALOID gibi, ama ücretsiz**

![Version](https://img.shields.io/badge/version-2.7.2-ff6fa0)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20x64-2b2b2b)
![Formats](https://img.shields.io/badge/VST3%20%7C%20CLAP%20%7C%20ARA2-plugin-6f42c1)
![Languages](https://img.shields.io/badge/languages-14-3aa7e0)

[**⬇ Kurulum programını indir**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) · [**📖 Kılavuz**](GUIDE-tr.md)

🌍 [English](../README.md) · [Русский](README.ru.md) · [Українська](README.uk.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Português](README.pt.md) · [Polski](README.pl.md) · [Čeština](README.cs.md) · **Türkçe** · [简体中文](README.zh.md) · [한국어](README.ko.md)

![Cubase eklenti penceresinde OpenUtau](cubase-pianoroll.png)

</div>

> [!NOTE]
> Bu sayfa makine çevirisiyle hazırlandı: yazar Türkçe bilmiyor. Düzeltmeler [Issues](https://github.com/BoBeR76/OpenUtau-DAW/issues) bölümünde memnuniyetle karşılanır.

## Nedir

OpenUtau DAW, şarkı düzenleyicisi [OpenUtau](https://github.com/stakira/OpenUtau)'yu doğrudan eklenti penceresinde açan bir Cubase eklentisidir. Vokal, WAV dosyalarını ileri geri dışa aktarmadan Cubase projesinin içinde yazılır ve çalar.

- 🎤 **Eklenti penceresinde OpenUtau.** Bir Instrument parçası ekleyin — düzenleyici zaten orada.
- ⏱ **Tempo ve ölçü Cubase'den.** OpenUtau projeye kendiliğinden uyum sağlar. Şarkı içindeki tempo değişiklikleri için **OpenUtau DAW Bridge** ARA uzantısı vardır.
- ▶ **Ortak aktarım.** OpenUtau'daki Çal, Durdur ve “başa dön” Cubase'i kontrol eder.
- 🎹 **Notalar iki yönde.** Bir MIDI parçasını Cubase'den OpenUtau'ya, bir bölümü de OpenUtau'dan bir Cubase parçasına sürükleyin. MIDI klavyede çalınan notalar OpenUtau'da yanar.
- 👥 **Birden fazla ses.** Her “OpenUtau DAW” parçası ayrı bir sestir; OpenUtau'daki “+” Cubase'e de parça ekler. 8 ayrı çıkış.
- 💾 **Her şey Cubase projesiyle kaydedilir,** ayrıca vokalin 10 yedeği tutulur.
- 🌍 **14 dil:** русский, English, українська, 日本語, español, Deutsch, français, italiano, português, polski, čeština, Türkçe, 简体中文, 한국어.

| | |
|---|---|
| ![Instrument parçasında eklenti](cubase-plugin.png) | ![OpenUtau pencereleri eklentinin üzerinde açılır](settings-inside.png) |
| Instrument parçasında eklenti | OpenUtau pencereleri eklentinin üzerinde açılır |
| ![Yerleşik kılavuz](guide.png) | ![Dil seçimli kurulum programı](media/en/installer-welcome.png) |
| Yerleşik kılavuz | Dil seçimli kurulum programı |

## Kurulum

1. `OpenUtauDAW-Setup-2.7.2.exe` dosyasını (ya da onu içeren zip'i) [**Releases**](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest) sayfasından indirin.
2. **Cubase'i kapatın** — yoksa eklenti dosyası kullanımda olur.
3. Kurulum programını çalıştırın, dili seçin, lisans sözleşmesini kabul edin.
4. Cubase'i açın ve **OpenUtau DAW** eklentili bir Instrument parçası ekleyin.

Eklenti listede yoksa: *Studio → VST Plug-in Manager → yeniden tara*.
Yeni sürüm eskisinin üzerine kurulur; OpenUtau ayarları, ses bankaları ve projeler korunur.

**Gereksinimler:** Windows 10/11 64 bit, Cubase 15 (test edildi). VST3 ve CLAP biçiminde eklenti; tempo köprüsü ARA2.

## Hızlı başlangıç

1. OpenUtau parçasının başlığında bir şarkıcı seçin. Ses bankalarını (.zip) OpenUtau penceresine sürüklemeniz yeterli.
2. Notaları ve sözleri OpenUtau'da yazın — ses Cubase parçasından gelir.
3. Dışa aktarmadan önce eklenti çubuğundaki **yeşil noktayı** bekleyin.

**[📖 Tam kılavuz](GUIDE-tr.md)** — resimli, 14 dilde. Programla birlikte de kurulur ve OpenUtau'da açılır: *Yardım → “OpenUtau DAW Kılavuzu”*.

## Dosyaları doğrulama

SHA-256 sağlama toplamları her sürümdeki `SHA256SUMS.txt` dosyasındadır.

## Lisans ve teşekkürler

OpenUtau DAW ücretsizdir. Koşullar, kurulum programının gösterdiği lisans sözleşmesindedir (ve program klasöründeki `LICENSE.txt` dosyasında).

Proje, başkalarının harika çalışmaları üzerine kuruludur:

- [OpenUtau](https://github.com/stakira/OpenUtau) — stakira ve katkıda bulunanlar (MIT)
- [openutau-vst-bridge](https://github.com/KakaruHayate/openutau-vst-bridge) — KakaruHayate ve katkıda bulunanlar (MPL-2.0), eklentinin temeli
- VST 3 SDK — Steinberg (MIT), [CLAP](https://github.com/free-audio/clap), [clap-wrapper](https://github.com/free-audio/clap-wrapper) (MIT), ARA SDK — Celemony (Apache 2.0)

MPL-2.0 kapsamındaki bölümlerin kaynak kodu programla birlikte `source` klasörüne kurulur. Lisansların tam metinleri `THIRD-PARTY-NOTICES.txt` içindedir.

OpenUtau DAW; Steinberg, Yamaha, Celemony veya OpenUtau yazarlarıyla bağlantılı değildir. Cubase ve VST, Steinberg Media Technologies GmbH'nin; ARA, Celemony Software GmbH'nin ticari markalarıdır. Ses bankaları, yazarları tarafından kendi koşullarıyla dağıtılır.

<div align="center"><sub>.Борислав(BoBeR 76)</sub></div>
