# 📖 Guida di OpenUtau DAW

[← Home](../README.md)

🌍 [Русский](GUIDE.md) · [English](GUIDE-en.md) · [Українська](GUIDE-uk.md) · [日本語](GUIDE-ja.md) · [Español](GUIDE-es.md) · [Deutsch](GUIDE-de.md) · [Français](GUIDE-fr.md) · **Italiano** · [Português](GUIDE-pt.md) · [Polski](GUIDE-pl.md) · [Čeština](GUIDE-cs.md) · [Türkçe](GUIDE-tr.md) · [简体中文](GUIDE-zh.md) · [한국어](GUIDE-ko.md)

> [!NOTE]
> Questa guida è stata tradotta con un traduttore automatico: l’autore non parla italiano. Le correzioni sono benvenute nelle [Issues](https://github.com/BoBeR76/OpenUtau-DAW/issues).

OpenUtau DAW integra l'editor di canto OpenUtau direttamente nella finestra del plugin di Cubase. Qui trovi ciò che aggiunge il plugin; OpenUtau funziona come sempre. *(Le animazioni mostrano l'interfaccia in russo.)*

## Installazione

1. Scarica `OpenUtauDAW-Setup-2.7.1.exe` da [Releases](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest).
2. **Chiudi Cubase.** Se è aperto, l'installer chiede di chiuderlo e premere «Riprova».
3. Nella prima pagina scegli la lingua: sarà anche la lingua di OpenUtau e della barra del plugin.
4. Spunta la casella del contratto di licenza: senza, «Avanti» resta disattivato.

Vengono installati il plugin **OpenUtau DAW** (VST3 e CLAP), il ponte del tempo **OpenUtau DAW Bridge** (ARA2) e OpenUtau per DAW in `C:\OpenUtau-DAW`.

| | |
|---|---|
| ![Scelta della lingua](installer-welcome.png) | ![Licenza](installer-license.png) |

> **Aggiornamento.** La nuova versione si installa sopra la precedente. Impostazioni di OpenUtau, voicebank e progetti restano invariati.

## Primo avvio

1. In Cubase aggiungi una **traccia instrument** con il plugin **OpenUtau DAW**.
2. **OpenUtau si apre direttamente nella finestra del plugin**, con una traccia vuota già creata per questo plugin.
3. Scegli un cantante e inizia a scrivere.

![Aggiunta di una traccia OpenUtau DAW](media/01.gif)

> Se il plugin non è nell'elenco: *Studio → VST Plug-in Manager → ripeti la scansione*.

## La barra del plugin

La striscia sopra OpenUtau nella finestra del plugin:

![Barra del plugin](media/panel.png)

| Cosa vedi | Significato |
|---|---|
| 🟢 **connesso** | Tutto pronto, il suono corrisponde alle note |
| 🟡 **rendering 45%** | OpenUtau sta preparando il suono |
| 🔴 **⚠ …** | Qualcosa non va, e c'è scritto cosa, ad es. «la traccia 1 non ha un cantante: sceglilo in OpenUtau» |
| **110.00 BPM** | Il tempo di Cubase visto da OpenUtau |
| **Sinc. MIDI** | Prende le note da Cubase durante la riproduzione (vedi sotto) |
| **⚙** | Impostazioni del plugin |

![Nessun cantante: messaggio rosso; cantante scelto: punto verde](media/02.gif)

## Note tra Cubase e OpenUtau

### Trascinamento

- **Cubase → OpenUtau:** trascina una parte MIDI dalla finestra progetto di Cubase nella finestra di OpenUtau, sulla traccia e sulla battuta volute.
- **OpenUtau → Cubase:** tieni premuta una parte in OpenUtau, trascinala **oltre il bordo della finestra del plugin** e rilasciala in un **punto vuoto** di una traccia di Cubase.

![MIDI da Cubase a OpenUtau e ritorno](media/04.gif)

> Se Cubase mette la parte su una nuova traccia: *Modifica → Preferenze → MIDI → File MIDI* → attiva **«Importa file trascinato come parte singola»**.

### Sincronizzazione durante la riproduzione

1. Scrivi le note in una parte MIDI sulla traccia «OpenUtau DAW».
2. Attiva **«Sinc. MIDI»** nella barra del plugin e riproduci il passaggio.
3. Le note compaiono in OpenUtau. **Le sillabe già inserite restano**: puoi modificare la melodia in Cubase senza perdere il testo.
4. Alla fine disattiva «Sinc. MIDI».

