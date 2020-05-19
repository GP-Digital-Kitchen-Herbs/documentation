---
title: Start
author: Johannes
---
<div style="display: flex; justify-content: center;">
    <img src="hero.svg" width="50%">
</div>
---

# GPA: Digital Kitchen Herbs - Nachschlagewerk

## Allgemeines

An dieser Stelle soll eine Art Nachschlagewerk für das GPA Digital Kitchen Herbs entstehen.
Durch eine sinnvolle Aufbereitung soll es möglich sein, Quellen und eigene Dokumente schnell nachzuschlagen.

Für die Literatur werden Beispielsweise folgende Informatioen (wenn möglich) festgehalten:

- Zusammenfassung
- Wichtigste Informationen
- Weitere Links
- Schlagworte

Dokumente und Informationen können über die Suche oder über die Tags-Seite gefunden werden.

## Historie

### Innovation

```mermaid
graph TB
    innovation["Innovation"]
    five-forces["5 Forces"]
    high-five["High Five"]
    interviews["Erste Interviews durchgeführt"]
    experiences["Eigene Erfahrungen gesammelt"]
    questionaire["Fragebogen-Interviews (54 Stück)"]
    evaluation["Auswertung der Fragebögen"]
    persona-canvas["Persona Canvas erstellt"]
    requirements["Vision Brainstorming (Anforderungen gesammelt)"]
    req-assessment["Bewertung und Priorisierung der Anforderungen"]
    solutions["Brainstorming für Lösungsideen"]
    i-three["Bewertung und Priorisierung von Ideen nach I³"]
    
    innovation --> five-forces
    five-forces --> high-five
    innovation --> interviews
    innovation --> experiences
    interviews --> questionaire
    experiences --> questionaire
    questionaire --> high-five
    questionaire --> evaluation
    high-five --> persona-canvas
    evaluation --> persona-canvas
    persona-canvas --> requirements
    requirements --> req-assessment
    req-assessment --> solutions
    solutions --> i-three
```

### Research & Technology

```mermaid
graph TB
    research["Research & Technology"]
    kraeuter["Kräuter Research (Ideale Werte zum Wachsen)"]
    wiki["Wiki mit aktuellem Wissenststand"]
    prototype["Prototyp für das Monitoring"]
    sensors["Sinnvolle Sensoren bestimmt"]
    testplan["Testplan Sensoren Werte und Kräuter (On Hold)"]
    light["Research zu besseren Lichtsensoren"]
    watering["Research zu Bewässerungsmethoden"]

    research --> kraeuter
    research --> wiki
    research --> prototype
    kraeuter --> testplan
    kraeuter --> sensors
    sensors --> testplan
    sensors --> light
    testplan --> light
    testplan --> watering
```
