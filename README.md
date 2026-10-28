# MagguuCFW – Releases

Fertige Pakete (Zip-Dateien) für die Nintendo Switch. Hier liegt **nur das Paket**, kein Quellcode und keine Schlüssel.

- Download: Reiter **Releases**. Wähle das Zip: `full` (Standard), `full-MagguuOC` (mit MagguuOC) oder `minimal` (klein, ohne Horizon OC).
- Entpacke das Zip in die **Wurzel** der SD-Karte (so, dass `atmosphere`, `bootloader`, `switch` direkt auf der SD liegen).
- Lizenzen und Quellen: im Paket unter `config/magguucfw/LICENSES/UEBERSICHT.md`. Den Quelltext der eigenen Teile (Magguu Tools, reboot_ofw, MagguuOC) findest du als `MagguuCFW-Quelltext-<Version>.zip` im jeweiligen Release.
- Prüfsummen: `SHA256SUMS` im Release. Die Update-Dateien (`latest-*.json`) sind mit Ed25519 signiert; Magguu Tools prüft die Signatur.
- Version `0.1.0-rc6` ist ein **Release-Kandidat** und auf einer Switch **noch nicht geprüft**. Benutzung auf eigene Gefahr, keine Garantie. Dieses Paket steht in keiner Verbindung zu Nintendo.
- Fragen und Quelltext-Anfragen: Reiter **Issues**.

---

Ready-made packages (zip files) for the Nintendo Switch. This repo only holds the package, no source code and no keys. Download from the **Releases** tab and unzip into the root of the SD card. Licences and sources: `config/magguucfw/LICENSES/UEBERSICHT.md` inside the package; source of our own GPL parts is attached to each release as `MagguuCFW-Quelltext-<version>.zip`. `0.1.0-rc5` is a release candidate and has **not yet been tested on hardware**. Use at your own risk, no warranty. Not affiliated with Nintendo.
