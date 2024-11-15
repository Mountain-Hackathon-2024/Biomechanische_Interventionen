# Biomechanische_Interventionen
Das ist ein Repo für das Projekt "Biomechanische Interventionen"

## Bitte untenstehende Angaben ausfüllen:
### Bereich: 
Softwareentwicklung
### Projekt-Titel: 
Biomechanische Interventionen
### Projekt-Ziel: 
Die Entwicklung eines digitalen Zwillings zur Speicherung und Visualisierung individueller, biomechanischer Daten und eines maschinellen Lernmodells, um personalisierte Interventionen für Patienten zu optimieren und Beschwerden am Bewegungsapparat zu reduzieren.

### Projekt-Beschreibung:
swissbiomechanics ist ein führendes Unternehmen auf dem Gebiet der Entwicklung und Herstellung maßgeschneiderter orthopädischer Lösungen und biomechanischer Produkte. Als Spin-off der ETH Zürich verbindet das Unternehmen traditionelle Handwerkskunst mit modernster Technologie, um individuelle Lösungen zur Verbesserung der menschlichen Bewegungsfähigkeit zu schaffen. Zu ihrem Produktsortiment zählen maßgefertigte orthopädische Einlagen, Schuhe, Skischuhe und Golfschuhe, die mittels detaillierter biomechanischer Analysen wie 3D-Lauf- und Ganganalysen exakt auf die Bedürfnisse der Kunden abgestimmt werden. Das Unternehmen plant den Einsatz von Künstlicher Intelligenz und maschinellem Lernen, um biomechanische Messungen optimal zu nutzen und die Behandlung von Beschwerden am Bewegungsapparat weiter zu verfeinern. Diese innovativen Technologien sollen dazu beitragen, eine Vielzahl individueller Daten – wie Fußform, Fußdruck, Bewegungsdaten (Kinematik) und Belastungsdaten (Kinetik) – in einem digitalen Zwilling zu speichern. Dieser digitale Zwilling ermöglicht eine präzise, individuelle Analyse sowie das Monitoring biomechanischer Risikofaktoren.
Basierend auf den gesammelten Daten und den spezifischen Beschwerden der Patienten entwickelt swissbiomechanics personalisierte Interventionen, beispielsweise durch Anpassungen der Fußkorrektur mittels maßgefertigter Einlagen oder durch Modifikationen der Struktur und Form der Zwischensohle beim Schuh. Diese personalisierten Maßnahmen zielen darauf ab, biomechanische Risikofaktoren zu reduzieren und somit die Beschwerden zu lindern. Nach einer definierten Tragedauer von etwa sechs bis acht Wochen werden erneute Messungen durchgeführt, um die Wirksamkeit der Maßnahme zu bewerten. Durch den Vergleich der Ausgangsmessungen, der Messungen während der Intervention und der Messungen nach der Tragedauer können Veränderungen der biomechanischen Parameter und des Schmerzzustands objektiv beurteilt werden. Dieser Feedback-Loop soll durch den Einsatz von Künstlicher Intelligenz und maschinellem Lernen kontinuierlich optimiert werden, um eine datengetriebene Anpassung der therapeutischen Maßnahmen zu ermöglichen und so eine effektivere Behandlung zu gewährleisten.

### Produkt/ Technologie: 
Zielsetzung: Die Teilnehmer sollen ein technisches Konzept entwickeln, das die Erzeugung eines digitalen Zwillings zur Abbildung individueller biomechanischer Daten ermöglicht und ein maschinelles Lernmodell implementiert, das die datengetriebene Optimierung von Interventionen (Masseinlagen und Schuhen) unterstützt. Der Fokus liegt auf der Integration und dem Management von Patientendaten (biomechanische Daten) sowie der Verbesserung des Feedback-Loops zur Reduktion von Beschwerden.

### Fragestellungen und Anforderungen:
1. Digitaler Zwilling: Datenspeicherung und Risikoprofil
  - Aufgabe: Entwickeln Sie ein Konzept zur Speicherung und Verwaltung individueller biomechanischer Daten in Form eines digitalen Zwillings. Dieser soll verschiedene Datenformate integrieren, wie beispielsweise Fussform, Fussdruck, Bewegungsdaten (Kinematik) und Belastungsdaten (Kinetik).
  - Technische Anforderungen:
    - Datenstruktur: Definieren Sie eine skalierbare Datenarchitektur, die zukünftige Erweiterungen ermöglicht (z. B. durch neue Sensoren oder Datenquellen).
    - Interoperabilität: Der Datenpool muss offen gestaltet sein, um die Integration neuer Datenformate und -quellen zu ermöglichen.
    - Risikoprofil: Der digitale Zwilling soll ein individuelles Risikoprofil erstellen, das basierend auf den gespeicherten Daten mögliche biomechanische Risikofaktoren erkennt und zur Auswahl geeigneter Interventionen dient. 
  - Erwartete Ergebnisse: Vorschläge zur technischen Implementierung des digitalen Zwillings, einschließlich Datenbankstruktur, APIs zur Dateneingabe und -ausgabe sowie Ansätze oder konkrete Umsetzungen zur Visualisierung des Risikoprofils.

