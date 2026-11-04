# DepotDuell

Vergleichsrechner für die private Altersvorsorge: das neue **Altersvorsorgedepot** (ab 1.1.2027), die **Riester-Rente** und ein freier **MSCI-World-Sparplan**, jeweils nach Steuern mit Rentenbeginn.

## Funktionen

- **Eigene Annahmen:** Alter, Beitrag, Kinder, Rendite, Kosten, Steuersatz heute und im Alter, jeweils mit Hinweis, was realistisch ist
- **Ergebnis:** Nettobetrag je Variante mit Balken (Einzahlungen, Förderung, Ertrag, Steuern), Verlauf, Aufschlüsselung und Gewinnschwelle beim Steuersatz im Alter
- **Ausland:** Jahre ohne Förderberechtigung und Rückforderung bei Wohnsitz außerhalb von EU/EWR (§ 95 EStG)
- **Handy:** drei Reiter statt einer langen Seite; Regler nur am Knopf greifbar, dazu Minus/Plus
- **Hell/Dunkel-Modus:** gemeinsame Einstellung mit dem Dashboard (`overall-theme`)
- **PWA:** installierbar und offline nutzbar

Regeln nach dem Altersvorsorgereformgesetz (BGBl. I 2026 Nr. 156), Stand November 2026. Vereinfachtes Modell, keine Steuerberatung.

## Aufbau

- `index.html`: die komplette App (HTML, CSS, JS)
- `sw.js`: Service Worker; bei neuen oder umbenannten Dateien die Cache-Version erhöhen
- `shared/ios-nav.js`: gemeinsame Navigation wie in den anderen Apps
- `icon.svg`, `icon-maskable.svg`, `icons/`: App-Icon im gemeinsamen Stil (Akzent Grün `#0f7a5c`)

Teil des Dashboards [mvs2-bot.github.io](https://mvs2-bot.github.io/).
