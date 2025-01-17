# Technologie auswahl

## Einleitung
In diesem Dokument vergleichen wir die Vor- und Nachteile der Eigenentwicklung einer Website mit der Nutzung von Tools wie WordPress. Ziel ist es, die beste Methode zur Umsetzung einer professionellen Website für ein Nagelstudio innerhalb von 5 Wochen zu identifizieren. Die Website soll Terminvereinbarungen ermöglichen und mit dem Kalender des Inhabers synchronisiert werden.
Tools wie WordPress vereinfachen die Entwicklung von Websiten. Mit Plugins kann man auch gewissen Dienste, wie das automatische Senden von E-Mails oder Nachrichten hinzufügen. Somit ist es nicht mehr nötig einen Code mit dieeser Logik zu schreiben. Jedoch haben diese Tools ihre vor- und Nachteile.

# Vergleiche
## Eigenes Programmieren mit HTML, JS und CSS

### Vorteile
* Volle Kontrolle: Design und Funktionen können individuell erstellt werden.

* Optimale Performance: Minimaler und sauberer Code sorgt für schnelle Ladezeiten.

* Keine Abhängigkeiten: Kein Risiko durch unsichere Drittanbieter-Plugins.
* Übersicht: Man was welcher Code für was Zuständig ist und man kennt die technische Funktionalitäten.


### Nachteile
* Zeitintensiv: Entwicklung und Testen nehmen viel Zeit in Anspruch.

* Responsives Design: Muss manuell erstellt werden und fordert wiedrum Zeit.

* Wartung: Anpassungen und Updates müssen selbst durchgeführt werden.
* Keine sofortigen Module: Funktionen wie Kalendersynchronisation müssen eigenständig programmiert werden.

## Nutzwertanalyse Websitebuilder oder Eigenentwicklung

Punktevergabe: 1 - 10

| Kriterium                  | Gewichtung | Websitebuilder wie WordPress | Eigenentwicklung  
| -------------------------- | ---------- | ------------------ | ------------------------- |  
| **Zeitaufwand**            | 45%        |   9                |  4                        | 
| **Flexibilität**           | 30%        |   5                 |     7                    | 
| **Benutzerfreundlichkeit** | 15%        |    8                |     6                    |  
| **Performance**            | 10%        |      6              |       7                  |  
| **Gesamtpunkte**           | 100%       | **7.35**           | **5.5**                   |  


### Bewertung der Kriterien

- **Zeitaufwand (45%)**: Da wir nur 5 Wochen habe eine ganze Website mit logik implementieren, ist Zeit das wichtigste. Produkte wie WordPress bietet vorgefertigte Tools, die die Entwicklung erheblich beschleunigen. Bei Eigenentwicklung ist der Aufwand deutlich höher.
- **Flexibilität (30%)**: Eigenentwicklung bietet nahezu unbegrenzte Anpassungsmöglichkeiten, während WordPress durch Plugins und Themes eingeschränkt ist.
- **Benutzerfreundlichkeit (15%)**: Websitebuilder erleichtert die Bedienung durch fertige Oberflächen und eine breite Community.
- **Performance (10%)**: Eigenentwicklung erzielt durch optimierten Code eine bessere Performance als Tools mit Plugins

**Ergebnis**: Websitebuilder ist die bevorzugte Wahl für dieses Projekt, da es eine schnellere Umsetzung möglich ist.

# Websitebuilder
## Auswahl
Mit der vorherigen Nutzwertanalyse haben wir uns, auf grund der Zeit, entschieden einen Websitebuilder zu nehmen, statt eine Website mit HTML, CSS und JS selber zu implementieren. Nun stellt sich die Fragen welchen Websitebuilder nehmen wir. Es gibt sehr viele. Bekannte sind WordPress, Wix etc. Jedes Tool braucht unterschiedliches Vorwissen und Skill. Wir versuchen den Bestmöglichen Builder zu nehmen, der für unsere Voraussetzung (Kalender, Modernes Design) umzusetzen.

## Nutzwertanalyse Websitebuilder
Auswahl: WordPress, Odoo Studio, Wix, Squarespace

### WordPress

#### Vorteile

