![](https://i.imgur.com/iywjz8s.png)



# Samenwerkingsdocument dag 2

2025-02-03 Research Software Support

Welkom bij het samenwerkingsdocument van de workshop.

Dit document wordt gesynchroniseerd terwijl u typt, zodat iedereen die deze pagina bekijkt dezelfde tekst ziet. Hierdoor kunt u naadloos samenwerken aan documenten.


----------------------------------------------------------------------------



Dit is het document voor vandaag: edu.nl/ggk8g

Samenwerkingsdocument dag 1: edu.nl/df9v6

Samenwerkingsdocument dag 2: edu.nl/ggk8g


##  🫱🏽‍🫲🏻 Gedragscode

Van deelnemers wordt verwacht dat zij deze richtlijnen volgen:
* Gebruik gastvrije en inclusieve taal.
* Respecteer verschillende standpunten en ervaringen.
* Accepteer constructieve kritiek op een elegante manier.
* Focus op wat het beste is voor de gemeenschap.
* Toon respect tegenover andere leden van de gemeenschap.

[training@esciencecenter.nl](mailto:training@esciencecenter.nl)

## ⚖️ Licentie

Alle inhoud is openbaar beschikbaar onder de Creative Commons Attribution Licentie: [creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/).

## 🙋Hulp krijgen

Om een vraag te stellen, steek je gewoon je hand op.

Als je hulp nodig hebt van een helper, plak dan een roze post-it op de klep van je laptop. Er komt zo snel mogelijk iemand van ons langs om je te helpen.


## 🖥 Workshop website

Workshop informatie:
[link](https://esciencecenter-digital-skills.github.io/2025-02-03-ds-rss-masterclass-DCC-PO/)

Les- en zelfstudiematerialen:
[link](https://esciencecenter-digital-skills.github.io/research-software-support/)


## 👩‍🏫👩‍💻🎓 Instructeurs

Jaro Camphuijsen, Dani Bodor, Lourens Veen

## 🧑‍🙋 Helpers


## 👩‍💻👩‍💼👨‍🔬🧑‍🔬🧑‍🚀🧙‍♂️🔧 Roll call
Naam/ voornaamwoorden (optioneel) / werk, rol / social media (twitter, github, ...) / achtergrond of interessen (optioneel) / stad


## 🗓️ Schema
|  Tijd | Onderwerp                            |
| -----:|:------------------------------------ |
| 09:30 | Welkom, recap en huiswerk            | 
| 10:00 | Version Control and Software Testing |
| 11:00 | Break                                |
| 11:15 | Software Documentation               |
| 12:15 | Lunch Break                          |
| 13:15 | Distributing Software                |
| 14:15 | Break                                |
| 14:30 | Software Licenses                    |
| 15:15 | Break                                |
| 15:30 | Software Publication and Citation    |
| 16:15 | Wrap-up                              |
| 16:30 | End & Drinks                         |


## 🏢 Locatie logistiek
 * Koffie en toiletten bevinden zich in de gang, net buiten het klaslokaal.
* Als u het gebouw verlaat, 
  zorg ervoor dat je vergezeld wordt door iemand van het esciencecentrum om je via de deur op de begane grond weer binnen te laten
* Voor toegang tot deze verdieping dient u eventueel aan te bellen, zodat iemand u binnen kan laten
* In geval van nood kunt u onze verdieping verlaten via de hoofdtrap.
  Of volg de groene lichtborden aan het plafond naar de noodtrap.
* **Wifi**: Eduroam zou moeten werken. Gebruik anders het netwerk 'MatrixONE', het wachtwoord is te vinden op de uitgeprinte vellen in de kamer.

## 🎓 Aanwezigheidscertificaat
Indien u de volledige workshop volgt, kunt u een certificaat van deelname aanvragen door te mailen naar training@esciencecenter.nl.
Vraag uw certificaat binnen 8 maanden na de workshop aan, aangezien wij na deze periode alle persoonlijk identificeerbare informatie zullen verwijderen.

## Huiswerk


## 🔧 Oefeningen

### Exercise: Which of the following do you think should be part of a code repository (5-10 mins)
Discuss with your neighbor which of the following should be part of the code repository and why it should or should not.

- installation instructions (i.e. detailed instructions on how to install the software)
- user documentation (i.e. information for the users of the software about its functionality and features)
- full dataset to reproduce figures from a paper
- a few data files to test the functionality of the code base
- in-line comments intended only for code developers

### Exercise: Which of the following do you think should be part of a code repository (5-10 mins)

Identify the test types in this story:

During the process of manufacturing a ballpoint pen, we see smoke coming out of one of our machines, so we halt production immediately, put out the fire, and check why it caught fire in the first place before continuing.
We can now start production. The cap, the body, the tail, the ink cartridge, and the ballpoint are produced separately and we check the quality of each component before assembly. Next we check that the cap and tail fit on the body and the ink cartridge fits inside. When everything is put together, we ensure that it writes properly and doesn't leak.

In the future, we plan to supply different colors of ink and will re-run these tests for each new colored pen.

Test types: https://esciencecenter-digital-skills.github.io/research-software-support/modules/testing/software-testing#/2


#### JARO 
Unit Test → Controle van individuele onderdelen.
Integration Test → Passen van componenten samen testen.
System Test → Controle of de pen schrijft en niet lekt.
Regression Test → Hetzelfde testproces herhalen voor nieuwe inktkleuren.

#### Nog niet bekend
Smoke test -> Snelle test waarom de pen in brand vliegt 
                        
Unit testen -> Test van elke componenent 
System testen-> Als alles samengezet is

Integration test -> Past de dop, de body en de tail met elkaar.
Regression test -> veranderingen van de kleuren

#### Noord, Zuid, Oost, West
Unit test:test van de verschillende onderdelen
Integratie test: of alles in elkaar past
System test: werkt het met elkaar
Regression test: nieuwe kleuren 


#### The FAIRies
Systemtest: to check why it got fire in the first place.
Unit test
Integration test
Regression test

#### {Groepsnaam5}


### Levels of documentation

https://esciencecenter-digital-skills.github.io/research-software-support/modules/documentation/exercise-levels

Joanne is working on her research software 'WeatherMap' that analyses and summarizes measurements from weather stations.

Here is a list of possible forms of documentation:

A basic README file containing: quick installation instructions, two lines explaining why the software was created, two basic examples of how you can use the software.
A tutorial: 'Finding unusual patterns in daily average temperatures using WeatherMap'.
In-code documentation: Comments in her code that explain why she made certain implementation choices.
API reference: Detailed description of each function/class of WeatherMap.
Overview of components: A detailed overview of each component in the software.
User documentation: Extensive documentation on how users can use each of the functionalities of WeatherMap.
Naming: Logical names for functions, modules, and classes so that it is immediately clear what the corresponding piece of code does.
For the following scenarios, which forms of documentation would you suggest Joanne to incorporate in her project:

Scenario A:
Joanne just started her PhD and is the only one using WeatherMap to create results for her first paper. She does not really care about anyone else using her software.

Scenario B:
Joanne works together with a few other PhD students in her research group on the software. She wants to make it easier for other researchers in her group to also adopt the software, and finds it important that when she moves on to a different job that the software can be still be used and improved in her absence.

Scenario C:
Joanne and her colleagues spend half of their time updating and improving WeatherMap. They have a large community of users around the globe that depend on WeatherMap for their research.


#### JARO 
Scenario A: In-code documentation and naming.
Scenario B: alles behalve user doc. 
Scenario C: Alles. 


#### Nog niet bekend
a readme
b alles
c alles



#### Noord, Zuid, Oost, West
Joanne
a: In code, basic readme, naming
b: In code, readme, naming, user, overview,
c: In code, readme, naming, user, overview, API, tutorial


#### The FAIRies
A:In-code documentation
B:
C:Alle documenten

#### {Groepsnaam5}



### How to distribute this software?

https://esciencecenter-digital-skills.github.io/research-software-support/modules/distributing/exercise-distributing


## Post-Workshop Survey 

https://www.surveymonkey.com/r/8JVZPTT


## 🧠 Gezamenlijke notities

## 📚 Resources

### SMP

- Software Management Template van het eScience Center: https://www.esciencecenter.nl/wp-content/uploads/2023/01/SS-2023-3.-Template-Software-Management-Plan-2023.docx

### Voorbeeld documentatie

Deze voorbeelden demonstreren verschillende vormen van documentatie van een en dezelfde software:

- Repository met README: https://github.com/multiscale/muscle3
- Gebruikersdocumentatie/API documentatie: https://muscle3.readthedocs.io/en/latest/
- Klasse met docstring in Python
- : https://github.com/multiscale/muscle3/blob/51f84afa9c6e37d6f42dbd3ade63aacfeb7d76df/libmuscle/python/libmuscle/instance.py#L107
- Automatisch gegenereerd daaruit: https://muscle3.readthedocs.io/en/latest/python_api.html#libmuscle.Instance
- Zelfde klasse, maar nu in C++, met `/* ... */` in plaats van `"""`, en boven de klasse in plaats van erin: https://github.com/multiscale/muscle3/blob/51f84afa9c6e37d6f42dbd3ade63aacfeb7d76df/libmuscle/cpp/src/libmuscle/instance.hpp#L93


### Licenties

- Hoofdstuk in The Turing Way over licensing: https://book.the-turing-way.org/reproducible-research/licensing
- Choose a license: https://esciencecenter-digital-skills.github.io/research-software-support/modules/licenses/ex_choose_a_license