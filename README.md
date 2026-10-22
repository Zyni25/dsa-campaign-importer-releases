# DSA Campaign Importer – Installationspakete

Dieses Repository enthält die **öffentlich herunterladbaren, geprüften Installationsdateien** des Foundry-VTT-Moduls `dsa-campaign-importer`. Die Entwicklung erfolgt getrennt in einem privaten Repository.

## Erste installierbare Version: 0.1.1

- **Manifest-URL:** `https://raw.githubusercontent.com/Zyni25/dsa-campaign-importer-releases/main/module.json`
- **Installationsdatei:** `https://raw.githubusercontent.com/Zyni25/dsa-campaign-importer-releases/main/releases/v0.1.1/dsa-campaign-importer.zip`
- Getestete Importfunktionen: Journal anlegen, vorhandenes Journal nicht überschreiben, Fehler bei ungültiger JSON-Datei melden, Standardberechtigung `All Players: None`.
- Testumgebung: Foundry 14 Build 367, DSA5 8.1.11 auf The Forge.
- Gegenüber 0.1.0: Importcode unverändert, Installations-/Update-Adressen und Kompatibilitätsangabe ergänzt.
- **Noch nicht überprüft:** Neuinstallation/Aktualisierung direkt über The Forge anhand dieser Manifest-URL.

## Installation

Öffne in The Forge die Paket-/Modulverwaltung und verwende **„Installieren über Manifest“** mit der Manifest-URL von oben. Bereits installierte Module werden auf The Forge oft zwischen Spielwelten geteilt: vor dem Aktualisieren einer vorhandenen Installation muss geprüft werden, ob die Hauptwelt betroffen sein könnte.

## Sicherheit

Die Installationsdatei ist öffentlich und enthält den ausführbaren Programmcode. Keine privaten Weltdaten, Abenteuer-PDFs oder Zugangsdaten gehören in dieses Repository. Das Archiv ist versioniert und soll nach Veröffentlichung unverändert bleiben.
