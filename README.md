# Api inlämnnigsuppgift 2

## Teoretisk del
### G:
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

### VG:
#### 1. Vad innebär Service Oriented Architecture (SOA)
SOA är ett sätt att bygga mjukvara där olika enkla tjänster som arbetar ihop genom att sända och ta emot data.

#### 2. Vad är fördelarna med API:er jämfört med en webblösning som går direkt mot en databas?
Fördelarna med att använda sig av API istället för att koda direkt mot backend är att man kan använda API:et till flera olika projekt, samt att man enkelt och säkert kan göra data från API:et tillgängligt public.

#### 3. Vad innebär OAUTH?
OAUTH innebär att man ger användare möjlighet att logga med sina användaruppgifter från t.ex. facebook eller google. Enkelt, smidigt och säkert. Både för utvecklare och användare.

#### 4. Vilka typer av managed services erbjuds av Public Cloud och vad innebär de?
On-Premises:
Servrar som körs på samma fysiska plats som ägaren. Ägaren står själv för all hantering och alla kostnader såsom inköp, elektricitet och perosnal. 

Infrastructure as a service:
Server/servrar som tillhandahålls av någon annan. Man ansvarar själv för all 'mjuk' hantering, såsom installation, konfigurering, uppdatering o.s.v.

Platform as a service:
Servrar och mjukvara som tillhandahålls och sköts av någon annan. Enbart inriktad på en sorts hosting. Man själv sköter enbart koden till själva applikation.

Software as a service: 
Tjänster man bara använder såsom gmail eller google maps.

#### 5. Vad innebär TDD och BDD?
TDD - Test Driven Development innebär att man först skriver tester, sen skriver aktuell logik som ska testas.
BDD - Behavior Driven Development innebär att man skriver tester i vanlig text och i 'layman's terms' så att alla kan förstå dem.





## Praktiskt del
### Produktbeskrivning
Jag vill utveckla en sida där användare kan lägga upp och se säljes-annonser för motorcyklar.
Man kan sortera annonserna efter pris eller ev. avstånd.
Man kan filtrera annonserna utifrån t.ex. märke eller årsmodell.

Väl inne i annonsen ska bild/bilder finnas samt mer information och vart den finns.

### Usecases
https://trello.com/b/QfY18efd/usecases-apiuppg2