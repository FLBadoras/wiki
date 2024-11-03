---
short_name: factory
title: Fabrik
layout: default

table:
  headers:
    - Material
    - Rohstoffkosten
    - Fundort Rohstoff
    - Produktionsdauer
  objects:
    - attributes:
        - Plastikplatte
        - 10 Plastik
        - Schrottplatz, Korallen
        - 10 Sekunden/Stück
    - attributes:
        - Holzplanke
        - 10 Eichenbaumstamm
        - Farmwelt
        - 20 Sekunden/Stück
    - attributes:
        - Stoff
        - 10 Fäden
        - Farmwelt, Schrottplatz, Dungeons
        - 30 Sekunden/Stück
    - attributes:
        - Aluminiumplatte
        - 20 reines Aluminium
        - Mine, Herstellung
        - 40 Sekunden/Stück
    - attributes:
        - Kupferdraht
        - 15 Kupferbarren
        - Schrottplatz, Korallen
        - 30 Sekunden/Stück
    - attributes:
        - Bronzelegierung
        - 5 Bronzebarren
        - Farmwelt, Herstellung
        - 50 Sekunden/Stück
---
# {{ page.title }}

Die Fabrik dient als Herstellungsort für Materialien und [Blueprints](/systems/blueprints). Außerdem
befindet sich die [Möbelmanufaktur](/systems/furnituremanufacturer) und ein Vorarbeiter auf dem Gelände,
bei dem man Lizenzen erwerben und Kassiterit aus der [Mine](/jobs/mine) verkaufen kann.

## Vorarbeiter

Der Vorarbeiter steht am Eingang der Herstellungshalle. Dort kannst du Lizenzen
für die Produktion von Materialien erwerben. Klicke auf die jeweilige Lizenz,
um die geforderten Rohstoffe abzugeben. Du erhältst für jede erworbene Lizenz
eine zufällige Bezahlung vom NPC.

Du kannst bei ihm auch Kassiterit aus der [Mine](/jobs/mine) verkaufen. Dafür musst du
das Kassiterit vorher in einer Werkbank allerdings zu Kassiteritblöcken
verarbeiten. Im Durchschnitt erhältst du von ihm 9 Euro pro Kassiteritblock,
wobei der genaue Preis tagesabhängig ist und stark schwankt.
_Tipp: Es lohnt sich also, die Preise im Blick zu behalten und zum richtigen_
_Zeitpunkt zu verkaufen, sofern du nicht auf das schnelle Geld angewiesen bist._

## Materialien

Für die Herstellung von Materialien (Kupferdraht, Aluminiumplatten, ...)
benötigt man eine Lizenz. Diese erhält man beim Vorarbeiter der Fabrik.

Nach dem Erwerb der Lizenzen kann man die entsprechenden Materialien an der
Bedientafel in der Produktionshalle herstellen. Dafür benötigt man Rohstoffe,
die man auf unterschiedliche Art und Weise erhält.

{% include lists_table.md %}

_Übrigens: Bei der Entnahme von Materialien erhält man auch eine bestimmte Menge_
_Erfahrungspunkte gutgeschrieben._
