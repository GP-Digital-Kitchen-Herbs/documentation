---
title: Grove - Moisture Sensor
tags:
 - Feuchtigkeit
 - Sensor
---

# Grove - Moisture Sensor

## Funktion
Bestimmt die Feuchtigkeit der Erde.

## Nutzung im Projekt
Kann genutzt werden um festzustellen, wann die Pflanze wieder gegossen werden muss.

## Hinweise
- Wird an einem **analogen** Port angeschlossen.

## Code
[Code-Beispiel](https://github.com/aletutto/digital-kitchen-herbs/blob/master/moisture/moisture_to_thingsboard.py)

[Link zur offiziellen Dokumentation](http://wiki.seeedstudio.com/Grove-Moisture_Sensor/#play-with-raspberry-piwith-grovepi_plus)

## Interpretation der Daten
Laut dem Seeedstudio-Wiki (siehe Link zur offiziellen Dokumentation) bedeuten die Werte des Sensors folgendes:

| Min | Typ | Max | Condition                  |
|-----|-----|-----|----------------------------|
| 0   | 0   | 0   | Sensor an der Luft         |
| 0   | 20  | 300 | Sensor im trockenden Boden |
| 300 | 580 | 700 | Sensor im feuchten Boden   |
| 700 | 940 | 980 | Sensor im Wasser           |

