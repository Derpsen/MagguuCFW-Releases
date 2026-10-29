# MagguuCFW – Releases

Fertige Pakete (Zip-Dateien) für die Nintendo Switch. Hier liegt **nur das Paket**, kein Quellcode und keine Schlüssel.

- Download: Reiter **Releases**. Seit `0.1.0-rc7` gibt es **ein** Zip: `MagguuCFW-<Version>.zip` (alles, mit MagguuOC). Die Zips `full-MagguuOC` und `minimal` gibt es nicht mehr.
- Entpacke das Zip in die **Wurzel** der SD-Karte (so, dass `atmosphere`, `bootloader`, `switch` direkt auf der SD liegen).
- **Update von älteren Versionen:** Wer `full` hat (z. B. rc16, rc15, rc14, rc13, rc12, rc11, rc10, rc9, rc8, rc7 oder rc6 `full`), bekommt rc17 ganz normal per Update in Magguu Tools.
- **Einmaliger Schritt für alte `full-MagguuOC`- und `minimal`-Installationen (rc4 bis rc6):** Die alte Magguu Tools lehnt das neue Paket ab und ändert dabei nichts. Kopiere **einmal** `switch/magguu-tools/magguu-tools.nro` aus dem aktuellen Zip (rc17) an dieselbe Stelle auf der SD-Karte (oder entpacke das ganze Zip in die Wurzel), öffne Magguu Tools und tippe auf „Aktualisieren“. Danach laufen Updates wieder automatisch.
- Lizenzen und Quellen: im Paket unter `config/magguucfw/LICENSES/UEBERSICHT.md`. Den Quelltext der eigenen Teile (Magguu Tools, reboot_ofw, MagguuOC) findest du als `MagguuCFW-Quelltext-<Version>.zip` im jeweiligen Release.
- Prüfsummen: `SHA256SUMS` im Release. Die Update-Dateien (`latest-*.json`) sind mit Ed25519 signiert; Magguu Tools prüft die Signatur.
- Version `0.1.0-rc17` ist ein **Release-Kandidat** und auf einer Switch **noch weitgehend ungeprüft**. Benutzung auf eigene Gefahr, keine Garantie. Dieses Paket steht in keiner Verbindung zu Nintendo.
- Fragen und Quelltext-Anfragen: Reiter **Issues**.

---

Ready-made packages (zip files) for the Nintendo Switch. This repo only holds the package, no source code and no keys. Download from the **Releases** tab and unzip into the root of the SD card. Since `0.1.0-rc7` there is **one** zip, `MagguuCFW-<version>.zip` (everything, with MagguuOC); the `full-MagguuOC` and `minimal` zips are gone.

- **Updating:** `full` users (e.g. rc16, rc15, rc14, rc13, rc12, rc11, rc10, rc9, rc8, rc7 or rc6 `full`) get rc17 automatically through the normal update in Magguu Tools.
- **One-time step for old `full-MagguuOC` and `minimal` installs (rc4 to rc6):** the old Magguu Tools app rejects the new package and changes nothing. Copy `switch/magguu-tools/magguu-tools.nro` from the current zip (rc17) to the same place on the SD card **once** (or unzip the whole zip into the root), open Magguu Tools and press "Aktualisieren" (update). After that, updates are automatic again.

Licences and sources: `config/magguucfw/LICENSES/UEBERSICHT.md` inside the package; source of our own GPL parts is attached to each release as `MagguuCFW-Quelltext-<version>.zip`. `0.1.0-rc17` is a release candidate and is **still largely untested on hardware**. Use at your own risk, no warranty. Not affiliated with Nintendo.
