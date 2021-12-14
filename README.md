# Examen Opdracht IoT Devices

Los onderstaande vragen zo compleet mogelijk op. Voorzie figuren waar mogelijk. Gelieve ook te letten op spelling en grammatica.

Geen copy/paste van Internet. De bedoeling is dat je wat onderzoek doet en met je eigen woorden de vragen beantwoord. Vermeld ook onderaan het document je bronnen.

## I2C

* Wat is I2C? Geef de belangrijkste eigenschappen.
* Welke topology gebruikt deze communicatie-technologie. Verduidelijk met een figuur. Geef ook aan hoe de fysieke connectie gebeurt tussen verschillende devices en licht elke connectie toe. Wat is het nut van de open-drain output drivers?
* Hoe gebeurt de adressering van een device? Verduidelijk ook hoe dit plaatsvind op een lager / fysisch niveau (bus contention).
* Geef een klein code-voorbeeld hoe je schrijft en leest naar en van een device met mbed.

## UART / RS232

* Wat is het verschil tussen UART en RS232 ?
* Hoe kunnen twee embedded devices met elkaar serieel communiceren aan de hand van deze technologie? Welke topologie wordt hier gevormd ? Verduidelijk aan de hand van een figuur.
* Hoe kan de connectie gebeuren met device zoals een computer/laptop? Welke component heb je hiervoor nodig?

## SPI

* Wat is SPI? Geef de belangrijkste eigenschappen.
* Welke topology gebruikt deze communicatie-technologie. Verduidelijk met een figuur. Geef ook aan hoe de fysieke connectie gebeurt tussen twee devices en licht elke connectie toe. Hoe kunnen meerdere slave devices worden aangesloten op een  enkele master (twee opties)? Geef van elk een figuur.
* Hoe gebeurt de selectie/adressering van een slave device bij SPI? Wat is het verschil met bv. I2C?
* Geef een klein code-voorbeeld hoe je schrijft en leest naar en van een device met mbed.

## LoRaWAN

* Wat is LoRaWAN? Geef de belangrijkste eigenschappen.
* Maak een figuur van een LoRaWAN topologie waarbij je alle componenten verduidelijk van node tot applicatie. Geef wat uitleg bij elke component.
* Wat gebeurt er wanneer het radio bericht door twee gateways wordt ontvangen? Hoe komt het dat we dit maar 1x in de Things Network Console krijgen en geen 2x?
* Wat is payload filter? Geef een klein voorbeeld. Wat is het nut van de fPort?
