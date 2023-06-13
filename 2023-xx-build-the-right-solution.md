:title Løs det rette problemet
:author stig
:published 2023-01-20
:tech [:programming]

:blurb

Jeg elsker å løse oppgaver. Det gir meg mestringsfølelse og skaperglede. 
Når du må sette deg inn i en problemstilling og så eksponere det du har forstått (og misforstått) gjennom den koden du skriver, så lærer du fort. 

... men det er ikke alltid effektivt bruk av tid. 

Jeg har min egen modell som hjelper meg til å forstå viktige sammenhenger og effektivisere skapergleden min.
:body

Mine største blemmer som systemutvikler - handler ikke om teknologi, men derimot om feil fokus og mangel på verktøy til å forstå det raskt nok. 

* Jeg har laget funksjonalitet som aldri har blitt brukt 
* Jeg har laget løsninger som er bedre på unntakshåndtering enn det å støtte de sentrale standardprosessene.

Dette handler om forstå hva som er viktig.
Hvorfor fokuser vi av og til på feil oppgave? Hvorfor tar det av og til veldig lang tid før oppgavens kontekst forstås?
Hvordan skal du raskt komme under huden på en organisasjon og virkelig forstå DNA'et i det de driver med? 

Det finnes masse materiale om gode prosesser for å forstå brukerbehov. Mye nyttig lesing, men jeg synes ofte at metoder blir for omfattende til at det gir meg noen praktisk guiding i det daglige arbeidet. 

Det blir fort litt for mye tran og teknikker. Jeg ønsket meg en enkel modell som får plass på en serviett. 
Noe som kan ligge der i bakhodet samtidig som jeg kan gjøre det som er gøy. 

Over tid - så har jeg formet min "egen" mentale sjekkliste som hjelper meg å forstå og fokusere. 

Det er jo bare sunn fornuft, faktisk veldig gammel sunn fornuft. 
En gammel greker som het Aristoteles, ble tatt under vingene av en enda eldre greker, Platon, når han bare var 17 år gammel. 

På tenkeskolen var Aristoteles i 20 år og rakk å tenke mange kloke tanker innenfor ulike fagfelt, blant annet filosofi. 
For å forstå menneskers handlinger i fra ett filosofisk ståsted, definerte han det engelsktalende kaller **The 5 W's and one How**... eller på norsk: **Hvem, Hva, Hvor, Hvordan, Hvofor og Når**. 

Dette er en nyttig strategi for å forstå, innenfor mange fagfelt - også systemutvikling. 

De ulike perspektivene er ikke likeverdige. Det er jo ikke tvil om at **Hvorfor** er viktigere enn **Hvordan**. 
Over tid, har disse boksene ramlet på plass og fått litt spisset budskap på min serviett.

## Servietten
Sånn ser servietten ut. Den har 6 bokser, der _Hvem_, _Hvorfor_ og _Hva_ danner rammene for de andre. 
![Bestandelene av s1](/images/blogg/paper_all_2.png)

* **Hvem** - beskriver de aktørene som påvirker eller blir påvirket innenfor domenet/området vi jobber i.
* **Hvorfor** - beskriver det som er viktig for de ulike aktørene vi forholder oss til. 
* **Hva** - beskriver de sentrale begrepene på en slik måte at det er veldig tydelig og klart hva de betyr. 

Jeg har spisset teksten i boksene for å være litt mer tydelig i forhold til hva jeg legger i dem.
_Hvem_, _Hvorfor_ og _Hva_ har blitt: **Aktører**, **Mål/hensikt** og **Begrep**. 

Denne rammen legger føringer for de andre "boksene". 

### Aktører
Aktører er premissgivere for vårt domene eller mottakere av det vi holder på med. 
Slike premissgivere kan være eiere, myndigheter, konkurrenter eller bransjeorganisasjoner. Sentrale bransjestandarder kan også gi føringer som er viktige å forstå.
Mottakere er de som blir påvirket av måten vi driver vår virksomhet.
Det dekker alt i fra leverandører, kunder, egne ansatte og ikke minst eiere.
Aktører er den ene veggen i modellen - fordi vi må forstå deres påvirkning på alle nivå. 

### Mål/hensikt
Alle aktører har sine målsetninger.
Noen ganger kan det vere overlappende målsetninger på tvers av aktører, men de kan også være veldig ulike. 
I noen tilfeller ser vi også at ulike aktører kan ha målsetninger som er i direkte konflikt. 
De fleste prosjekter er flinke til å belyse hva som er hensikten med det vi skal gjøre, men ofte mangler bredden i forhold til å forstå alle som blir påvirket. 
Mål/hensikt er taket i modellen fordi det er overgripende for alt annet som blir definert. 