- **Schnelle Umsetzung**: Fertige Themes und Plugins beschleunigen die Entwicklung.
- **Einfache Integration von Funktionen**: Plugins erleichtern Terminbuchungen und Kalendersynchronisation.
- **Responsives Design**: Viele Desginmodule sind mobilfreundlich und sehen modern aus.
- **Große Community**: Es gibt eine grosse community und viele Tutorials.
- **Docker-Kompatibilität**: Aus der Website kann ein Docker-Image erstellt werden. 

#### Nachteile

- **Abhängigkeit von Plugins**: Sicherheitsrisiken und Inkompatibilitäten möglich.
- **Leistungsprobleme**: Grosse Plugins und Themes können die Performance beeinträchtigen.
- **Regelmäßige Wartung**: Updates sind notwendig, um Sicherheitsrisiken zu minimieren.
- **Kosten für Premium-Plugins/Themes**: Zusätzliche Kosten können durch kostenpflichtige Erweiterungen entstehen.

### Odoo Studio

#### Vorteile

- **Integrierte Lösung**: Perfekt mit Odoo-Modulen wie CRM, Buchhaltung und Lagerverwaltung verknüpft.
- **Kalenderintegration**: Synchronisation mit internen Odoo-Kalendern und CRM-Daten möglich.
- **Geschäftsorientiert**: Ideal für Unternehmen, die ihre Prozesse digitalisieren möchten.

#### Nachteile

- **Komplexität**: Erfordert viel Wissen von Odoo Studio.
- **Weniger Designfreiheit**: Fokus liegt mehr auf Funktionalität als auf Design.
- **Kosten**: Die Enterprise-Version ist kostenpflichtig.

### Wix

#### Vorteile

- **Benutzerfreundlich**: Drag-and-Drop-Editor, schnelle Entwicklung.
- **Kalenderintegration**: Eingebaute Buchungssysteme wie Wix Bookings.

#### Nachteile

- **Weniger Flexibilität**: Eingeschränkte Anpassungsmöglichkeiten.
- **Kosten**: Premium-Pläne erforderlich, um Werbung zu entfernen.
- **Performance**: Kann bei größeren Websites langsamer werden.

### Squarespace

#### Vorteile

- **Designfokus**: Hochwertige Vorlagen, gut für kreative Websiten.
- **Eingebaute Buchungsfunktionen**: Squarespace Scheduling.
- **Benutzerfreundlich**: Einfach zu bedienen.

#### Nachteile

- **Kosten**: Teurer als andere Plattformen.
- **Weniger Flexibilität**: Begrenzte Anpassungen möglich.

## Nutzwertanalyse

| Kriterium                  | Gewichtung | WordPress (Punkte) | Odoo Studio (Punkte) | Wix (Punkte) | Squarespace (Punkte) |
|--------------------------- |----------- |--------------------|----------------------|--------------|----------------------|
| **Zeitaufwand**            | 30%        | 9                  | 6                    | 8            | 8                    |
| **Flexibilität**           | 25%        | 8                  | 7                    | 6            | 6                    |
| **Benutzerfreundlichkeit** | 20%        | 8                  | 6                    | 9            | 8                    |
| **Kosten**                 | 15%        | 8                  | 6                    | 7            | 6                    |
| **Kalenderintegration**    | 10%        | 9                  | 9                    | 8            | 8                    |
| **Gesamtpunkte**           | 100%       | **8.3**            | **6.9**              | **7.7**      | **7.3**              |


### Bewertung der Ergebnisse
- **WordPress**: Beste Wahl für Flexibilität, es hat eine breite Community und Erweiterbarkeit. Optimal für eine Website mit kreativem Design und ist optimal für unsere anforderungen. Dazu ist WordPress Dockerkompatibel.
- **Odoo Studio**: Ist für unsere Anforderungen nicht geeignet.
- **Wix**: Einfach nutzbar, aber die Kreativität und flexibilität ist eingeschränkt.
- **Squarespace**: Ideal für Designfokus, aber weniger anpassbar und kostet viel.

## Fazit
Für das geplante Projekt ist **WordPress** die beste Wahl, da es eine perfekte Balance zwischen Flexibilität, einfacher Kalendersynchronisation und Benutzerfreundlichkeit bietet. Ebenfalls ist mit WordPress die Dockerisierung der Website möglich. Dies ist wichtig um das Produkt auf einem Lokalen Server zu hosten.

