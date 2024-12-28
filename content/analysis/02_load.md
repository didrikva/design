Colors
=======================

Uppgiften handlar om att dokumentera olika sidors laddningstid samt storlek. 

Urval
-----------------------

<a href="https://www.chelseafc.com/en">Chelsea</a> <br>
<a href="https://www.nrm.se/">Naturhistoriska Riksmuseet</a> <br>
<a href="https://www.tesla.com/sv_se">Tesla</a> <br>

Valen av webbplatser grundar sig till större del genom olika större företag. Här väljer jag ett fotbollslag (sport), ett museum (Kultur) samt ett stort företag (Tesla). Alla hemsidorna vill framföra olika saker och är även olika stora företag vilket leder till att det kan vara intressant att jämföra deras laddningstid samt storleken på sidan.

Metod
-----------------------

I webbläsaren Chrome besöktes hemsidan verktyget inspektera användes. Därefter går jag till fliken nätverk och tittar på load.

Resultat
-----------------------
<iframe class="laddning" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRQxe2kllobC6m8e1TcmFRFfNKG5cgcCow3YljM96ZssBccHiP6SrM4nZLoRiiOvkGOq5T0i4zAIYe3/pubhtml?widget=true&amp;headers=false"></iframe>

Chelsea
<img class="flash-img" src="image/../../assets/img/chelsea-design.png">
Förbättring: Använder mycket inhämtade exempel bilder, js osv vilket leder till många requests. Detta påverkar laddningstiden. Utöver detta är sidan stor och man kanske skulle försöka minska på onödig användning av data för att förbättra laddningstid. 

Naturhistoriska museet
<img class="flash-img" src="image/../../assets/img/natur.design.png">
Förbättring: Konkret har jag svårt att nämna en förbättring på sidan då den egentligen är ganska simpel, finns alltid sätt att minska hämtningen av data. 

Tesla
<img class="flash-img" src="image/../../assets/img/tesla.design.png">
Förbättring: Även här är sidan väldigt stor men använder sig inte av lika många requests. Dock är DOM content tiden väldigt hög och finns nog sätt att förbättra laddningen av DOM. 


Analys
-----------------------

<br>
Chelsea hämtar mycket data från utstående sidor vilket påverkar laddningstiden då dem måste hämtas samt läsas in. Sidan är generellt ganska stor och det påverkar alltid laddningstiden. DOM content är snabbinläst så jag vill mest påstå att hämtandet av data borde minskas för att förbättra laddningstid. Sen är det förståeligt varför mycket data måste hämtas då det är en sportklubb som behöver hämta information, bilder och liknande från andra källor. 
<br>
<br>
Naturhistoriska museet är som nämnt tidigare en väldigt simpel sida egentligen med mycket bilder och simplare texter. Dock hämtas även här väldigt mycket av den lilla data som finns hämtas mer än hälften. Optimicering av denna data kan hjälpa med överföringen.
<br>
<br>
Tesla har stora bilder som inte är helt optimicerade alltid utan kan behöva komprimeras för att förbättra laddningstiden. Här skickas inte alls lika mycket data över men totalstorleken på sidan är ganska stor. Stora filer leder även till längre laddningtid. Möjligtvis förbättring och komprimering av kod kan hjälpa till att ladda sidan snabbare. 

Vinnare
-----------------------
1. Naturhistoriska
2. Chelsea
3. Tesla

Kommentar: Naturhistoriska är den minsta sidan men samtidigt laddas in snabbast. Har få requests och bilderna verkar vara bra komprimerade. 

Gräns för laddningstid
-----------------------
Jag vill påsta en snabb hemsida är allt under 2 sekunder. Långsammare hemsidor där man tänker på att sidan laddas låmngsamt är runt 5 sekunder skulle jag påstå.
<br>
<br>
Utgår man ifråna mina åsikter är ingen av mina utvalda sidor "långsamma" men endast Naturhistoriska klarar sig som en snabb sida. Jag tyckte inte någon av sidorna laddar direkt långsamt och man klarar av laddningstiden utan att tänka på det.


Referenser
-----------------------

Ange de eventuella referenser du använder dig av, om några.

Övrigt
-----------------------

Didrik.