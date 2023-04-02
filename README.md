##Eindopdracht object georiënnteerd
Voor de eindopdracht hebben we een aantal dingen uit moet voeren. Deel 1 van de opdracht staat in het mapje deel 1. Deel 2 van de opdracht staat in deel 2, maar de uitleg wat ik heb veranderd staat hieronder.

Uitleg hoe je het programma op start staat als laatste genoteerd.

# Wat is er mis met jabberpoint?

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

# Hoe start je het op? 
Ik heb visual studio code (VSC) hiervoor gebruikt. 
Als je de folder app opent in VSC geeft hij als het goed is automatisch aan om extensions voor java te downloaden.
Als hij dat niet doet, heb ik de volgende extensions gebruikt:
1. Debugger voor Java
2. Extension Pack voor Java
3. IntelliCode
4. IntelliCode API Usage Examples
5. Language Support for Java(TM) by Red Hat
6. Maven voor Java
7. Project Manager for Java
8. Test Runner for Java

Als je vervolgens het programma wilt starten ga je naar het bestand deel 2/app/src/jabberpoint/jabberpoint.java en druk je op f5. Als het goed is moet het programma dan starten