### I tasti si illuminano

Le note premute si vedono nel piano roll di OpenUtau, come nell'editor di Cubase:

- suoni una **tastiera MIDI** o clicchi sui tasti dell'editor di Cubase: quei tasti **si illuminano in OpenUtau**;
- clicchi sui tasti del piano roll di OpenUtau: la nota suona **attraverso Cubase**, sull'uscita del plugin.

![Tasti premuti visibili in OpenUtau](media/keys.gif)

## Trasporto e tempo

![Trasporto di OpenUtau](media/transport.png)

- **Play, Stop e «all'inizio»** in OpenUtau (e `Spazio`, `Home`) controllano Cubase: suona tutto il brano, non solo la voce.
- OpenUtau prende **tempo e metro** da Cubase: cambi il BPM e OpenUtau si adegua.

## Ponte del tempo OpenUtau DAW Bridge

Se **il tempo cambia durante il brano**, aggiungi il ponte: così OpenUtau conosce l'intera mappa di tempo e battute. Una volta per progetto:

1. Crea una traccia audio e mettici un qualsiasi evento audio lungo quanto il brano. Silenzialo (Mute).
2. Seleziona l'evento → *Audio → Extensions →* **«OpenUtau DAW Bridge»**.

Il ponte funziona come con VOCALOID.

![OpenUtau DAW Bridge](media/10.gif)

## Più voci

**Ogni traccia «OpenUtau DAW» in Cubase è una voce a sé**, tutte nella stessa finestra di OpenUtau.

- Nuova traccia «OpenUtau DAW» in Cubase → nuova traccia vuota in OpenUtau.
- **«+»** in OpenUtau → nuova traccia **anche in Cubase**.

![«+» in OpenUtau crea una traccia in Cubase](media/11.gif)

- **Nome e colore** della traccia di Cubase passano in OpenUtau.

![Il colore della traccia di Cubase passa in OpenUtau](media/13.gif)

### ⚙ Se «+» non deve creare una traccia in Cubase

> [!TIP]
> **Ti servono più voci su una sola traccia di Cubase?** Clicca **⚙** a destra della barra del plugin e togli la spunta da **«Il pulsante «+» di OpenUtau aggiunge anche una traccia in Cubase»**.
>
> Così «+» aggiunge la voce solo in OpenUtau, e questa suona sull'uscita **«Track N»** dello stesso plugin (attivala in **F11**).

![Menu ⚙ del plugin](media/gear-menu.png)

## Salvataggio e backup

- **La voce viene salvata automaticamente con il progetto di Cubase.**
- Vengono conservate **le ultime 10 versioni**. Per ripristinarne una: *File →* **«Ripristina da backup»**.

## Piccoli comfort

- 🔁 **Riavvio automatico.** Se OpenUtau si blocca, il plugin lo riavvia. La voce non va persa.
- 🪟 **Finestre sopra il plugin.** Preferenze, cantanti e messaggi di OpenUtau si aprono sopra la finestra del plugin: Cubase non la nasconde.
- 🎚 **Uscite separate.** 8 uscite stereo «Track 1…8», una per traccia di OpenUtau (da attivare in F11).
- ⏳ **L'esportazione attende il rendering.** Se OpenUtau sta ancora preparando il suono, l'Audio Mixdown aspetta.
- ⚡ **Niente finestre superflue.** In Cubase OpenUtau salta la pagina iniziale e apre subito la voce del progetto.
- 🌍 **14 lingue**, e la barra del plugin usa la stessa lingua di OpenUtau.

## Non ancora possibile

- **Scrivere le note nell'editor di Cubase** (come con VOCALOID) e la sincronizzazione bidirezionale dal vivo. Si attende ARA 3: sarà fatto appena Celemony lo pubblicherà.
- I marker di Cubase non sono accessibili ai plugin, quindi OpenUtau non li mostra.

## Domande frequenti

**L'installer dice che Cubase è in esecuzione.** Chiudi Cubase del tutto (il processo resta qualche secondo dopo la finestra) e premi «Riprova».

**Nessun suono.** Guarda il punto nella barra del plugin: 🔴 — accanto è scritto il motivo; 🟡 — attendi la fine del rendering.

**Il plugin non è nell'elenco.** *Studio → VST Plug-in Manager → ripeti la scansione*.

**«OpenUtau è aperto in un'altra finestra del plugin».** Clicca sul messaggio: OpenUtau si sposterà in questa finestra.