2. Maschinelles Lernen: Feedback-Loop und datengetriebene Optimierung
  - Aufgabe: Entwickeln Sie ein maschinelles Lernmodell, das den Feedback-Loop zwischen Intervention (Massprodukt) und Schmerzzustand des Patienten optimiert (Auch Simulationen können gemacht werden). Ziel ist es, auf Basis der gesammelten Daten individuelle Anpassungen vorzunehmen, um die bestmögliche individuelle Intervention zu finden.
  - Technische Anforderungen:
    - Modellwahl: Schlagen Sie geeignete Algorithmen vor (z. B. überwachte oder verstärkende Lernverfahren) und begründen Sie Ihre Wahl unter Berücksichtigung der vorliegenden Daten und Zielsetzungen.
    - Datenverarbeitung: Entwickeln Sie eine Pipeline zur Datenvorverarbeitung und zum Feature-Engineering, die verschiedene Datenquellen integriert und die Datenqualität für das Modell optimiert.
    - Feedback-Loop: Implementieren Sie eine Methode, die kontinuierlich neue Daten aus den Messungen nach der Intervention einbezieht und das Modell fortlaufend anpasst, um personalisierte Empfehlungen zu geben.
  - Erwartete Ergebnisse: Vorschläge zur Modellarchitektur, Datentransformationsmethoden, Kriterien zur Evaluation der Modellleistung sowie Ansätze zur Verbesserung der Feedback-Schleife.

### Anforderungen / Praktische Umsetzung:
- Datenbasis: Nutzen Sie die bereitgestellten Daten, um erste Modelle und Konzepte zu entwickeln und zu testen. Diese Daten sollen als Grundlage dienen, um Prototypen zu erstellen und die Machbarkeit der vorgeschlagenen Lösungen zu evaluieren.
- Präsentation: Die Ergebnisse sollen in Form eines technischen Konzepts präsentiert werden, einschließlich Mock-ups, Architekturskizzen und ersten Modellergebnissen. Ziel ist es, ein nachvollziehbares und skalierbares Konzept zu entwickeln, das in einer realen Umgebung angewendet werden kann.

### Bewertungskriterien/Erwartungen:
1. Innovationsgrad: Wie neuartig und kreativ sind die vorgeschlagenen Lösungen? Ist die Lösung zukunftsorientiert (Quantencomputing)
2. Technische Machbarkeit: Wie realistisch ist die Umsetzung der vorgeschlagenen Architektur und Modelle? Wie zeitnah kann dies umgesetzt werden?
3. Skalierbarkeit und Flexibilität: Kann die Lösung an unterschiedliche Datenquellen und neue Anforderungen angepasst werden?
4. Kosten: Wie hoch fallen die Kosten in etwa aus?
5. Wirkungspotenzial: Inwiefern trägt die Lösung dazu bei, die Beschwerden der Patienten zu lindern und die Qualität der Interventionen zu verbessern?
Hintergrund: Der Einsatz digitaler Zwillinge und maschineller Lernverfahren bietet ein großes Potenzial, die Personalisierung und Wirksamkeit biomechanischer Interventionen zu verbessern. Durch die Integration verschiedener Datenquellen und die datengetriebene Anpassung der Interventionen können maßgeschneiderte Lösungen entwickelt werden, die die Lebensqualität der Patienten nachhaltig steigern.

Mögliche Quellen / Infos:
Digital twin:
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10295686/ 
https://www.swri.org/technology-today/article/enhancing-the-human-experience 
https://cjme.springeropen.com/articles/10.1186/s10033-024-00998-7

Simulation:
https://www.anybodytech.com/  
https://www.anybodytech.com/industries/sportsbiomechanics/gait-and-running-technique-footwear-assessment-etc/  
https://anyscript.org/ammr/Applications/Mocap/ADL_Gait.html 
 
Plattform für Datenmanagement:
https://www.pryv.com/ 
https://datico.com/de/  
https://www.biot-med.com/  
https://labs.moveup.care/  
https://force8.coach/ 

Folgende Rohdaten werden zur Verfügung gestellt:
- 3D Fussform (stl.)
- Fussdruckmessung (apd.)
- Wearable
- Bewegungsdaten Kinematik (c3d.)
- Bewegungsdaten Kinetik (c3d.)
## Benötigte Hardware:
keine besondere Hardware nötig

## Max. Anzahl Teammitglieder:
## Zuständigkeit:
- Christian Kryenbühl, CEO swissbiomechanics
- Matthias Zäh, head of innovation"
## E-Mail:
- c.kryenbuehl@swissbiomechanics.ch
- m.zaeh@swissbiomechanics.ch "
