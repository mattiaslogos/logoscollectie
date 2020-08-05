+++
title = "Axe3"
description = ""
tags = [
    "midi",
    "interface",
    "bewegingsdetectie"
]
date = "2007-01-01"
dates = "2007"
categories = [
    "digitaal",
    "elektronisch"
]
alfabetisch = ["A"
]
menu = "main"
summary = "<a href='/logoscollectie/catalogus/2007/axe3'><img src='/logoscollectie/catalogus/img/Axe3/Axe3-thumb.jpg'></a>Axe3 is een interface met twee acceleratiesensoren. Deze zijn elk met een kabel met de midimodule verbonden. Zowel de info over de acceleratie in twee assen als de tilt-informatie (de hoek ten opzichte van een horizontaal oppervlak), wordt in midi omgezet en naar een computer of rechtstreeks naar een midi-instrument gestuurd."
+++

# Axe3

![alt text][afb1]
[afb1]: /logoscollectie/catalogus/img/Axe3/Axe3-thumb.jpg "Axe3"

**Collectie**
Stichting Logos

**Titel**
Axe3

**Productie**
Gebouwd door Godfried-Willem Raes te Gent

**Datering**
2007

**Afmetingen**<br>
*Module:*<br>
H x B x L: 4 cm x 11 cm x 18 cm

*Sensoren zonder kabel:*<br>
H x B x L: 2 cm x 3 cm x 6 cm

**Classificatie**
Categorie 55

**Inventarisnummer**
LOGOS

#### Beschrijving van het instrument
Axe3 is de vernieuwde versie van Axe2 (zie catalogus). Ook deze interface is gebouwd rond de chips ADXL202 (Analog Devices). Raes gebruikt voor Axe3 een development board van Coridiumcorp met een ARM microprocessor (LPC2103) om de data van de chips in een midi-stroom om te zetten.
De twee sensoren (chips)zijn elk in de plastic behuizing van een 3-prong Euroconnector gelijmd en gelabeld met R en L (rechts en links). De kabel leidt naar de twee DIN-connectoren op de midi-module. Deze is gebouwd op een gaatjesprint die in een metalen u-profiel met vier rubberen pootjes is gemonteerd. Aan de andere smalle kant van de DIN-connectoren zien we de connector voor het netsnoer (met daarachter de voeding) en de midi-uitgang. Op de gaatjesprint is het reeds aangehaalde development board gevezen. Aan de midi-uitgang zien we 8 DIP-schakelaars. Het midi-kanaal wordt bepaald met schakelaars 5 tot en met 8. Het programma kan worden bepaald met de schakelaars 1 tot en met 4. De elektrische schema’s vind je in de bijlage.

#### Speelwijze, repertoire en inzet in producties
In elke hand wordt een sensor vastgehouden. Door deze gecontroleerd te bewegen wordt de gewenste midi-stroom opgewekt. De sensoren kunnen eventueel ook aan de benen worden vastgemaakt.

Axe3 werd gebruikt in volgende composities:
- Godfried-Willem Raes "Flexes" (2002/2007)
- Godfried-Willem Raes "Handy" (2007)
- Kristof Lauwers "Tilt!" (2007)

#### Opbouw van het instrument/installatie
Volgende programma’s zijn in de firmware aanwezig:
- Program 0: Data rate 129 bytes/s Midi encoding using key aftertouch commands. The high nibble of the msb holds the data channel (0= x right, 1=y right, 2= x left, 3=x right).
- Program 1: Data rate 400 bytes/s. Encoding as above
- Program 2: Using the sensors for direct control of our <Klung> robot.
- Program 3: Using the sensors for direct control of our <Flex> robot
- Program 4: reserved
- Program 5: reserved
- Program 6: reserved
- Program 7: debug mode. The data are sent to the connected PC via the USB port. Used for monitoring and adjustment.

#### Inscripties
- R *(3x)*
- L *(3x)*
- AXE3

#### Staat van het instrument
In werkende staat

#### Historiek van het instrument
Andere interfaces die werken met soortgelijke technologie (acceleratiesensoren) zijn Ei (1995) en Axe2 (2003). De verschillende generaties interfaces zijn het resultaat van aanpassingen naar de nieuwe technologische mogelijkheden.

#### Problematieken
/

#### Media
##### Afbeeldingen
{{< load-photoswipe >}}
{{< gallery dir="/catalogus/img/Axe3" />}}

