# OGO-eindopdracht

Over het algemeen is er redelijk wat mis met Jabberpoint. Dit is mijn poging om het te verbeteren en goed te maken. Ik heb hiervoor de design pattern 'decorator' gebruikt.
Verder heb ik nog een aantal andere bewerkingen gedaan:
De reden dat de user interface functionaliteiten gescheiden worden van de kern functionaliteiten:
https://refactoring.guru/smells/speculative-generality

De reden dat de accessor is vervangen door aparte load en save klasses:
https://refactoring.guru/smells/middle-man

De reden waarom alle methodes kort zijn:
https://refactoring.guru/smells/long-method

De reden waarom de SlideViewer de presentation in zich heeft en andere klasses de SlideViewer aanspreken:
https://refactoring.guru/design-patterns/decorator
