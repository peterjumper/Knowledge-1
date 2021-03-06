# App Finanzen
Installation Modul Finanzen (account_accountant).

## Initialisierung

Arbeitsschritte:
*  Unternehmensdaten eintragen
*  Bankkonto erfassen
	*  IBAN: CH3989144871696181962
	*  Name: UBS
*  Buchungsperiode eröffnen
*  Kontenplan übernehmen

## Erweiterungen installieren

Auswahl:
* Import CAMT Bank Statement (account_bank_statement_import_camt)
* SEPA Kreditübertragung (account_sepa)
* Account Invoice Extract (account_invoice_extract)
* Accounting Reports (account_reports)
* Analytische Konten   (analytic_enterprise)
* Budgetverwaltung (account_budget)
* Schweizer Buchhaltungsauswertungen (l10n_ch_reports)

## Customizing
Auswahl:
* Journale und Sequenzen festlegen

## Optionen aktivieren
Navigation nach *Einstellungen > Finanzen* und Auswahl:
* Print Swiss QR Code
* Rechnungsdigitalisierung
* Kostenrechnung
* Kostenstellen-Tags

## Import Kontoauszug
Arbeitsschritte:
* Kontoauszug als XML-Datei ISO-20022 camt.053 exportieren
* Die Datei in Odoo importieren
* Für jede Zahlung  eine offene Rechnung auswählen