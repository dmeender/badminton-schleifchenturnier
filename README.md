# Badminton-Schleifchenturnier

Offline nutzbare Turnierleitung für wechselnde Badminton-Doppel. Die gesamte Anwendung steckt in einer einzigen HTML-Datei.

## Starten

`Schleifchenturnier.html` auf einem Handy oder Laptop in einem Browser öffnen. Ein Webserver, eine Installation und eine Internetverbindung sind nicht erforderlich.

## Funktionen

- Teilnehmende einzeln erfassen und ihre Spielstärke einschätzen
- Anzahl der Felder einstellen
- Doppel und Pausen für jede Runde auslosen
- Personen in der aktuellen Aufstellung tauschen
- Sieger erfassen und Ergebnisse später korrigieren
- Rundenzeit ab Auslosung und Spieldauer bis zur Ergebniseingabe erfassen
- Zentrierte Hallenansicht für einen großen Monitor im Vollbild anzeigen
- Zwei Tabs im selben Browser halten Anzeige und Ergebniseingabe auf demselben Gerät aktuell
- Schleifchen und Rangliste automatisch berechnen
- Turnierstand lokal speichern sowie als JSON-Backup exportieren und importieren
- Rangliste und Turnierverlauf drucken oder als PDF sichern

## Datensicherung

Der Browser speichert den Turnierstand lokal auf dem jeweiligen Gerät. Über **Backup sichern** in der oberen Leiste kann die Turnierleitung jederzeit eine JSON-Datei herunterladen, auch während einer laufenden Runde. Die Hallenansicht bietet denselben Knopf. Das Backup enthält auch bereits eingetragene Ergebnisse der aktuellen Runde und deren Startzeit. Die Datei kann über **Vorbereitung → Daten & Sicherung → Backup importieren** wieder geladen werden.

## Dateien

- `Schleifchenturnier.html` – vollständige Anwendung ohne externe Abhängigkeiten
