# Angular en Esri
**Dit is de basis voor de Angular met Esri opdracht.**

## Opzetten van de applicatie
1. Installeer NodeJS versie 6 of hoger. ([https://nodejs.org/en/](https://nodejs.org/en/))
2. Zorg dat npm geïnstalleerd is. Wanneer je NodeJS installeerd krijg je deze er automatisch bij.
3. Installeer je angular/cli met het volgende command line commando. Hierdoor kunnen we straks de unit testen uitvoeren.
```
npm install -g @angular/cli
```
4. Voer het volgende commando uit om een nieuw project te starten:
```
ng new [PROJECTNAAM]
```
Vervang hierbij [PROJECTNAAM] door een naam voor je project.
5. Er is nu een nieuw project voor je aangemaakt. Om te testen of alles naar behoren werkt, ga je via de command line naar de map waar je net aangemaakte project staat en voer je het volgende commando uit:
```
ng serve
```
6. Via [http://localhost:4200](http://localhost:4200) zie je nu een website met de tekst 'App works!'.