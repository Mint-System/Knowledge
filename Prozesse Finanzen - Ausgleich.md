# Prozess Ausgleich
Kontostand eBanking mit Odoo abgleichen.

## Kontodaten exportieren

Arbeitsschritte:
* Im eBanking einloggen
* Unter Datentransfer die Kontodaten als camt.053 XML-Datei herunterladen
* Die Datei unter *Finanzen > Datentransfer* ablegen
* Datei importieren *Finanzen > Übersicht > Journal Bank > Import*
* Die einzelnen Transaktionen mit Rechnungen abgleichen

## Import Kontoauszug
Arbeitsschritte:
* Kontoauszug als XML-Datei ISO-20022 camt.053 exportieren
* Die Datei in Odoo importieren
* Für jede Zahlung  eine offene Rechnung auswählen