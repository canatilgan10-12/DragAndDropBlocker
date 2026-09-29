# Drag & Drop Blocker

Browser-Erweiterung, die verhindert, dass Dateien **versehentlich per Drag & Drop** auf fremde Websites gezogen werden. Zusätzlich warnt sie, wenn **sensible Daten** wie AHV-Nummern oder IBAN in Textfelder eingegeben oder eingefügt werden.

> Entwickelt während meines Praktikums. Die Screenshots zeigen Beispieldaten.

## Was das Tool macht

- **Drag & Drop blockieren:** Auf allen Websites, die nicht auf der Whitelist stehen, können keine Dateien abgelegt werden. Auch das versehentliche Ersetzen der aktuellen Seite durch eine abgelegte Datei wird verhindert.
- **Whitelist:** Erlaubte Domains lassen sich verwalten, Wildcards wie `*.sharepoint.com` sind möglich. Eine Website kann direkt aus dem Popup freigegeben werden. Der Schutz lässt sich auch für eine Minute temporär deaktivieren.
- **Eingabe-Schutz (Text Guard):** Warnt bei Telefonnummer, E-Mail-Adresse, IBAN, Kreditkartennummer, AHV-Nummer und weiteren Datentypen. Der eingegebene Text wird dabei nie verändert.
- **Compliance-Profile:** nDSG und DSGVO aktivieren die passenden Datentypen mit einem Klick, einzelne Muster bleiben frei wählbar.
- **Dashboard:** Statistik der Blockierungen nach Domain, letzte Ereignisse und Zusammenfassung.
- **Export und Import** der Einstellungen sowie ein dunkles Design.

## Screenshots

### Popup
Status der aktuellen Website mit Schnellaktionen.

<img src="screenshots/01-popup.png" alt="Popup" width="320">

### Einstellungen
Whitelist-Verwaltung, Eingabe-Schutz und Aktionen.

<img src="screenshots/02-einstellungen.png" alt="Einstellungen" width="700">

### Eingabe-Schutz
Compliance-Profile und Auswahl der Datentypen.

<img src="screenshots/03-eingabe-schutz.png" alt="Eingabe-Schutz" width="600">

### Dashboard
Statistiken und Aktivitätsübersicht.

<img src="screenshots/04-dashboard.png" alt="Dashboard" width="500">

### Informationen
Übersicht über Status, Berechtigungen und Einschränkungen.

<img src="screenshots/05-informationen.png" alt="Informationen" width="500">

### Hinweise für Benutzer
Meldung bei blockiertem Drag & Drop und bei geschützten Eingaben.

<img src="screenshots/06-hinweis-drag-and-drop-blockiert.png" alt="Hinweis: Drag & Drop blockiert" width="450">
<img src="screenshots/07-hinweis-eingabe-schutz.png" alt="Hinweis: Eingabe nicht erlaubt" width="450">
