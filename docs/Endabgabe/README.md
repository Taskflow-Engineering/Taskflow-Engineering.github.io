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

Das Docs-Repository ist der zentrale Anlaufpunkt für alle konzeptionellen, organisatorischen und anleitenden Informationen rund um das Projekt. Besonders relevant ist der Ordner `/docs/Endabgabe/`, der alle finalen und überarbeiteten Dokumente der Endabnahme bereithält.

**Detaillierte Struktur der Dokumentation (`/docs/Endabgabe/`):**

- **`/Anleitungen/`**:
  - `TaskFlowEngineering-Endabgabe-Installationsanleitung.pdf`: **Der wichtigste Startpunkt.** Dieses Dokument erklärt Schritt für Schritt, wie Sie das Backend und Frontend lokal aufsetzen, konfigurieren und ausführen.
  - `TaskFlowEngineering-Endabgabe-Handbuch-Zensiert.pdf`: Das Nutzerhandbuch. Es beschreibt aus Anwendersicht, wie die Software bedient wird und welche Funktionen zur Verfügung stehen.

- **`/Design/`**:
  - `TaskFlowEngineering-Endabgabe-Designbeschreibung.pdf`: Enthält die Architektur, UML-Klassendiagramme und grundlegende technische Design-Entscheidungen, die wir getroffen haben.

- **`/Dokumentation/`**:
  - `Swagger-Api.pdf`: Detaillierte Dokumentation aller REST-API-Endpunkte, inklusive Anfragen und Antworten.
  - **`/Code_Dokumentation/`**: Beinhaltet generierte und manuell geschriebene Dokumentationen direkt zum Code (`backend-kommentar-dokumentation.pdf` und `frontend-dokumentation.pdf`), um Entwicklern das Verständnis der Architektur zu erleichtern.

- **Zentrale Projekt-Dokumente (direkt in `/docs/Endabgabe/`):**
  - `TaskFlowEngineering-Endabgabe-Storyplan.pdf`: Zeigt, wie wir die Anforderungen in Epics und User Stories unterteilt und implementiert haben.
  - `TaskFlowEngineering-Endabgabe-Testsuite.pdf`: Beschreibt unser Testkonzept und belegt die durchgeführten Qualitätssicherungsmaßnahmen.
  - `TaskFlowEngineering-Endabgabe-Glossar.pdf`: Eine Übersicht über alle projektspezifischen Fachbegriffe und Definitionen.

- **`/Projektphase 1` bis `/Projektphase 6` (in der obersten `/docs/`-Ebene):**
  - Diese Ordner dienen als Archiv des Entwicklungsfortschritts. Sie enthalten alle historischen Abgaben, Zwischenstände, Risikoanalysen und Lasten-/Pflichtenhefte der jeweiligen Meilensteine.

---

### Zusammenfassung & Erste Schritte

Zusammenfassend lässt sich sagen: **Backend** und **Frontend** enthalten den jeweiligen ausführbaren Programmcode samt der dazugehörigen Tests. Das **Docs**-Verzeichnis bündelt hingegen das gesamte theoretische Wissen und alle Anleitungen.

**Der beste Startpunkt:** 
Bitte navigieren Sie für die Einrichtung des Projekts direkt in den Ordner `/docs/`. Suchen Sie dort nach der **Installationsanleitung** – diese führt Sie strukturiert durch den gesamten Startprozess der Anwendung.
