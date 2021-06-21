# Prozess Aufgaben verwalten
Aufgabenverwaltung im Odoo

## Aufgabe erstellen

Beim Erstellen einer Aufgabe muss beachtet werden, dass standardmässig ein Auftragselement aus dem verlinkten Verkaufsauftrag hinzugefügt wird. Soll die verbuchte Zeit auf der Aufgabe verrechnet werden, muss ein entsprechendes Auftragselement vorhanden sein. Ansonsten gilt es den Link zum Auftrag zu entfernen.

### Haupt- und Unteraufgaben

Alle Unteraufgaben haben Prefix: `OI: `. OI steht in diesem Fall für Odoo Implementierung.  
Alle Hauptaufgaben haben am Ende des Namens den Suffix " (OI)" mit den jeweiligen Anfangsbuchstaben.

![[Prozesse Projektmanagent Unterteilung Aufgaben.png]]

### Vorlagen

**Verrechenbar**

* Odoo Implementierung (OI) - Implementation von Odoo-Funktionen
* Projektleitung (PL) - Allgmeine Projektleitung
* Software-Entwicklung (SE) - Implementation von Geschäftsapplikationen
* System-Engineering (SN) - Konfiguration Betriebssystem und Applikationen
* Projektphase (PX) - Name der Projektphase und Nummer anstelle von X
* Geschäftsanalyse (GA) - Abwicklung von Beratungsprojekten

**Nicht verrechenbar**

* Anforderungsanalyse (AA) - Anforderungen definieren
* Projektadministration (PA) - Administrativer Aufwand zur Erstellung und Verwaltung des Projekts
* Know-how (KH) - Erarbeiten Basiswissen zur Beratung von Kunden
* Reisezeit (RZ) - Fahrzeit zum Kunden

## Aufgabenstatus festlegen

Jede Projektaufgabe durchläuft die folgenden Stufen:
* **Backlog [[Emoji#🎒|🎒]]** Hier werden neue Aufgaben erstellt und Ideen gesammelt.
* **Bereit 🏁** Die Aufgabe ist bereit und hat alle Informationen zur Bearbeitung hinterlegt.
* **In Arbeit 🧑‍💻** Die Aufgabe befindet sich in Bearbeitung.
* **Zur Verifizierung 🔍** Der Abschluss der Aufgabe wird durch eine zweite Person verifiziert.
* **Erledigt ✅** Die Aufgabe ist erledigt und kann archiviert werden.
* **Permanent ♻️** Die Aufgabe steht Permanent zur Zeiterfassung zur Verfügung.

## Aufgaben bündeln

Bei mehreren Aufgaben ist es schwierig die Übersicht der Fristen zu behalten. Zur Planung können mehrere Aufgaben zu einem Paket gebündelt werden. Dazu erstellt man eine Aufgabe mit der Bezeichung `AP1: Beschreibung`. Das Aufgabenpaket (AP) verlinkt man mit den anderen Aufgaben.

Auf die Aufgabenpakete wird keine Zeit gebucht. Sie dienen lediglich der Planung.