### Begrep
Vårt fag er ikke ukjent med begrep og deres betydning for vårt arbeid. 
Vi snakker om entiteter, klasser, objekter og datastrukturer som alle kan ha en eller annen direkte kobling til en organisasjons virksomhet. 
Uansett hva vi kaller byggeklossene - så er det utrolig viktig at vi klarer å definere tydelige begrep som alle kan enes om. 

Abstrasjonsnivå er viktig. Fokuser på begrep som handler om det organisasjonen driver med .... ikke hvordan noe er implementert. 

Selv om dette er velkjent - dukker det fremdeles opp vonde modeller. 
_Hvis vi bare tilpasser denne strukturen - så kan vi gjenbruke dette_... selv om vi egentlig burde definert nye begrep. 
Typiske problembegrep er: ordre, produkt eller kunde. 
I en verdikjede dukker jo disse begrepen opp i alle ledd, men betyr kanskje helt ulike ting på reisen. 

Begrep er den andre veggen i modellen fordi de skal gjenomsyre alle andre lag. Alt som beskrives i andre lag - må benytte begrep som er tydelig definert. 

Attributt eller ny struktur?

### Regler og beste praksis
Denne er viktig! Det er her du bestemmer om du skal lage gull eller gråstein. 
Regler og beste praksis skal beskrive hvordan en organisasjon faktisk har tenkt å innfri målsetningene til de ulike aktørene. Dette er i praksis _Hvordan_ på ett prinsippnivå. Ikke hvordan noe er implementert, men hvordan skal vi skal klare å få noe til.

* Hvilke triks har organisasjonen i ermet sammenlignet med sine konkurrenter?
* Hva er regnet for å være beste praksis?
* Hvilke lover og regler må vi forholde oss til? 

Jeg opplever at denne "boksen" ofte er underkommunisert. Noen har klart for seg hva som gjelder, men det er ikke tydelig formidlet til brukere og prosjektdeltagere.
Noen ganger oppleves det også som litt vondt å grave i regler, det er ikke alltid de er så tydelig definert. 
* Det har alltid vært sånn
* Noen har sagt at det skal være sånn
* Det er sånn det er solgt inn

Dette er ikke regler, men unnskyldninger. 

Noen ganger jobber vi med ett forretningsområde som er i støpesjeen og da er det kanskje ikke så klart hva som er beste praksis. 
Da er det fint å ha noen hypoteser og sørge for at vi raskt kan håndtere endringer. 

Systemer som har litt tid på baken, må ofte tilpasses fordi noe i denne "boksen" endres. Da er det viktig å forstå disse endringene før funksjonalitet utvikles... og ikke minst... hvilke regler er det som ikke lenger gjelder og hva kan vi ta bort av funksjonalitet.

Regler som ikke kan knyttes til noen målsetning - må bort. 

### Hendelser og prosess
Hendelser og prosess definerer alt det viktige som vil, eller kan, inntreffe og hvordan dette blir håndtert. Dette dekker _Når_ og _Hvordan_ i fra ett mer praktisk perspektiv. 

* Hva gjør aktørene som vi må håndtere?
* Hva skjer når vi har tilstandsendringer i sentrale begrep (ordre utført, ordre kansellert)?

Håndtering av endringer over tid kan være utfordrende. 
Det er ikke alltid en begrepsmodell passer i alle faser. 
Tenk på en plan for eksempel. 
Den kan være veldig vagt definert når den opprettes. 
Kanskje bare en dato, grovt kapasitetsestimat og litt geografi. 
Etter hvert så kommer mer detaljer på plass. Vi får konkrete klokkeslett, adresser og ikke minst allokerte ressurser. 

På ett tidspunkt glir planen over til å bli en instruks som noen skal utføre. 
Etter hvert som oppgavene utføres har vi en logg av utførte aktiviteter, samtidig som gjenstående aktiviteter kan replanlegges. 

Slike scenarier kan være krevende å modelere .... men desto viktigere å forstå. 
Det er derfor viktig å grave i hendelser som kan inntreffe og lære seg hvordan disse håndteres. 

### Systemstøtte
Endelig ... det som er gøy. 
Det er her vi virkelig lærer og skaper verdi. 
... men det er viktig at vi ser en rød tråd i det vi lager opp gjenom boksene og helt til målsetning og hensikt. 
* Hvordan skal funksjonaliteten understøtte viktige hendelser og prosesser. 
* Hvordan griper de inn i regler og beste praksis?
* Hvordan påvirker de aktørenes målsetninger?

![Bestandelene av s1](/images/blogg/maal_og_hensikt.png)


Det var det, en ganske enkel modell.

Jeg bruker den som en sjekkliste for å forstå hvor jeg har hull i kunnskapen min. 

Nedenfor har jeg forsøkt å lage ett eksempel som illustrerer modellen i praksis.

## Ett praktisk eksempel

