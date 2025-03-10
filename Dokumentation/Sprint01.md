# Sprint Dokumentation

## Sprint Übersicht

- **Sprint Nummer:** 1
- **Dauer:** 17.01.2025 bis 24.01.2025 (2 Arbeitstage)
- **Sprint-Ziel:** Definierung der Projektanforderungen, Recherche geeigneter Technologien, Erstellung von zwei Designentwürfen und Durchführung des ersten Kundenkontakts zur Sammlung von Kundenbedürfnissen sowie Erstellung eines ersten Prototyps.

---

## Sprint Planning

### Sprint-Ziel definieren

*Definierung der Projektanforderungen, Recherche und Evaluierung geeigneter Technologien, Erstellung von zwei Designentwürfen, Vergleich mit Konkurrenzprodukten, erster Kundenkontakt zur Präsentation der Ergebnisse und Sammlung von Kundenbedürfnissen sowie Erstellung eines ersten Prototyps.*

### Ausgewählte Product Backlog Items

| ID  | Titel                                                 | Beschreibung                                                                                                                                                                                    | Aufwand   | Verantwortlich |
| --- | ----------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | -------------- |
| 1   | Anforderungen definieren & Technologien recherchieren | Detaillierte Festlegung der Projektanforderungen, Recherche geeigneter Technologien und Bewertung der Umsetzungsmöglichkeiten.                                                                  | 3 Stunden | Pascal         |
| 2   | Design erstellen & Konkurrenzvergleich                | Erstellung von zwei Designentwürfen, Vergleich dieser mit Wettbewerbsprodukten und Optimierung der Designs.                                                                                     | 3 Stunden | Keanu          |
| 3   | Vorbereitung Kundenkontakt                            | Gesammelte Informationen evaluieren und zur Präsentation vorbereiten.                                                                                                                           | 2 Stunden | Keanu & Pascal |
| 4   | Erster Kundenkontakt & Prototyp erstellen             | Durchführung des ersten Kundenmeetings, Präsentation der Ergebnisse, Erfassung von Kundenbedürfnissen und Integration in die Planung, sowie Erstellung eines ersten Prototyps inkl. Fotografie. | 5 Stunden | Keanu & Pascal |

---

## Daily Scrum

### 17.01.2025

- **Was wurde heute gemacht:**
    - Heute wurde eine Recherche und Bewertung von verschiedenen Umsetzungsmöglichkeiten gemacht.
  - Sprint-Palnung wurde erstellt.
  - Bewertung von Umsetzungsmöglichkeiten
  - Über die Technologie WordPress informiert.
  - Konkurenzwebsiten angeschaut
  - Technologieauswahl-Dokumentation erstellt
  - WordPress dockerisiert
  - Den Container auf einem Server gestartet.
  - Login-Erstellt
- **Blocker:**
  - Weiteres vorgehen nicht möglich, da wir den Kunden auf die ersten Entwürfe Informieren müssen.

### 24.01.2025

- **Was wurde das letzte Mal gemacht:**
  -  Sprint-Palnung wurde erstellt.
  - Bewertung von Umsetzungsmöglichkeiten
  - Über die Technologie WordPress informiert.
  - Konkurenzwebsiten angeschaut
  - Technologieauswahl-Dokumentation erstellt
  - WordPress dockerisiert
  - Den Container auf einem Server gestartet.
  - Login-Erstellt
- **Was wird heute gemacht:**
  - Heute wird die Präsentation für den Kunden erstellt.
  - Kontakt mit dem Kunden aufgenommen und die Präsentation vorgestellt.
  - Feedback vom Kunden in die Planung migrieren.
  - Beginn Implementation vom Produkt
- **Blocker:**


---

## Entwicklungsarbeit

**17.01.2025:** 
Mit Googlerecherche und Vergleichungen von verschiedenen Aspekten haben wir eine Detailierte Entscheidungsauwahl für die Technologie erstellt.
  - [Technologieauswahl-Dokumentation](https://github.com/Kurizaki/Nagelstudio-Naildesign-Nataliya/blob/main/Dokumentation/Technologie.md)

Wir haben uns auf dem Server vom Inhaber mit Adminrecht verbunden. Darauf haben wir das Dockerfile auf den Server kopiert und den Container mit WordPress gestartet. Eine Herausforderung war das Erstellen des Containers auf dem Server mittels ssh. Wir mussten das File vom lokalen Computer auf den Server laden und schliesslich den container starten. Dies erforderte Zeit, wurde aber jedoch erfolgreich umgesetzt.
  - [Dockerfile](https://github.com/Kurizaki/Nagelstudio-Naildesign-Nataliya/blob/main/DockerConnection/docker-compose.yml)

**24.01.2025:** Heute haben wir die Mock-Ups fertiggestellt. Dazu haben wir ebenfalls mit dem Kunden den Kontakt aufgenommen und die Präsentation vorgestellt. Das Protokoll wurde erfasst und schlussendlich wurde das Kundenfeedback in unsere Planung einbezogen. 
 - [Protokoll](https://github.com/Kurizaki/Nagelstudio-Naildesign-Nataliya/blob/main/Gespr%C3%A4chsprotokoll/Protokoll01_24.01.2025.md) 

    
---

## Sprint Review

### Fortschritt der Arbeit

Das Dokumentationsfile für die gewählte Technologie (WordPress) wurde erstellt. Dazu wurde einen Container, auf dem WordPress läuft erstellt und von aussen zugänglich gemacht.
![WordPressLogin](https://github.com/user-attachments/assets/83535705-f6a8-4032-94ec-cb5b25c13f46)

Erstes Mock-Up wurde erstellt

## Sprint Retrospektive

### Was lief gut

-  Das  Aufsetzen der Container auf dem Server lief sehr gut.
- Das Finden der passenden Technologie ging sehr gut.
- Der erste Kontakt mit der Kundin verlief gut. Wir haben uns gegenseitig vorgestellt und sind auf ihre Wünsche eingegangen.
  
  ### Was kann verbessert werden
- Das Protokollieren im Gespräch war chaotisch, wir müssen das Protokoll im nächsten Sprint nochmals überarbeiten. Um Zeit zu sparen, müssen wir uns etwas überlegen, wie wir das protokollieren während des Gesprächs vereinfachen.


### Massnahmen für den nächsten Sprint

- Für das nächste Mal machen wir uns Gedanken, wie wir das Protokollieren während eines Gesprächs vereinfachen, um weniger Zeit für das Überarbeiten zu sparen.
- Für das nächste Gespräch werden wir eine Vorlage für das Protokoll erstellen, indem das wichtigste vordefiniert ist. Dazu werden wir uns die Produktbetreffende Frage überlegen und diese in die Vorlage mit hinein nehmen.
---
