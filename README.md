# Netzwerk-Spielwiese

Interaktive Visualisierung zu Access Point, Switch, Router und Repeater.

## Verwenden

`index.html` direkt im Browser öffnen. Die Anwendung benötigt keine externen Abhängigkeiten, keinen Build und kein Backend.

## Missionen

- PC öffnet eine Website – Hin- und Rückweg der Daten.
- Handy druckt lokal – funktioniert auch ohne Internet.
- Laptop surft über einen Repeater – guter Standort und Funkloch im Vergleich.

Geräte können angeklickt werden. Die Reise lässt sich schrittweise oder automatisch abspielen. Internetanschluss und Repeater-Standort sind umschaltbar.

## Deployment

Statische Website auf Vercel. Framework: Other, kein Build-Befehl, Ausgabe im Projektverzeichnis. Produktionsbranch: `main`.

Das Netzwerk ist ein vereinfachtes Lernmodell; DNS, ARP und weitere Protokolldetails werden nicht simuliert.

## Packet Rescue

Am Seitenende wartet ein Lernspiel mit zehn Einsätzen pro Runde: sieben zufällig gewählte Störungsfragen aus einem Pool von 15 und drei Datenweg-Aufgaben. Vier Fehler beenden die Runde. Richtige Antworten geben Punkte und Kombos; Hinweise reduzieren den möglichen Punktgewinn. Jede Entscheidung erhält eine Erklärung. Ein Lernprotokoll und lokal gespeicherter Rekord runden das Spiel ab. Lokale Speicherung ist optional; das Spiel funktioniert auch ohne sie.
