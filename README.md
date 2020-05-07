# Api inlämnnigsuppgift 2

## Teoretisk del
#### 1.  Vad är skillnaden mellan backend och databas? Beskriv vad respektive ansvarar för?
Backend är allting som har med servern att göra, sånt användare inte ser. Där körs logik för att hantera data, medans databasen enbart finns för att lagra och servera data både till frontend och backend.

#### 2. Varför är det viktigt att vara konsekvent i sin API-design för att skapa ett användarväntligt API?
Det är viktigt att vara konsekvent i sin API-design för att underlätta för utvecklare som sedan ska använda API't. En bra struktur förenklar hanteringen av data och minimerar risken för ev. fel. en väl strukturerad API underlättar dessutom felsökning.

#### 3. Vad är autentisering vs auktorisering?
Autentisering identifierar **vem du är** medans autorisering verifierar **vad du är tillåten att göra**

#### 4. Vad är skillnaden mellan "Private Cloud" och "Public Cloud". Vilka typer av tjänster erbjuder public cloud?
Ett private cloud är ett företags egna moln av servrar där företaget själv ansvarar för underhåll osv.
Ett public cloud är ett moln av servrar som tillhandahålls och underhålls av en provider där man kan hyra in sig, såsom t.ex. azure eller amazons AWS

#### 5. Varför testar vi mjukvara?
Tester skrivs för att förhindra att man implementerar kod med buggar.

## Praktiskt del
### Produktbeskrivning
Jag vill utveckla en sida där användare kan lägga upp och se säljes-annonser för motorcyklar.
Man kan sortera annonserna efter pris eller ev. avstånd.
Man kan filtrera annonserna utifrån t.ex. märke eller årsmodell.

Väl inne i annonsen ska bild/bilder finnas samt mer information och vart den finns.

### Usecases
https://trello.com/b/QfY18efd/usecases-apiuppg2