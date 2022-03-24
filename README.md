# Opdrachtbeschrijving

## Inleiding

Voor de muziekvereniging "OnsGenoegen" is een applicatie nodig om overzicht te houden van de instrumenten en actieve leden. Tot nu toe moet de leiding met allerlei papieren bij houden, van hoe alles op dat moment geregeld is. Dit is een rompslomp en zou de leiding graag anders zien. Je hebt eerder gekeken naar de requirements voor de applicatie, nu ga je een klassediagram samenstellen voor deze applicatie.

## Benodigde klassen

Voor deze app gebruiken we de volgende klassen:

- Instrument (id, name, type, usedBy, checked)
- Member (id, name, age, sex, sectionPossition, memberSince, instrument)
- Teacher (id, name, age, sex, section, instrument)
- Lesson (id, teacher, listOfStudents, section)
- Section (id, name, members, teachers)


![Muziek!](./assets/muziek.JPG)

## Opdracht

Stel voor de app een klassendiagram samen. Maak hierbij gebruik van de hierboven staande `Classes` en `variables`. Kijk daarna hier onder of je uit de tekst soorten relaties kan halen.

## applicatie beschrijving volgens leiding

Notule vergadering 12-05-2021

We zijn bij een om te bepalen of een applicatie voor de vereniging wenselijk is. 
De stemming heeft uitgewezen dat van de 15 personen uit de leiding van OnsGenoegen, 12 voor en 3 tegen zijn. 
De voornaamste redenen voor tegen is: Het niet gewend te zijn te moeten werken met applicaties, maar als de app gebruiksvriendelijk ontwikkeld wordt kunnen we ze hierbij helpen.

De volgende punten zijn wenselijk om te kunnen doen binnen de applicatie te kunnen regelen:

- De leraren zouden graag willen zien wanneer ze een les moeten geven en welke studenten daar bij aanwezig zullen zijn 
- De mensen van het onderhoud zouden graag overzichtelijk willen zien wanneer een instrument gecontroleerd moet worden 
- De leiding van de vereniging zou graag een overzicht van leden willen hebben 
- Piet die altijd de evenementen regelt zou graag willen zien wie op welke positie speelt
- De leiding wil graag kunnen zien welke secties wanneer oefenen
- De mensen van onderhoud zouden graag willen zien welk lid welk instrument in gebruik heeft
- De leiding wil zien welke leraren welke sectie les kunnen geven
