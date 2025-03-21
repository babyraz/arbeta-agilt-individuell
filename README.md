länk till gruppens repo
https://github.com/holmnotfound/Yum-Yum-Gimmie-Sum.git

# Individuella reflektioner

Svara på var och en av frågorna nedan individuellt (minst 100 tecken per fråga)

## Frågor

### Inledning

#### Vad var ditt mål med projektet initialt?

Att lära mig mycket av mina gruppmedlemmar. Jag var medveten om att jag var i en grupp med kunniga gruppmedlemmar så mitt fokus var att ställa mycket frågor och försöka lära mig så mycket som möjligt av dem.

#### Vad var din känsla inför att arbeta i ett team när du gick in i uppgiften?

Jag var lite nervös inför att jobba i just den här gruppen min upplevelse var att dom andra medlemmarna kanske var mer kunniga än jag men jag valde att ha en ödmjuk inställning till det och vara ärlig med vart jag känner att jag brister i mina kunskaper. 

### Planering och genomförande

#### Hur tycker du att planeringen inför projektet fungerade?

Väldigt bra. Vi diskuterade och satte poängvärden på alla user stories och valde sedan ut vad vi skulle göra i första sprinten och skissade upp vyerna i Figma. Vi pratade mycket om MVP och hur vi skulle prioritera bland user stories för att få en fungerande produkt som i alla fall kan funka som proof of concept - att man ska kunna lägga en beställning.

#### Vad har du bidragit med i planeringen, samt utvecklandet av applikationen.

Jag har bidragit med att tänka utifrån MVP, ibland behöva resonera kring vad som är logiskt att genomföra vs hur enkelt vi ska göra det för oss själva. Ex. när vi gick igenom user story gällande att kunden ska få en leveranstid tänkte vissa gruppmedlemmar att man behövde ha ett logisk uträkning för hur lång tid det faktiskt skulle ta att göra medan jag tänkte, att till en början i alla fall, så kan vi slumpa fram en tid  som känns rimlig. När vi sedan har alla grundläggande funktioner på plats så hade vi kunnat förbättra/utveckla sådana funktioner.

I själva applikationen har jag gjort login-sidan med tillhörande logik som validerar gentemot localstorage. Jag har varit med och utvecklat vår "databas" - vi skapade klasser för kunder och admin för att kunna spara inloggningsuppgifter. Jag gjorde även en "hitta oss" sida med tre kartor som skiftar mellan tre platser i Malmö, Göteborg och Stockholm för att simulera att foodtruckarna rör på sig. Jag skapade även en admin sida med statistik om hur försäljningen ser ut och funktionalitet kopplat till login-sidan - loggar man in som admin kommer man till admin-sidan. Jag gjorde en liten funktion för att slumpa fram en leversanstid mellan 10 och 20 minuter. Utöver det har jag gjort flera småsaker, som att ändra så att LOGGA IN knappen ändras till LOGGA UT om man är inloggad, och att LOGGA UT faktiskt loggar ut användaren. Utöver detta har jag gjort diverse buggfixar.

#### Beskriv med dina egna ord, er applikation

Vi har skapat en applikation för Yum Yum Gimmie Sum där man kan registrera sig och logga in som användare, lägga en eller flera beställningar, få kvitto och se orderhistorik. Man kan även se vart foodtruckarna finns i realtid samt få mer info på "om oss" sidan. Appen har även funktionalitet för att man som admin kan se statistik på försäljningen.

### Teamets utmaningar och lösningar

#### Vika var de största utmaningarna för dig?

Att ta mig an svåra uppgifter och våga be om hjälp av (huvudsakligen) sedan tidigare främmande gruppmedlemmar.

#### Hur löste eller hanterade du dessa utmaningar?

Jag arbetade aktivt med att ställa frågor så fort jag inte förstod vad någon menade eller om där fanns kod jag inte förstod. I vår sprint retro pratade jag även om att det var ett av mina mål.

#### Vilka kompromisser inom teamet har du fått göra under projektets gång?

Att vissa saker funktioner gjordes mer funktionella än vad jag tänkt att man skulle börja med. Min inställning var att hårdkoda det mesta för att få en proof of koncept app, för att sedan bygga den faktiska funktionalitet för att t.ex. kunna registrera användare. Men andra gruppmedlemmar ville bygga grunden för funktionaliteten så det var det vi gjorde och i slutändan så använde vi oss mycket ut av den och det underlättade det senare arbetet.

### Individuell reflektion och utvärdering

#### Vad lärde du dig under projektets gång?

Vikten av att ha en grundlig struktur och att vara närvarande och lättillgänglig. Vi satt mycket i Discord även om vi inte hade ett specifikt möte igång. På så sätt var alla lättillgängliga, det var lätt att ställa frågor och det blev allmänt god stämning.

#### Finns det någonting du skulle velat göra annorlunda om du fick chansen igen?

Jag hade kanske velat ta längre tid på mig på varje task och göra det så skalbart som möjligt istället för att känna stress att bli färdig med tasks.

#### Vilka möjligheter ser du med de kunskaper du fått under arbetet med projektet?

