+++
title = "Polymetronoom"
description = ""
tags = [ "midi", "printerpoort/centronics"
]
date = "1994-01-01"
dates = [ "2012", "1994" ]
categories = [ "elektronisch", "digitaal"
]
alfabetisch = [ "P"
]
menu = "main"
summary = "<a href='/logoscollectie/catalogus/1994/polymetronoom'><img src='/logoscollectie/catalogus/img/Polymetronoom/20200702_0019_02-thumb.jpg'></a>Polymetronoom is gebouwd om muzikanten te helpen bij het spelen van combinaties van complexe tempi. Polymetronoom bestaat uit acht dirigeermodules met elke een automatisch bewegend dirigentstokje en een lichtje dat pinkt op het geprogrammeerde tempo. De dirigeermodules kunnen onafhankelijk van elkaar verschillende tempi aangeven. De polymetronoom is computergestuurd."
+++


# Polymetronoom

![alt text][afb1]
[afb1]: /logoscollectie/catalogus/img/Polymetronoom/20200702_0019_02-thumb.jpg "Polymetronoom"

**Collectie** 
Stichting Logos

**Titel**
Polymetronoom

**Productie**
Gebouwd door Godfried-Willem Raes te Gent

**Datering**
1994 / 2012

**Afmetingen**<br>
*8 Metronoommodules:*<br>
H x B x L: 12 cm x 3 cm x 25 cm<br>

*Midisturing:*<br>
H x B x L: 10 cm x 13 cm x 17 cm

**Classificatie**
Categorie 0 (accessoires)

**Inventarisnummer**
LOGOS 

#### Beschrijving van het instrument
De polymetronoom stuurt acht programmeerbare mechanische dirigeermodules aan. Deze zijn telkens gebouwd op een printplaat. Onderaan de printplaat is een vleugelmoer gemonteerd waarmee de dirigeermodule op een statief kan worden geplaatst. Het tempo wordt aangegeven met behulp van een op – en neergaand metalen stokje en een pinkend lichtje (LED). Het stokje wordt via een scharnierpunt met een elektromagneet bewogen. Deze wordt geschakeld met de mosfet (IRF540) die naast de magneet op het koelplaatje is geplaatst. De beweging van het stokje wordt begrensd door twee viltjes, die tevens ongewenste bijgeluiden dempen. In de hoek bovenaan zien we het lampje. 
Via de DIN-plug naast de vleugelmoer wordt het commandosignaal (stroom) door gegeven. 

Alle acht de dirigeermodules zijn met behulp van een DIN-kabel met sturingsmodule verbonden. Deze module werd oorspronkelijk (1994) via een centronics printerpoort gestuurd. Deze schakeling zien we op de onderste printplaat van de sturingsmodule. In 2012 paste Raes de sturingsmodule aan zodat deze ook met midi kon worden aangestuurd. Deze nieuwe printplaat die verbonden is met de voeding en centronicspoort werd met vier vijsjes op de oorspronkelijke sturingsmodule gemonteerd.

De midi-ingang bevindt zich in het midden van de bovenste printplaat (aan de optocoupler en de hub). De twee andere pluggen zijn midi-thru. De zes rechtopstaande pinnetjes dienen voor het programmeren van de microprocessor (PIC18F2525) die de midicode naar de code voor de printerpoort omzet.

Je vindt de firmware, elektrische schema’s en pcb’s in de bijlage.

#### Speelwijze, repertoire en inzet in producties
De polymetronoom werd onder andere gebruikt voor de composities *Shifts*, *Spring'94* en *Fall'95* van Godfried-Willem Raes.

#### Opbouw van het instrument/installatie
De midi implementatie voorziet in twee besturingswijzen, waarbij voor elke besturingswijze en voor elke metronoom een afzonderlijke controller wordt gebruikt:

- Low level controle:
Hierbij worden alle pulsen nodig voor het omklappen van de metronomen via het zendende computerprogramma en de midi output ervan gestuurd: Note-On / Note-Off kommandos 36 tot 43 sturen de metronomen 1 tot 8. De velocity waarde is 0 (voor metronoomspoel onbekrachtigd) of 1-127 voor bekrachtiging van de metronoomspoel.
- Periodiciteits controle:
Hierbij worden de gewenste tempi, via controllers naar de verschillende metronomen gestuurd. Hierbij worden de controllers 36 tot 43 gebruikt voor het programmeren van het MSB van de periodetijd, terwijl kontrollers 68 tot 75 ingezet worden voor het programmeren van het LSB voor de gewenste periodetijd. Op deze wijze kon een resolutie van 14 bits worden bereikt.

Controller 66 schakelt alle metronomen uit of aan terwijl controller 65 kan worden gebruikt voor synchronisatie bij de start, wanneer verschillende tempi werden geprogrammeerd.

#### Inscripties
/

#### Staat van het instrument
In werkende staat

#### Historiek van het instrument
Reeds in 1968 bouwde Raes een automatische dirigent voor de uitvoering van zijn compositie Logos 3/5. Zie Automatische dirigent in de catalogus.
De polymetronoom van 1994 werd in 2012 herzien. Raes bouwde een soort van adapter waardoor de metronoom ook met midi kan worden aangestuurd. Ook de viltjes die de dirigeerstokjes begrenzen, werden in 2012 aangebracht.

#### Problematieken
/

#### Media
{{< load-photoswipe >}}
{{< gallery dir="/catalogus/img/Polymetronoom" />}}

##### pdf-bestanden
[Firmware PIC midiboard](/logoscollectie/catalogus/pdf/Polymetronoom/Firmware%20PIC%20midiboard.pdf)

