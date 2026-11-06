# Freewood-Loot

**Deutsch & English · German & English.** Autor · Author: Lacustat. Version 0.1.6 · Interface 16001 (World of Warcraft: Forever).

![loot](https://github.com/Lacustat/Freewood-OctoWoW-Bilder/blob/main/loot.jpg)

## Inhalt · Contents
- [Deutsch](#deutsch)
- [English](#english)
- [Tastenbelegung · Key bindings](#tastenbelegung--key-bindings)

## Deutsch

### Was ist das?
Eine Blacklist für Beute: gelistete Items nimmt das Addon mit und löscht sie mit deinem nächsten Klick in der Spielwelt. Forever erlaubt das Löschen nur durch einen Klick von dir.

### Funktionen
- Listen, „Zuletzt erhalten“ und Protokoll gelten pro Charakter.
- Selbsttest mit `/fwloot test`.

### Abhängigkeiten
- Benötigt: `Freewood-Core`
- Optional: –

### Befehle
- `/fwloot`: Reiter öffnen
- `/fwloot test`: Selbsttest

### Installation
Den Ordner `Freewood-Loot` nach `World of Warcraft\_forever_\Interface\AddOns\` kopieren. Neue Dateien lädt das Spiel erst nach einem kompletten Neustart; ein `/reload` genügt nur, wenn sich bestehende Dateien geändert haben. Fehler sichtbar machen: `/console scriptErrors 1`, danach `/reload`.

### Hinweise
Alles Neue ist, soweit nicht anders vermerkt, im Spiel noch nicht geprüft (getestet wurde in einer Simulation).

### Lizenz
GPL-3.0, siehe `LICENSE`.

---

## English

### What is it?
A blacklist for loot: the addon picks up listed items and deletes them with your next click in the world. Forever only allows deleting through a click of yours.

### Features
- Lists, “recently received” and the protocol are per character.
- Self-test with `/fwloot test`.

### Dependencies
- Required: `Freewood-Core`
- Optional: –

### Commands
- `/fwloot`: Reiter öffnen
- `/fwloot test`: Selbsttest

### Installation
Copy the folder `Freewood-Loot` to `World of Warcraft\_forever_\Interface\AddOns\`. New files only load after a full game restart; a `/reload` is enough only when existing files changed. To see errors: `/console scriptErrors 1`, then `/reload`.

### Notes
Unless marked otherwise, everything new has not yet been verified in game (it was tested in a simulation).

### License
GPL-3.0, see `LICENSE`.

## Tastenbelegung · Key bindings
**DE:** Unter Optionen > Tastaturbelegung gibt es einen eigenen Abschnitt für dieses Modul. Dort lässt sich eine Taste zum Öffnen und Schließen des Reiters belegen (zum Beispiel J für die Gilde). Ist der Reiter schon offen, schließt dieselbe Taste das Fenster. Nach der Installation einmal das Spiel neu starten, damit die neue Datei Bindings.xml gelesen wird.
**EN:** Options > Key Bindings has its own section for this module. Bind a key to open and close the tab (for example J for the guild). If the tab is already open, the same key closes the window. Restart the game once after installing so the new Bindings.xml file is read.
