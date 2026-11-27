# Badminton-Schleifchenturnier

Offline nutzbare Turnierleitung für wechselnde Badminton-Doppel. Die gesamte Anwendung steckt in einer einzigen HTML-Datei.

## Starten

`index.html` auf einem Handy oder Laptop in einem Browser öffnen. Ein Webserver, eine Installation und eine Internetverbindung sind nicht erforderlich.

## Funktionen

- Teilnehmende einzeln erfassen und ihre Spielstärke einschätzen
- Vorbereitung in drei einzeln aufklappbaren Schritten durchgehen; nach Turnierangaben und Teilnehmerliste jeweils bewusst zum nächsten Schritt wechseln
- In der Vorbereitung zunächst zehn Teilnehmende anzeigen, bei Bedarf alle einblenden; Namenssuche und Bearbeitung erfassen weiterhin die gesamte Liste
- Auf Handys über die feste Navigation unten zwischen den Bereichen wechseln; Backup oben sichern
- Anzahl der Felder einstellen
- Anzahl der Felder zwischen Runden ändern; während einer offenen Runde bleibt sie gesperrt
- Doppel und Pausen für jede Runde auslosen
- Ab Runde 3 auf Wunsch bisherige Siege pro gespieltem Spiel für ausgeglichenere Doppel berücksichtigen
- Personen in der aktuellen Aufstellung tauschen; nach Rundenstart werden dabei Ergebnisse gelöscht und die Zeit neu gestartet
- Noch offene Spiele in der aktuellen Runde anzeigen; Sieger erfassen, eine versehentliche Eingabe kurz rückgängig machen und Ergebnisse später korrigieren
- Eine offene Runde nach Bestätigung abbrechen; abgeschlossene Runden bleiben erhalten
- Rundenzeit nach der Auslosung manuell starten, pausieren und fortsetzen; Pausenzeit zählt weder für die Runde noch für einzelne Spiele
- Optionaler Zeitmodus mit 8 Minuten Standard und eigener Dauer je Runde; Countdown gilt für alle Felder, stoppt bei null und lässt sich verlängern
- Bei Zeitablauf bleiben Ergebnisse manuell erfassbar; Hallenansicht zeigt „Zeit abgelaufen“ und kann nach Aktivierung einen Signalton ausgeben
- Hallenansicht in einem zweiten Tab öffnen, auf einen großen Monitor ziehen und dort in Vollbild schalten; Status vor dem Start und bei Pause als Band über sichtbaren Feldern zeigen; fehlende Runde und Zeitablauf groß einblenden
- Auf dem Beamer zwischen Flyer, Spielplan und Rangliste wechseln; der Ranglistenknopf öffnet bei Bedarf den Hallen-Tab, zeigt zehn Personen pro Seite und berücksichtigt nur abgeschlossene Runden
- Beamer-Flyer vor der ersten Auslosung und zwischen Runden anzeigen; optional ein PNG-, JPG- oder WebP-Bild bis 1,5 MB wählen und zwischen Flyer und Spielplan überblenden
- Auf GitHub Pages halten sich zwei Tabs im selben Browser auf demselben Gerät automatisch aktuell; mehrere Leitungstabs werden gewarnt und veraltete Änderungen beim Speichern abgefangen
- Schleifchen und Rangliste automatisch berechnen; Gesamtspielzeit und Durchschnitt je Person auswerten
- Im Reiter Spieler eine Person suchen und ihren Rundenverlauf mit Partnern, Gegnern, Ergebnissen, Pausen und Spielzeiten ansehen
- Turnierstand lokal speichern, letzte erfolgreiche Speicherzeit anzeigen sowie als JSON-Backup exportieren und importieren
- Rangliste und Turnierverlauf drucken oder als PDF sichern

## Datensicherung

Der Browser speichert den Turnierstand lokal auf dem jeweiligen Gerät. Über **Backup sichern** in der oberen Leiste kann die Turnierleitung jederzeit eine JSON-Datei herunterladen, auch während einer laufenden Runde. Die Hallenansicht bietet denselben Knopf. Das Backup enthält auch bereits eingetragene Ergebnisse der aktuellen Runde, deren manuell gesetzte Startzeit und das ausgewählte Flyerbild. Die Datei kann über **Vorbereitung → Daten & Sicherung → Backup importieren** wieder geladen werden.

## Dateien

- `index.html` – vollständige Anwendung ohne externe Abhängigkeiten
