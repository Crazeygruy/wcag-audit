# WCAG Audit 

Doe een WCAG audit op een bestaande website uit je eigen omgeving en rapporteer daarover.

De instructies van deze opdracht staan in [WIKI](https://github.com/fdnd-task/wcag-audit/wiki).


## Titel Website

Welke website heb je getest? Beschrijf de website en voeg een screenshot toe.

Toon een screenshot van het Lighthouse Accessibility testresultaat.

Schrijf een samenvatting van de testbevindingen, en link naar je Wiki voor de volledige documentatie.

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

## Bounyad zijn deel samenvatting bevindingen SV Hillegom
https://www.svhillegom.nl/

Keyboard test: Ik zie dat je niet kan zien waar je naartoe gaat als je gaat tabben of met de keyboard navigeert, je ziet wel de namen van de links en wat de link naam daadwerkelijk is vergeleken met de benaming op de website, maar je hebt geen idee waar je bent omdat de website dat niet laat zien

Screen reader test: De fotos hebben geen alt wat al uit de lighthouse was gekomen, Aria hidden= true is niet toegepast aan de website, dus dat hebben ze goed gedaan voor mensen met screen readers.

interactive elements en headings and landmarks: Je kan met tab naar knoppen, alleen zie je helemaal geen focus, er staan veel koppen op h4 en h5, maar er is geen duidelijke h1 of h2. De semantische gedeelte is niet voldaan, ik zie alleen maar body, divs en verder geen main, header of footer.