Nå passer det bra med ett eksempel innenfor ett domene som er ukjent for de fleste. 
Jeg skal forsøke å danne ett bilde av funksjonalitet gjennom å fylle "boksene" rundt med innhold.  

Vi skal hjelpe han her har (akspetert at han blir hengt ut). 

Orientering

Glad og blid før start, men blir litt grumpy underveis i arrangementet. 
Ett par prosesser som fungerer dårlig og trenger systemstøtte ... eller kanskje til og med en skikkelig refakturering. 

### Aktørene
* Norges Orienteringsforbund
* deltager
* **tilskuer**
* ulike arrangørroller
    * starter
    * sekreteriat
    * premieutdeler
    * speaker
    * saftblander

Ikke vanskelig å forstå hvilke aktører som er viktig. 
Fokuserer på tilskueren i dette eksempelet

### Hensikt og målsetning
Hva er viktig for en tilskuer?
Det er vel ingen hemlighet at vi har få tilskuere som kommer på orienteringsløp bare for å følge med på spenningen. 

De aller fleste som er på løp - er der for å løpe selv eller følge opp barn som skal løpe. 
Mye vening og så ett lite tidsvindu som er viktig i det den unge håpefulle stempler på sistepost og stormer frem i oppløpet på vei til mål. 
Her gjelder det å komme med noen oppmutrende ord. 
Når alle barna har kommet i mål og fått tildelt sin premie så er det ofte raskeste vei hjem som teller.

Målsetningene for en tilskuer kan oppsummeres slik
* heie på sine favoritter i oppløpet
* komme seg hjem så fort som mulig

### Begrep

På tide å tydeliggjøre noen begrep. 
* En deltager tilhører en klubb. 
* En deltager melder seg på i en klasse som passer kjønn, alder og nivå.
* En klasse er satt opp til å løpe en løype
* En løype kan løpes av flere klasser.
* En løype består av flere poster som er sjekkpunkter som skal besøkes i riktig rekkefølge
* Ute i skogen er det plassert post-enheter for å markere poster. 
* En postenhet kan benyttes av mange ulike løyper
* På en postenhet kan det plasseres en mellomtidsstasjon som overfører passeringser (stemplinger) til tjenester på internett. 
* En deltager har en elektronisk brikke som benyttes til registrering av passering på postenhet 

![Bestandelene av s1](/images/blogg/begrep.png)
![Bestandelene av s1](/images/blogg/postbukk_med_mellomtid.jpg)

### Regler og beste praksis

Hva gjør vi for å oppnå hensikten /målsetningen for våre tilskuere?

<style>
.info {
  background: rgba(175,175, 219,0.2);
  padding: 10px;
}
</style>

<div class="info">
Målsetning: Heie på sine favorittdeltagere i oppløpet
</div>

<div class="info">
Regel: Vi må fange opp at deltagere nærmer seg mål. 
Det gjør vi ved å sørge for at alle løyper har en felles postenhet 300-500 meter før mål. 
På denne postenheten settes det opp en mellomtidsstasjon som overfører brikkenummer, postkode og tidspunkt til tjenester som tilgjengeliggjør dette på internett.  
</div>

### Hendelser og prosess

Hva skjer så under selve stemplingsprosessen?
Visualisert i ett forenklet sekvensdiagram. 

Slik ser det ut i skogen. 
![Bestandelene av s1](/images/blogg/stemplingsprosess.png)



## Inspirasjon
Togaf
zackman framework
Aristoteles

## Betraktninger...

Noen ganger fokuseres det på feil oppgave eller det tar veldig lang tid før oppgavens kontekst forstås. 

Jeg har ingen ønsker om å komme tilbake til en tid med fossefall og forsøk på å tenke alle tanker før spaden settes i jorda. 
Det fungerte ikke før - og fungerer fremdeles ikke. 
Innimellom er det likevel lurt å løfte blikket for å forstå de litt større sammenhengene. 
Over tid har jeg fått mine egne "bokser" som definerer viktige sammenhenger som hjelper meg med å effektivisere skapergleden min. 


Du kan bli en god sparringspartner for hva som er riktig funksjonalitet 

I ett prosjekt skal vi sjelden løse alle utfordringer i en organisasjon. 
En første sortering av hvilke aktører/målsetninger vi skal forholde oss til - kan være en fin definering av scope. 

Disse skal vi forsøke å innfri/forbedre, mens disse er bare til informasjon. Kjekt å kjenne til, men det er ingen forventning om at vårt prosjekt skal påvirke hvordan disse håndteres. 

I prosjekter som har sklidd på tid - er det veldig ofte knyttet til uavklarte målsetninger i en tidlig fase. 
Det er jo selvfølgelig fint å lære underveis, men da bør læringen være lik for alle parter i prosjektet og ikke bare ensidig opplæring av en part.... ala dette burde du ha forstått. 

dokumentasjon
Noen ganger er til og med brukerene selv ikke på riktig spor. 