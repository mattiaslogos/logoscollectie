+++
title = "Invisible instrument (BOM en Songbook)"
description = ""
tags = [ "bewegingsdetectie", "interface"
]
date = "1992-01-01"
dates = "1992"
categories = [
    "elektroakoestisch"
]
alfabetisch = [ "I", "B", "S"
]
menu = "main"
summary = "<a href='/logoscollectie/catalogus/1992/invisible_instrument_bom-songbook'><img src='/logoscollectie/catalogus/img/Invisible_Instrument_(BOM-Songbook)/Book_of_moves-thumb.jpg'></a>Na de productie Holosound waarin Raes zijn Invisible Instrument gebruikte, componeerde hij A Book of Moves (1992) en Songbook (1997). Ook bij deze producties wordt dat Invisible Instrument op basis van sonar-technologie gebruikt. Voor deze twee producties bouwde Raes in 1992 nieuwe hardware. De zender en drie ontvangers worden er verbonden met een demodulator die met een computer is verbonden."
+++

# Invisible instrument (BOM en Songbook)

![alt text][afb1]
[afb1]: /logoscollectie/catalogus/img/Invisible_Instrument_(BOM-Songbook)/Book_of_moves-thumb.jpg "Invisible instrument (BOM en Songbook)"

**Collectie**
Stichting Logos

**Titel**
Invisible instrument (BOM en Songbook)

**Productie**
Gebouwd door Godfried-Willem Raes te Gent

**Datering**
1992

**Afmetingen**
*Zender en ontvangers:*
H x B x L: 5,5 cm x 3 cm x 9 cm

*Demodulator:*
H x B x L: 3 cm x 10 cm x 17 cm

*Beugels:*
H x B x L: 10 cm x 11 cm x 2 cm

**Classificatie**
Categorie 55

**Inventarisnummer**
LOGOS

#### Beschrijving van het instrument
Zoals bij het Invisible Instrument dat bij Holosound werd gebruikt wordt ook bij de hardware van Songbook en A Book of Moves gebruik gemaakt van één zender, drie ontvangers en een demodulator die met behulp van een NIDAQ-kaart (National Instrument) met de computer wordt verbonden.
De zender en de twee ontvangers worden op de grond geplaatst in de hoeken van een denkbeeldige tetraëder. De derde zender wordt opgehangen in top van de denkbeeldige tetraëder. De zender en twee ontvangers die op de grond worden geplaatst zijn gebouwd in een metalen behuizing met een schuin oplopende voorkant waar de sensor zich bevindt. De zender heeft in tegenstelling tot de ontvangers drie LED-lampjes op de voorzijde en aan de zijkant een gaatje waarlangs een potmeter kan worden bediend. Zowel de ontvangers als de zender hebben achteraan een DIN-plug voor de voeding en het doorgeven van signalen naar de demodulator. De ontvanger die werd opgehangen met behulp van een beugel ontbreekt. De demodulator is gebouwd op een pcb. Langs de ene korte zijde zien we de DIN-pluggen voor zender en ontvangers. Langs de andere korte zijde zien we de bus van de flatcable die via een adapter naar de NIDAQ-kaart (National Instruments) loopt. Via deze kaart, die aangesloten is op de computer, ontvangt deze de te verwerken data. De elektrische schema´s zijn in het doctoraat van Raes opgenomen (zie bijlage).

Raes legt de werking als volgt uit:
<i>The transducers work on ultrasound and can be tuned to frequencies between 42 and 200kHz. The operating frequency determines the frequency range of the received differential tone-clusters. The lower this frequency, however, the larger the area covered by the system. The higher the frequency, the higher the resolution will be. There is one emitter and three receivers each placed on the vertexes of an imaginary tetrahedron and pointing to its point of gravity. The received signals (carrier plus differential tones) are fed into a high precision analog computer that calculates the Doppler-shifted differential frequencies. A second analog computer takes care of the Fourier transforms and does the conversions from the frequency domain into the time domain. It also does all the required lin-log conversions and the square rooting needed for the power calculation. This analog computer outputs 16 channels of analog data: 3 channels with vectorial movement-amplitude information, 3 channels with vectorial velocity information, 3 channels with non-vectorial power information, 3 channels with vectorial accelleration data and 4 channels carrying the integrated sum of vectorial amplitudes and power signals as well as the momentaneous non-vectorial peak-values of velocity and acceleration. These channels are fed into a dedicated microcomputersystem with a fast multi-channel 12-bit ADC converter. This digital computer is responsible for the conversion of the preprocessed analog data-stream into musical parameters, for the different mappings used in the 'Book of Moves' and for most of the midi-control. Although in the original (first edition of the Book of Moves) version, I used an industrial microcontroller, since the second edition I ported the software to a modified 80486DX platform. This laptop system takes at the same time care of all the midi-processing, including the real-time midi-dumps to whatever midi-gear is connected to the setup. I designed the system to work with a modified Emu Proteus sound module, but I might very well change this in an upcoming version of the piece. All hardware, exception made for the laptop computer, was designed and built by the author who also wrote all of the software, without using any commercially available packages other than the programming language compilers.
In no way this piece can be considered as a form of movement controlled sequencer, since none of the sound-structures exist neither in hardware nor software prior to the performance of the piece. The algorithms residing in Eproms and on the harddisk of the computer only hold the extensive math relevant for the musical syntax of the different pieces that make up the Book. The 'Book of Moves' is a real time algorithmic composition taking its control-inputs from the performer.</i>

