# Badminton-Schleifchenturnier

Offline nutzbare Turnierleitung für wechselnde Badminton-Doppel. Die gesamte Anwendung steckt in einer einzigen HTML-Datei.

## Starten

`index.html` auf einem Handy oder Laptop in einem Browser öffnen. Ein Webserver, eine Installation und eine Internetverbindung sind nicht erforderlich.

## Funktionen

- Teilnehmende einzeln erfassen und ihre Spielstärke einschätzen
- Auf Handys über die feste Navigation unten zwischen den Bereichen wechseln; Backup oben sichern
- Anzahl der Felder einstellen
- Doppel und Pausen für jede Runde auslosen
- Personen in der aktuellen Aufstellung tauschen
- Sieger erfassen und Ergebnisse später korrigieren
- Rundenzeit ab Auslosung und Spieldauer bis zur Ergebniseingabe erfassen
- Hallenansicht in einem zweiten Tab öffnen, auf einen großen Monitor ziehen und dort in Vollbild schalten
- Auf GitHub Pages halten sich zwei Tabs im selben Browser auf demselben Gerät automatisch aktuell
- Schleifchen und Rangliste automatisch berechnen; Gesamtspielzeit und Durchschnitt je Person auswerten
- Turnierstand lokal speichern sowie als JSON-Backup exportieren und importieren
- Rangliste und Turnierverlauf drucken oder als PDF sichern

## Datensicherung

Der Browser speichert den Turnierstand lokal auf dem jeweiligen Gerät. Über **Backup sichern** in der oberen Leiste kann die Turnierleitung jederzeit eine JSON-Datei herunterladen, auch während einer laufenden Runde. Die Hallenansicht bietet denselben Knopf. Das Backup enthält auch bereits eingetragene Ergebnisse der aktuellen Runde und deren Startzeit. Die Datei kann über **Vorbereitung → Daten & Sicherung → Backup importieren** wieder geladen werden.

## Dateien

- `index.html` – vollständige Anwendung ohne externe Abhängigkeiten
