# Projektarchiv - Ordnerstruktur und Übersicht

Willkommen zum Endabgabe-Archiv unseres Software Engineering Projekts. Dieses Archiv bündelt den gesamten Entwicklungsstand, die Dokumentation sowie alle projektbezogenen Artefakte, die im Laufe der Entwicklungsphasen entstanden sind.

Um eine saubere Trennung der Verantwortlichkeiten (Separation of Concerns) sicherzustellen, haben wir unser Projekt in drei klar voneinander abgegrenzte Repositories (Ordner) aufgeteilt. Diese Struktur erleichtert sowohl die Entwicklung als auch die spätere Wartung des Systems.

## Die drei Haupt-Repositories

Die oberste Ebene dieses Archivs gliedert sich in die folgenden drei Kernbereiche:

- `/Backend/`
- `/frontend/`
- `/docs/` (Dokumentation)

Im Folgenden wird detailliert erläutert, welchen Zweck diese Ordner erfüllen und was genau in ihnen zu finden ist.

---

### 1. Backend (`/Backend/`)

Dieses Repository bildet das technologische Fundament und das Herzstück unserer Anwendung. Hier läuft die gesamte zentrale Geschäftslogik ab und hier werden die Daten verwaltet.

**Inhalt und Zweck:**
- **Server & API:** Das Backend stellt die Schnittstellen (API) bereit, über die das Frontend mit den Daten kommuniziert. Sämtliche Algorithmen, Datenverarbeitungsprozesse und die Kommunikation mit der Datenbank sind hier gekapselt.
- **Code & Tests:** In den Quellcode-Ordnern des Backends finden Sie die eigentliche Logik (z.B. Controller und Services). Direkt daneben liegen die zugehörigen Tests (Unittests und Integrationstests), mit denen die Stabilität der Funktionen sichergestellt wird.

---

### 2. Frontend (`/frontend/`)

Dieses Repository ist ausschließlich für die Benutzeroberfläche (User Interface - UI) und die clientseitige Nutzererfahrung zuständig. Es greift auf die Daten aus dem Backend zu und bereitet diese visuell auf.

**Inhalt und Zweck:**
- **Benutzeroberfläche:** Hier befindet sich die gesamte visuelle Darstellung, die im Browser ausgeführt wird, inklusive Layouts, Styling und clientseitiger Interaktionslogik.
- **Code & Tests:** Die Code-Basis enthält alle UI-Komponenten und Views. Auch hier sind die spezifischen Frontend-Tests direkt im Code-Verzeichnis integriert, um sicherzustellen, dass die Benutzeroberfläche fehlerfrei funktioniert.

---

### 3. Dokumentation (`/docs/`)

Das Docs-Repository ist der zentrale Anlaufpunkt für alle konzeptionellen, organisatorischen und anleitenden Informationen rund um das Projekt. 

**Inhalt und Zweck:**
- **Installationsanleitung & Setup:** Einer der wichtigsten Bestandteile in diesem Ordner ist die detaillierte Installationsanleitung. Wenn Sie das Projekt (Frontend und Backend) starten oder evaluieren möchten, finden Sie hier alle notwendigen Schritte, Systemanforderungen und Befehle.
- **Projektphasen & Fortschritt:** Sie finden hier Ordner zu den einzelnen Projektphasen (z.B. Phase 1 bis 6), in denen Meilensteine, Berichte und Abgabedokumente gesammelt sind.
- **Systemdesign & Architektur:** Das Verzeichnis enthält außerdem Entwürfe, Architekturdiagramme, Datenbankmodelle sowie Protokolle.
- **Weitere Handbücher:** Allgemeine Beschreibungen, Nutzerhandbücher und API-Dokumentationen liegen ebenfalls in diesem Bereich.

---

### Zusammenfassung & Erste Schritte

Zusammenfassend lässt sich sagen: **Backend** und **Frontend** enthalten den jeweiligen ausführbaren Programmcode samt der dazugehörigen Tests. Das **Docs**-Verzeichnis bündelt hingegen das gesamte theoretische Wissen und alle Anleitungen.

**Der beste Startpunkt:** 
Bitte navigieren Sie für die Einrichtung des Projekts direkt in den Ordner `/docs/`. Suchen Sie dort nach der **Installationsanleitung** – diese führt Sie strukturiert durch den gesamten Startprozess der Anwendung.
