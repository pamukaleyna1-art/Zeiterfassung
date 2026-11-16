# Zeiterfassung

Kleine Web-App zum Stempeln der eigenen Arbeitszeit – mit Projekten, Monatsübersicht, Zeitsaldo, Urlaub und Export nach Excel, CSV oder PDF.

## Datenschutz

- Die App hat **keinen Server**. Alle Einträge werden nur lokal im Browser des eigenen Geräts gespeichert (localStorage).
- Dieses Repository enthält **nur den Programmcode**, keine persönlichen Daten.
- **Keine Sicherungsdateien (`.json`) oder Exporte (`.xlsx`, `.csv`, `.pdf`) in dieses Repository hochladen.**

## Funktionen

- Start/Stopp mit Projektauswahl, Projekt wechseln, Notiz pro Buchung
- Zeiten nachtragen und bearbeiten (inkl. Pause)
- Soll-Zeit pro Wochentag, Eintrittsdatum, Zeitsaldo inkl. Übertrag
- Österreichische Feiertage werden automatisch berechnet (inkl. Ostern/Pfingsten), 24.12./31.12. einstellbar, eigene freie Tage
- Urlaub, Krankenstand, Zeitausgleich usw. als Zeitraum
- Hinweise nach AZG (über 10 h / 12 h, Pause unter 30 Min.)
- Export: Excel (Arbeitszeit, Projekte, Buchungen), CSV, PDF/Druck
- Sicherung herunterladen / wiederherstellen
- Installierbar auf dem Startbildschirm, funktioniert offline

## Veröffentlichen mit GitHub Pages

1. Alle Dateien in ein Repository hochladen.
2. **Settings → Pages → Build and deployment**: Source „Deploy from a branch“, Branch `main`, Ordner `/ (root)` → Save.
3. Nach ca. 1 Minute ist die App unter `https://<benutzername>.github.io/<repo-name>/` erreichbar.

## Lizenz

Excel-Export mit [SheetJS](https://sheetjs.com) (Apache License 2.0), Datei `xlsx.full.min.js`.
