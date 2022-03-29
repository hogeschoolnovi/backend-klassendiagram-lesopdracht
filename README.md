## Inleiding

Voor de muziekvereniging "OnsGenoegen" is een applicatie nodig om overzicht te houden van de instrumenten en actieve leden. Tot nu toe moet de leiding met allerlei papieren bijhouden, van hoe alles op dat moment geregeld is. Dit is een rompslomp en zou de leiding graag anders zien. Je hebt eerder gekeken naar de requirements voor de applicatie, nu ga je een klassendiagram samenstellen voor deze applicatie.


# Opdrachtbeschrijving

Je gaat een klassendiagram maken voor de applicatie die voorziet in de wensen van de muziekvereniging "OnsGenoegen". Maak hierbij gebruik van de onderstaande `classes` en `variables`. Kijk ook of je uit de tekst onderaan soorten relaties kan halen.


## Benodigde klassen

Voor deze app gebruiken we de volgende klassen:

- Instrument (id, name, type, usedBy, checked)
- Member (id, name, age, sex, sectionPossition, memberSince, instrument)
- Teacher (id, name, age, sex, section, instrument)
- Lesson (id, teacher, listOfStudents, section)
- Section (id, name, members, teachers)


![Muziek!](./assets/muziek.JPG)


## Wensen voor de applicatie

Notule vergadering 12-05-2021

We zijn bijeen om te bepalen of een applicatie voor de vereniging wenselijk is. 
De stemming heeft uitgewezen dat van de 15 personen uit de leiding van OnsGenoegen, 12 voor en 3 tegen zijn. 
De voornaamste redenen voor tegen is: "niet gewend om te werken met applicaties", maar als de app gebruiksvriendelijk ontwikkeld wordt kunnen we ze hierbij helpen.

De volgende punten zijn wenselijk om te kunnen doen binnen de applicatie:

- De leraren willen zien wanneer ze een les moeten geven en welke studenten daarbij aanwezig zullen zijn.
- De facilitair medewerkers willen overzichtelijk zien wanneer een instrument gecontroleerd moet worden.
- De leiding van de vereniging wil graag een overzicht van leden hebben.
- Piet, die altijd de evenementen regelt, wil zien wie op welke positie speelt.
- De leiding wil zien welke secties wanneer oefenen.
- De facilitair medewerkers willen zien welk lid welk instrument in gebruik heeft.
- De leiding wil zien welke leraren welke sectie les kunnen geven.