Jag tycker att jag har fått en insikt i hur arbetslivet faktiskt ser ut som programmerare, både att jobba i team och enligt scrum men också själva processen av att skapa olika sidor/funktioner som ska lira med andras kod och att kunna felsöka genom flera led, och då kod som någon annan har skrivit. Utöver det så har jag lärt mig mycket av mina gruppmedlemmar, t.ex. hur man kan nyttja en och samma css fil för flera html sidor samt att arbeta med klasser.

### VG-frågor (minst 200 tecken)

#### Beskriv minst tre fördelar med att arbeta agilt och motivera varför de är viktiga. Använd exempel från ert projekt för att styrka dina argument.

1. Att man träffas varje dag och stämmer av med varandra gör så att alla är med på vad alla andra gör och förhindrar dubbeljobb, att två väljer samma task. Det möjliggör också gott samarbete eftersom man regelbundet kan uttrycka ev. hinder man sitter med och kunna få hjälp/stöd/tips av sitt team. Detta hände relativt ofta för oss och då satt vi antingen hela teamet och tittade på koden eller så satte sig två och parkodade.

2. Att jobba med kanban gav en tydlig överblick över vad som finns kvar att jobba med och vad en task innefattade. Det blev också en tydlig prioriteringslista utefter kundens value points och vår egna bedömning. Det var lätt att kontinuerligt ta på sig nya tasks men även att skapa nya tasks när saker uppstod, buggfixar eller extra features som man ville lägga till.

3. Att jobba med ett tydligt kundfokus är något jag är rätt van vid sedan tidigare så det var skönt att arbeta på ett sätt där kundens user stories fick leda en. Genom att utgå från user stories så upplevde jag att det blev lättare att prata om helhetsupplevelsen för användaren, det fick en att ta på sig användarens skor och tänka "hur tänker jag att jag hade velat uppleva detta" och då kommer man på många "quality of life" funktioner som man kanske inte hade tänkt på annars - liknande dom som dyker upp på användartest. Det hjälper även att kunna avgränsa projektet och hålla fokus - har vi faktiskt en user story för detta eller är det bara något som vi tycker är najs? I så fall kan vi ställa frågan direkt till kunden på nästa sprint review, istället för att försöka gissa kundens behov.

#### Beskriv en konkret lösning du föreslagit under projektet. Varför ansåg du att den var bäst? Jämför med minst en annan möjlig lösning och förklara varför du inte valde den.

När vi skulle göra admin-sidan diskuterade vi vad admin skulle ha tillgång till. Ska admin kunna lägga en beställning? Mitt förslag var att hålla det enkelt med fokus på user storien - om man loggar in som admin så kommer man direkt till en admin-sida som visar statistik istället för att det skulle ha lagts till som ett alternativ i hamburger-menyn. Min lösning blev både lättare att utföra och kändes också mest logiskt utifrån user storien men även hur man generellt tänker att en admin inloggning fungerar, det är inte logiskt att en admin ska lägga beställningar.

#### Ge minst två exempel på lösningar ni valde bort. Analysera varför ni avstod från dem. Hur påverkade det projektet? Kunde något ha gjorts annorlunda?

Vi hade klasser för customer och admin som vi använde för att kunna logga in. Vi hade tankar om att kunna spara ner den faktiska orderhistoriken för varje kund i localstorage för att sedan kunna visa det under orderhistorik och admin men i slutändan valde vi att hårdkoda det istället pga tidsbrist.

Vi hade också en tanke om leveranstiden, att försöka räkna ut en faktiskt rimlig leveranstid för hur lång tid vi tror att det hade tagit för en rätt att lagas färdigt beroende på rätten men även hur många andra beställningar som låg i pipelinen. Detta skrotade vi och istället gjorde vi det enkelt och randomiserade mellan 10-20 min. Funktionen hade vart häftig att få till men i slutändan så var det inte värt att lägga ner tiden på det utan istället tänkte vi MVP.

#### Reflektera kring hur den kod du bidragit med skulle kunna förbättras, ge konkreta exempel.

Jag hade haft fokus på att göra mina funktioner mer brett applicerbara och försöka se till att jag inte upprepar kod. Exempelvis skrev jag två funktioner i main.js för att hantera knapparna för att logga in, för att ändra den till att säga logga ut och att faktiskt logga ut användaren. Här anropar jag samma funktion för att validera gentemot localStorage. Istället hade jag velat få det att funka så att jag bara gjorde ett anrop,

Som grupp bestämde vi oss för att använda oss av BEM men jag märkte att jag av vana inte gjorde det. Hade jag haft mer tid hade jag sett över min kod för att säkerställa att allt är enligt BEM.

#### Om ni hade en vecka till på er, vad skulle du ändrat? Fokusera på arbetsprocessen, samarbetet eller verktygen ni använde. Hur skulle det ha påverkat resultatet?

Samarbetet gick väldigt bra i vår grupp, vi hade en välfungerande daglig rutin som alla verkade nöjda med så det är inte mycket jag have velat ändra egentligen. Något som vi har pratat om är att vi önskar att vi hade gått igenom mer av varandras kod för att verkligen förstå vad alla har gjort. Ett sätt att göra detta hade varit att alltid låta någon annan sköta mergandet eller på annat sätt schemalägga att vi går igenom vår kod och förklarar den.
