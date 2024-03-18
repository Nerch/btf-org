# btf-org
Webbasierte Lösung zur Organisation von Festival-Helfern.

# Festival-Webanwendung

Dieses Projekt dient der Vorstellung einer Webanwendung für ein Festival. Es umfasst ein Frontend, das mit HTML und CSS gestaltet wurde, und nutzt MariaDB für die Datenhaltung. Ziel dieses Projekts ist es, neu erlernte Fähigkeiten in einem praktischen Kontext anzuwenden und zu festigen, insbesondere in den Bereichen Webentwicklung und Datenbankmanagement.

## Projektübersicht
Die Webanwendung bietet umfassende Informationen und Funktionen zur Optimierung der Organisation und Koordination der Festival-Helfer. Ziel ist es, Administratoren und Teamleitern ein effektives Werkzeug an die Hand zu geben, mit dem sie die vielfältigen Aufgaben rund um das Festival managen können. Zu den Kernfunktionen der Anwendung gehören:

  **Überblick über die Helfer:** 
  Ein zentrales Dashboard, das einen schnellen Zugriff auf Helferprofile, Verfügbarkeiten und zugewiesene Aufgaben bietet.
  
  **Essensausgabenplanung:** 
  Ein Planungstool, das die Verwaltung und Koordination der Essensausgaben für Helfer und Künstler vereinfacht, inklusive Zeitplänen und speziellen Ernährungsbedürfnissen.
 
  **Schichtplanung:** 
  Ein flexibles Schichtplanungssystem, das die Zuweisung von Helfern zu verschiedenen Schichten basierend auf Verfügbarkeit, Fähigkeiten und Präferenzen ermöglicht.
  
  **Einsatzort und Aufgabenbereich:** 
  Ein interaktives Tool zur Definition und Verwaltung von Einsatzorten und Aufgabenbereichen, inklusive detaillierter Beschreibungen und Anforderungen für jede Position.

Diese Funktionen tragen dazu bei, die Effizienz und Effektivität der Helferkoordination zu steigern und eine reibungslose Durchführung des Festivals zu gewährleisten.

## Struktur

Das Projekt ist in mehrere Hauptkomponenten unterteilt:

- `frontend/`: Enthält die HTML-Seiten und zugehörigen CSS- und JavaScript-Dateien für das User Interface.
- `database/`: Beinhaltet Skripte für die Einrichtung der MariaDB-Datenbank, einschließlich Schema-Definitionen und Initial-Daten.
- `documentation/`: Enthält zusätzliche Dokumentationen zum Projekt und seiner Architektur.

## Voraussetzungen

Um dieses Projekt lokal auszuführen, müssen folgende Werkzeuge installiert sein:

- Ein Webserver (z.B. Apache, Nginx)
- MariaDB
- PHP (optional, falls serverseitige Skripte oder APIs verwendet werden)

## Lokale Einrichtung

1. Klone das Repository auf deinen lokalen Rechner.
2. Konfiguriere deinen Webserver, um auf das `frontend/`-Verzeichnis zu zeigen.
3. Importiere die `database/schema.sql` und `database/seeds.sql` in deine MariaDB-Datenbank, um die Datenbankstruktur und Anfangsdaten einzurichten.
4. Besuche die Website über deinen Webbrowser, indem du die entsprechende URL deines Webservers aufrufst.

## Mitwirken

Beiträge zum Projekt sind willkommen. Bitte erstelle einen Issue oder Pull Request, wenn du Verbesserungen vorschlagen möchtest.

## Lizenz

Dieses Projekt ist unter der GNU General Public License (GPL) veröffentlicht. Details findest du in der [LICENSE](LICENSE)-Datei.
