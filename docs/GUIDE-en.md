# OpenUtau DAW guide

[← Home](../README.md) · [Русский](GUIDE.md) · [Other languages](GUIDE.md#другие-языки)

The same guide is installed with the program and opens in OpenUtau: *Help → "OpenUtau DAW Guide"*.

## 1. First start

1. **Close Cubase** and run `OpenUtauDAW-Setup-2.7.0.exe` from [Releases](https://github.com/BoBeR76/OpenUtau-DAW/releases/latest).
2. In Cubase, add an **Instrument track** with the **OpenUtau DAW** plug-in. OpenUtau opens right inside the plug-in window.
3. Choose a singer: click "Select Singer" in the header of the OpenUtau track.

> If the plug-in is not in the list: *Studio → VST Plug-in Manager → rescan*.

![The plug-in on a Cubase track](cubase-plugin.png)

## 2. The bar at the top of the plug-in window

| Item | Meaning |
|---|---|
| 🟢 / 🟡 / 🔴 dot | Green — sound is ready; yellow — rendering; red — something is wrong (the text next to it says what, e.g. "track 2 has no singer") |
| **MIDI sync** | Takes notes from Cubase while playing (see 3) |
| **Track:** | Which OpenUtau track this plug-in plays |
| **⚙** | Settings |

## 3. Notes from Cubase to OpenUtau

**Method 1 — drag and drop.** Drag a MIDI part from the Cubase project window onto the right track and bar in OpenUtau.

**Method 2 — sync while playing.**
1. Write notes in a MIDI part on the "OpenUtau DAW" track.
2. Turn on **MIDI sync** and play the section you need.
3. The notes appear in OpenUtau; lyrics you have already entered are kept.
4. When you are done, turn MIDI sync off.

> Writing notes in Cubase's own editor, like with VOCALOID, is planned but not possible yet.

![OpenUtau piano roll inside Cubase](cubase-pianoroll.png)

## 4. Notes from OpenUtau to Cubase

1. Hold a part in OpenUtau and drag it out over the edge of the plug-in window.
2. Drop it on an empty spot of the Cubase track you want — a MIDI part appears there.

> If Cubase creates a new track for it: *Edit → Preferences → MIDI → MIDI File* → turn on **"Import Dropped File as Single Part"**.

## 5. Tempo and transport

- OpenUtau takes the tempo and time signature from Cubase.
- Play, Stop and "go to start" in OpenUtau control Cubase.

**If the tempo changes during the song,** add the bridge to the project (once per project):

1. Create an audio track, put any audio event on it covering the whole song and mute it.
2. Select the event → *Audio → Extensions →* **"OpenUtau DAW Bridge"**.

## 6. Several voices

- A new "OpenUtau DAW" track in Cubase creates a new track in OpenUtau.
- **"+"** in OpenUtau adds a new track in Cubase too.

## 7. Keys

| Key | Action |
|---|---|
| `Space` | Play / Stop |
| `Home` | To the start |
| `Ctrl+S` | Save |

> If a key does nothing, click the OpenUtau window first.

## 8. Export

Before exporting, wait for the **green dot** in the plug-in window.

## 9. Saving and restoring

- The vocal is saved together with the Cubase project automatically.
- *File → "Restore from Backup"* — go back to one of the earlier versions of the vocal (10 are kept).

## 10. Singer picture on the Cubase track

1. *Help → "Singer Pictures for Cubase"* opens the folder with the pictures.
2. In Cubase, double-click the track picture → *Import* → choose the singer.

## 11. New voices

- Drag a voicebank archive (`.zip`) into the OpenUtau window.
- If your voices are in another folder: *Tools → Preferences → Paths →* **"Additional Singer Path"**.
- For DiffSinger, use the graphics card: *Tools → Preferences → Rendering →* **"Machine Learning Runner"**.

![Dialogs open over the plug-in window](settings-inside.png)
