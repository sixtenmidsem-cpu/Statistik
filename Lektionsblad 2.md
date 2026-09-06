# Lektionsblad 2

> Source: `Lektionsblad 2.pdf` (4 pages). Auto-converted from PDF text layer; formulas and multi-column layouts may be imperfect.


---

<!-- page 1 -->

Lunds universitet
Ekonomihögskolan
Statistiska institutionen


          STAA40:1 Statistik: Grundkurs, Delkurs 1: Grunder, HT-26
                   STAA41 Statistik: Grundkurs 1, HT-26
                                             Lektion 2
                                           Slumpvariabler

Lektionens mål: Du ska

     • förstå begreppet slumpvariabel,

     • kunna använda en slumpvariabel som modell för att beskriva verkligheten,

     • kunna känna igen följande diskreta fördelningar:
       diskret likformig fördelning, binomialfördelning och Poissonfördelning samt
       hypergeometrisk och geometrisk fördelning,

     • förstå och kunna förklara centrala begrepp som
       sannolikhetsfunktion och fördelningsfunktion,

     • kunna beräkna väntevärdet E(X) och variansen Var(X) för en diskret slumpvariabel med
       känd sannolikhetsfunktion p(x).

Teorin som ni ska arbeta med finns i kursbokens kapitel 5. En slumpvariabel X kan vara diskret
(den har ett ändligt eller uppräkneligt antal möjliga värden) eller kontinuerlig (dess möjliga
värden bildar typiskt ett intervall). Den här lektionen handlar enbart om diskreta slumpvariabler.
Kontinuerliga slumpvariabler arbetar vi med nästa vecka.



 0       Förberedelse: Arbeta i grupper om tre. (I nödfall kan ni vara två, men inte fyra.) Pre-
         sentera er för varandra om ni inte känner varandra sedan tidigare.

 1       Antal 2:or: Av övningsledaren får ni fem tärningar. Fundera först enskilt i 45 sekunder
         på följande fråga:
         Hur många 2:or tror du att gruppen får när ni kastar de fem tärningarna?
         Diskutera sedan i gruppen. Vilka utfall (antal 2:or) är möjliga? Vilket utfall tror ni är
         mest sannolikt? Motivera.

 2       Kasta nu de fem tärningarna och räkna antalet 2:or. Anteckna resultatet. Stämde det med
         er gissning?
         Upprepa försöket nio gånger till, så att ni sammanlagt har tio observationer. Anteckna
         antalet 2:or efter varje försök.

 3       Gör en frekvenstabell över antalet 2:or i de tio försöken. Illustrera sedan tabellen med ett
         stapeldiagram. (Om ni inte vill rita för hand kan ni använda GeoGebra Classic. Öppna
         Kalkylbladsvyn och skriv de möjliga utfallen i den vänstra kolumnen och de observerade
         frekvenserna i den högra. Markera tabellen och välj verktyget Envariabelanalys. Välj ett
         stapeldiagram.)
         Tror ni att de andra grupperna har fått samma resultat som ni? Varför eller varför inte?
         Hur stora skillnader mellan gruppernas resultat väntar ni er?

---

<!-- page 2 -->

Statistik: Grundkurs 1, HT-26                                                                       2



 4     Om ni sammanställde resultaten från samtliga gruppers försök i en gemensam frekvensta-
       bell, hur tror ni att tabellen skulle se ut? Motivera.

 5     Vi kan inte på förhand veta hur många 2:or vi får när vi kastar fem tärningar. Däremot
       känner vi de möjliga utfallen och deras sannolikheter, om tärningarna är oberoende och
       perfekt symmetriska. Om vi definierar X = ”antal 2:or vid kast med fem tärningar”, vilken
       sannolikhetsfördelning är då lämplig att anta för X? Ange fördelningens parametrar och
       motivera.

 6     Med hjälp av GeoGebra kan vi simulera att vi kastar fem tärningar t.ex. 200 gånger. Gå
       tillbaka till kalkylbladet. Radera ev saker som står där sedan tidigare övningar, ställ dig i
       cell A1 och skriv
       =SlumptalBinomialfördelat(5, 1/6)
       Varför 5 och 1/6? Håll muspekaren över det nedre högra hörnet av cellen där det är en
       blå kvadrat så att muspekaren blir ett + och dra sedan det blå hörnet nedåt till rad 20.
       Dra därefter hörnet åt höger till kolumn J. Nu har ni 200 upprepningar av antalet 2:or
       vid kast med fem tärningar.
       För att få en överblick kan ni göra ett stapeldiagram på samma sätt som tidigare: markera
       de 200 värdena, klicka på knappen med ett histogram och välj Envariabelanalys. Är det
       nya diagrammet likt eller olikt det ni gjorde i uppgift 3? Vad är likt och vad är olikt?

 7     Vad tror ni händer med staplarnas relativa höjder och diagrammets form om vi i stället
       gör 500, 1 000 eller 10 000 simuleringar?

 8     Vad är sannolikheten att få exakt två 2:or vid kast med fem tärningar? Använd formel
       (5.12) i formelsamlingen för att räkna ut detta.
       Kontrollera nu beräkningen med GeoGebras sannolikhetskalkylator. Öppna Sannolik-
       hetskalkylatorn, välj Binomialfördelning och ange n = 5 och p = 1/6, där p är sanno-
       likheten att en tärning visar 2. Läs av sannolikheten för X = 2 i tabellen. Stämmer den
       med er beräkning?
       Studera sannolikheterna för alla möjliga utfall. Hur väl stämmer de överens med de relativa
       frekvenserna i era simuleringar? Vad drar ni för slutsats?

 9     Härled en fördelning: Upprepa försöket att kasta fem tärningar tills ni för första gången
       får exakt två 2:or. Anta att försöken är oberoende. Definiera slumpvariabeln Y = antal
       försök som krävs för att få exakt 2:or vid kast med fem tärningar.
       Vilka utfall y är möjliga?
       Vad är sannolikheten att man får exakt två 2:or på första försöket?
       Vad är sannolikheten att det krävs två försök?
       Vad är sannolikheten att det krävs tre försök?
       Kan ni beskriva detta med en formel (sannolikhetsfunktion) p(y) = . . .?

 10*   Hur kan man beräkna E(Y )? Vad tror ni att E(Y ) blir? (Det ligger utanför den här kursen
       att härleda E(Y ) exakt, men ni kan försöka hitta ett ungefärligt värde.)

 11    Kasta nu de fem tärningarna tills ni för första gången får exakt två 2:or. Anteckna anta-
       let försök. Upprepa detta totalt tio gånger. Jämför de tio observerade värdena med den
       teoretiska fördelningen i uppgift 9. Vad stämmer väl och vad stämmer mindre väl?

