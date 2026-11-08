# Story Director by Erzählwerk

Dein lokales Geschichtenatelier für Windows: Welten und Figuren entwickeln,
Geschichten schreiben und bearbeiten, Hörfassungen produzieren und Ausgaben exportieren.

## Installieren

**[Aktuellen Windows-Installer herunterladen](https://github.com/futuremeetsreality/story-director-downloads/releases/latest/download/StoryDirector-Install.exe)**

1. `StoryDirector-Install.exe` öffnen.
2. Programmordner und einen getrennten Datenordner wählen: neu beginnen oder vorhandene Story-Director-Daten weiterverwenden.
3. Installieren und Story Director starten. Bei einem neuen Atelier die erste eigene Welt anlegen.

Für Windows 10/11 (64 Bit). Python und FFmpeg sind enthalten. Git, Terminalbefehle
oder eine separate Python-Installation werden nicht benötigt. Die Oberfläche
öffnet sich im Browser; Geschichten und Aufnahmen bleiben auf deinem Computer.

Ein neues Atelier startet ohne Beispielgeschichten oder frühere Fassungen.
Bei Verwendung eines vorhandenen Datenordners bleiben dessen Welten, Geschichten,
Aufnahmen und Fassungen erhalten. Eigene API-Schlüssel für OpenAI, Fish Audio oder
ElevenLabs können bei der Einrichtung oder später in den Einstellungen eingetragen
werden. Anbieteraufrufe können Kosten verursachen.

## Einstieg, Daten und Hilfe

Ab Version **1.1.2** findest du in den Einstellungen:

- **Erste Schritte**: eine Checkliste bis zur ersten Ausgabe; manuelle Figuren und eigene Texte benötigen keinen Cloud-Auftrag.
- **Anbieterzugänge prüfen** und **Kostenwarnungen**: ausdrückliche Zugangstests, Bestätigungen, Warnschwellen und eigene Richtpreise. Schätzungen sind kein festes Limit des externen Anbieterkontos.
- **Datenordner & Sicherungen**: vorhandene Daten verwenden, neu beginnen oder eine Versionssicherung bzw. ein vollständiges Projekt-ZIP in einen leeren Zielordner wiederherstellen. Vor dem Wechsel wird gesichert.
- **Welten verwalten**: anlegen, umbenennen, archivieren, in den Papierkorb verschieben und wiederherstellen. Endgültiges Löschen erfordert den Weltnamen; physische Medien und Sicherungen bleiben erhalten.
- **System & Datenpfad** und **Diagnose herunterladen**: verwendete Version und Ordner prüfen oder technische Angaben ohne Geschichten, Schlüssel und persönliche Pfade exportieren.

Das Schließen des Browserfensters beendet den Server nicht. Verwende dafür
**Einstellungen → Server beenden**.

## Lokale Nutzer

Ab Version **1.1.3** öffnet der Nutzername **oben rechts** die **Nutzerauswahl**.
Alternativ findest du sie unter **Einstellungen → Lokale Nutzer → Nutzer auswählen**.

Der bisherige Datenbestand heißt zunächst **Standard** und lässt sich umbenennen.
Mit **Nutzer anlegen** vergibst du einen Benutzernamen und einen getrennten Datenpfad.
Wähle einen leeren Ordner für ein Testatelier oder einen vorhandenen Story-Director-
Datenordner. Beim Auswählen werden die Daten geprüft, gesichert und mit einem
geordneten Neustart geöffnet. Laufende Aufträge müssen vorher abgeschlossen sein.

**Auswahleintrag entfernen** entfernt nur die Registrierung. Geschichten, Aufnahmen
und Sicherungen bleiben im Datenordner erhalten; der aktive Nutzer ist geschützt.
Die Auswahl bleibt über Updates erhalten. Sie verwaltet lokale Datenbestände und
enthält keine Anmeldung mit Passwort oder Berechtigungsverwaltung.

## Aktualisieren

Ab Version **1.1.0** unter **Einstellungen → Updates …** nachsehen und **Update herunterladen**
wählen. Nach abgeschlossenen Aufträgen und gespeicherten Änderungen auf
**Neustarten & aktualisieren** klicken. Ein eigenes Updatefenster sichert Daten und
Programm, installiert im Hintergrund und startet Story Director wieder.

Für ältere Versionen einmalig den aktuellen Installer herunterladen, Story Director
über **Anwendung beenden** schließen und in den bisherigen Programmordner installieren.
Der Datenordner wird übernommen. Danach erfolgen Updates direkt aus der Anwendung.

Eine Deinstallation entfernt das Programm. Persönliche Geschichten im getrennten
Datenordner bleiben erhalten. **Sicherung wiederherstellen** im Startmenü öffnet
den Assistenten für automatische Versionssicherungen.

[Alle Versionen und Änderungen](https://github.com/futuremeetsreality/story-director-downloads/releases)

Der Installer ist derzeit nicht mit einem Herausgeberzertifikat signiert.
Dieses Repository dient der Verteilung; die Entwicklung wird separat verwaltet.
Die jeweiligen Lizenzhinweise für Python und FFmpeg liegen im Installationsordner.