#### Speelwijze, repertoire en inzet in producties
Deze hardware werd gebruikt voor zowel A Book of Moves als Songbook. Bij a Book of Moves werden de bewegingen van de performer na verwerking van de demodulator en de computer omgezet in midi-geluiden. Deze werden geproduceerd door de Proteus 3 World van E-mu Systems. Elke sectie van deze productie had een andere mapping van bewegingsparameters en de daarmee verbonden klankparameters.
Bij Songbook werden de bewegingsparameters gebruikt om de parameters van de in real time opgenomen stem van de performer te wijzigen. 

#### Opbouw van het instrument/installatie
De zender en ontvangers worden in de hoeken van een denkbeeldige tetraëder geplaatst en met DIN-kabels verbonden met de demodulator. Deze laatste wordt met behulp van een flatcable verbonden met een NIDAQ-kaart die op zijn beurt verbonden is met de computer. De zelfgeschreven software bepaalt in grote mate het klankresultaat.

#### Inscripties
- C
- X
- Y
- Z
- +15-

#### Staat van het instrument
Niet getest. De ontvanger die moet worden opgehangen ontbreekt.

#### Historiek van het instrument
Het Invisible Instrument op basis van sonar-technologie heeft een hele evolutie doorgemaakt. De hier gebruikte technieken worden verder ontwikkeld in het Invisible Instrument 2000 en 2010 (NAMUDA) die onder andere het Logos Robotorkest kunnen aansturen.

#### Problematieken
/

#### Media
##### Afbeeldingen
{{< load-photoswipe >}}
{{< gallery dir="/catalogus/img/Invisible_Instrument_(BOM-Songbook)" />}}

##### pdf-bestanden
[Onzichtbaar muziekinstrument BD1 (doctoraat GWR)](/logoscollectie/catalogus/pdf/Invisible_Instrument_(BOM-Songbook)/Onzichtb%20muziekinstr%20BD1%20(doctoraat%20GWR).pdf)

[Onzichtbaar muziekinstrument BD1 (doctoraat GWR)](/logoscollectie/catalogus/pdf/Invisible_Instrument_(BOM-Songbook)/Onzichtb%20muziekinstr%20BD2%20(doctoraat%20GWR).pdf)

[Onzichtbaar muziekinstrument BD1 (doctoraat GWR)](/logoscollectie/catalogus/pdf/Invisible_Instrument_(BOM-Songbook)/Onzichtb%20muziekinstr%20BD3%20(doctoraat%20GWR).pdf)

##### Audio
<audio controls>
<source src="/logoscollectie/catalogus/audio/Invisible_Instrument_(BOM-Songbook)/Book%20of%20moves.wav" type="audio/wav">
<source src="/logoscollectie/catalogus/audio/Invisible_Instrument_(BOM-Songbook)/Book%20of%20moves.wav" type="audio/x-wav">
</audio>
<a href="/logoscollectie/catalogus/audio/Invisible_Instrument_(BOM-Songbook)/Book%20of%20moves.wav"><i class="fa fa-download" aria-hidden="true"></i>
download</a>

<audio controls>
<source src="/logoscollectie/catalogus/audio/Invisible_Instrument_(BOM-Songbook)/Songbook%201.wav" type="audio/wav">
<source src="/logoscollectie/catalogus/audio/Invisible_Instrument_(BOM-Songbook)/Songbook%201.wav" type="audio/x-wav">
</audio>
<a href="/logoscollectie/catalogus/audio/Invisible_Instrument_(BOM-Songbook)/Songbook%201.wav"><i class="fa fa-download" aria-hidden="true"></i>
download</a>

<audio controls>
<source src="/logoscollectie/catalogus/audio/Invisible_Instrument_(BOM-Songbook)/Songbook%202.wav" type="audio/wav">
<source src="/logoscollectie/catalogus/audio/Invisible_Instrument_(BOM-Songbook)/Songbook%202.wav" type="audio/x-wav">
</audio>
<a href="/logoscollectie/catalogus/audio/Invisible_Instrument_(BOM-Songbook)/Songbook%202.wav"><i class="fa fa-download" aria-hidden="true"></i>
download</a>