---

<!-- page 3 -->

Statistik: Grundkurs 1, HT-26                                                                            3



 12    Hur skulle fördelningen för Y se ut om ett lyckat försök i stället var att få exakt fem 2:or?

 13    Hur skulle väntevärdet E(Y ) förändras om ett lyckat försök i stället var att få exakt fem
       2:or? Varför?

 14    Vilken fördelning? Föreslå en sannolikhetsfördelning för X i varje situation. Ange fördelningens
       parametrar och motivera de antaganden som behövs. Om både en exakt modell och en approxi-
       mation är relevanta ska ni ange båda.
         a Du kastar en symmetrisk sexsidig tärning och låter slumpvariabeln X = antal ögon. Vilken
            fördelning har X?
         b Du kastar en symmetrisk sexsidig tärning 20 oberoende gånger och låter slumpvariabeln
            X = antal ettor i de 20 kasten. Vilken fördelning har X?
         c Du singlar en symmetrisk slant en gång och låter slumpvariabeln X = antal kronor. Vilken
            fördelning har X?
         d Du singlar en symmetrisk slant 10 oberoende gånger och låter slumpvariabeln X = antal
            kronor. Vilken fördelning har X?
         e I en golfbag ligger 20 bollar: tolv Nike-bollar och åtta Titleist-bollar. Du drar utan
            återläggning fem bollar. Låt slumpvariabeln X = antal Nike-bollar. Vilken fördelning har
            X?
          f I en golfbag ligger 20 bollar: tolv Nike-bollar, sex Titleist-bollar och två Callaway-bollar.
            Du drar utan återläggning fem bollar. Låt slumpvariabeln X = antal Titleist-bollar. Vilken
            fördelning har X?
         g Ett vinförråd innehåller 20 Bordeauxviner och 80 andra viner. Du väljer utan återläggning
            fem flaskor. Låt slumpvariabeln X = antal Bordeauxviner bland de fem. Vilken fördelning
            har X?
         h Bland de 4 600 studenterna på EHL spelar exakt åtta procent innebandy. Femton studenter
            väljs slumpmässigt utan återläggning. Låt slumpvariabeln X = antal innebandyspelare bland
            de femton. Vilken exakt fördelning har X, och vilken enklare approximation kan användas?
          i Bland Lunds 32 000 studenter spelar exakt åtta procent innebandy. Etthundrafemtio studen-
            ter väljs slumpmässigt utan återläggning. Låt slumpvariabeln X = antal innebandyspelare
            bland dessa. Vilken exakt fördelning har X, och vilken enklare approximation kan användas?
          j En utbildningsadministratör vet att det under en vanlig dag ringer i genomsnitt 1,7 studenter
            per timme. Anta att samtalen inträffar oberoende av varandra med konstant intensitet.
            Låt slumpvariabeln X = antal telefonsamtal under en slumpmässigt vald timme. Vilken
            fördelning har X?
         k Sannolikheten att en student får alla rätt på en STAA41-tentamen är 3/500. Vid ett tenta-
            menstillfälle skriver 300 studenter. Anta att studenternas resultat är oberoende. Vi låter X =
            antalet studenter som får alla rätt. Vilken exakt fördelning har X, och vilken approximation
            kan användas?
          l Enligt en välrenommerad vindrutereparatör inträffar i genomsnitt 1,2 stenskott per 1 000
            körda mil. Anta att stenskotten inträffar oberoende med konstant intensitet per körd mil.
            Du tänker köra 1 500 mil och låter slumpvariabeln X = antal stenskott under färden. Vilken
            fördelning har X?
         m Till ett introduktionsmöte kl. 8.15 kallas 183 studenter. För var och en är sannolikheten att
            komma 80 %, och studenterna antas fatta sina beslut oberoende av varandra. Studierektorn
            har bokat sal MA 2 med 154 platser. Låt slumpvariabeln X = antal studenter som kommer.
            Vilken fördelning har X? Vad är sannolikheten att ingen behöver sitta i trappan och lyssna?




                                                                            2026-09-03 TV / JB / JW
