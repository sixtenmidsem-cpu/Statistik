# Lecture2Handouts

> Source: `Lecture2Handouts.pdf` (38 pages). Auto-converted from PDF text layer; formulas and multi-column layouts may be imperfect.


---

<!-- page 1 -->

Föreläsning 2: Sannolikhetslärans grunder

        Farrukh Javed, Lund University


              2 september 2026

---

<!-- page 2 -->

                      Inledning till sannolikhetsteori



Vad är sannolikhet?



Vad är sannolikheten för att vinna lotteriet?
Vad är sannolikheten för att det regnar imorgon kväll?
Vad är sannolikheten att Sverige vinner fotbolls-VM 2030?

Sannolikhet (given som en siffra mellan 0 och 1) är ett mått på hur troligt
det är att en viss händelse inträffar:
Antingen utifrån en matematiskt modell (teoretisk), grundad på
erfarenhet/historisk data (relativ frekvens) eller en subjektiv bedömning
(personlig uppfattning).




      Farrukh Javed                              Föreläsning 2           2 / 42

---

<!-- page 3 -->

                     Inledning till sannolikhetsteori



Definitioner




    Utfall: resultat av ett slumpmässigt försök/experiment, s.k.
    elementarhändelse.
    Utfallsrummet: mängden S av alla möjliga utfall.
    Händelse: en samling av utfall, delmängd av S.
    Trädiagram: ett sätt att beskriva utfallsrummet för stegvisa
    slumpexperiment (t.ex. med olika omgångar).




     Farrukh Javed                              Föreläsning 2      3 / 42

---

<!-- page 4 -->

                      Inledning till sannolikhetsteori




Exempel
Låt oss kasta en tärning.




Exempel
Låt oss kasta två likadana tärningar på en gång.




      Farrukh Javed                              Föreläsning 2   4 / 42

---

<!-- page 5 -->

                      Inledning till sannolikhetsteori




Exempel (Trädiagram)
Ett mynt kastas 3 gånger.
Klave betecknas med 0 och krona med 1.
Utfallsrummet kan representeras genom ett träd:




S = {000, 001, 010, 011, 100, 101, 110, 111}


      Farrukh Javed                              Föreläsning 2   5 / 42

---

<!-- page 6 -->

                            Kombinatorik



Kombinatorik




För att kunna hantera sannolikheter på ändliga utfallsrum, är det viktigt
att kunna beräkna antalet elementarhändelser, alltså |S|.

Teorin bakom det – att räkna fram alla olika kombinationer – ingår i
området som kallas kombinatorik.




      Farrukh Javed                Föreläsning 2                            7 / 42

---

<!-- page 7 -->

                               Kombinatorik



Multiplikationsprincipen

Antag att ett slumpexperiment sker i k steg. Låt nj vara antalet möjliga
utfall i steg j ∈ {1, . . . , k}. Utan vidare restriktioner ges då antalet utfall
för hela experimentet som nj = n1 · n2 · . . . · nk (jfr. trädiagram).
Exempel
På en fest var 8 herrar och 9 damer bjudna. Om herrarna dansar enbart
med damer och damerna enbart med herrar, hur många danspar kan det
bildas då?
Tre knep när det gäller att räkna fram kombinationer:
     med repetition eller utan?
     enklare tänka komplement?
     Ifall det finns restriktioner → hantera dem först!


       Farrukh Javed                  Föreläsning 2                                 8 / 42

---

<!-- page 8 -->

                             Kombinatorik



Permutation


Hur många tal kan man bilda med siffrorna {1, 2, 3} utan att repetera en
siffra?
Enligt multiplikationsprincipen finns det 3 · 2 · 1 = 6 möjliga
kombinationer:



Definition
En ordning av en mängd, i vilken alla element är olika, kallas för en
permutation av elementen i mängden.




      Farrukh Javed                 Föreläsning 2                       9 / 42

---

<!-- page 9 -->

                            Kombinatorik



Permutation


För att, i allmänhet, få fram antalet permutationer av N ∈ N element, kan
man tänka så här:
För plats ett har vi N val. För plats två har vi bara N − 1 val, då det
element som står på plats ett redan är taget, osv.
Antalet ordningar blir då:


N! kallas N-fakultet. 0-fakultet definieras som 0! := 1.

Sats
Det finns exakt N! permutationer av N (olika) element.



      Farrukh Javed                Föreläsning 2                      10 / 42

---

<!-- page 10 -->

                                    Kombinatorik



Urval med ordning


Hur många olika tvåsiffriga tal kan man bilda med siffrorna {1, 2, 3, 4, 5}
utan att repetera en siffra?
                                                              5!
Enligt multiplikationsprincipen finns det 5 · 4 = 5·4·3·2·1
                                                    3·2·1 = (5−2)! olika tal.



Sats (urval med ordning)
Antalet sätt, N Pn , att ordna n element som väljs bland totalt N olika är

                 N                                                N!
                       Pn = N(N − 1) · . . . · (N − n + 1) =
                                                               (N − n)!




       Farrukh Javed                       Föreläsning 2                   11 / 42

---

<!-- page 11 -->

                            Kombinatorik



Urval utan ordning

Om man drar två kort ur ett kortspel med 52 olika kort, hur många
kombinationer finns det då för det dragna paret (om ordningen av korten
inte är relevant)?
Enligt multiplikationsprincipen kan vi dra paret på 52 · 51 sätt. Dock
räknar vi då alla par dubbelt (om jag t.ex. drar kung i hjärter och klöver
ess, kan jag dra antingen kungen eller esset först).

Sats (kombination)
Antalet sätt att välja n element från en mängd med N olika element utan
                                     NP      N!
hänsyn till ordningen ges av N Cn = n! n
                                         = (N−n)!n! .

NC                                                    N
     n kallas binomialkoefficient och betecknas med   n .



        Farrukh Javed              Föreläsning 2                         12 / 42

---

<!-- page 12 -->

                             Kombinatorik




Exempel
Hur många olika bokstavskombinationer kan man bilda genom att
permutera bokstäverna av ordet “MAMMA”?




Exempel
En grupp av 5 vänner går till en liten bio och sätter sig i första raden, som
har 7 platser. Hur många olika sätt finns det för dem att fördela sig på
platserna?




      Farrukh Javed                 Föreläsning 2                         13 / 42

---

<!-- page 13 -->

                             Sannolikhet



Definitioner

Låt A, B vara två händelser i ett experiment med utfallsrum S.
    Den tomma mängden ∅ kallas den omöjliga händelsen, S kallas den
    säkra händelsen.
    A betecknar komplementet till händelsen A och omfattar alla utfall
    som inte finns med i A.
    A ∪ B betecknar unionen av båda händelser och omfattar alla utfall
    som finns med i minst en utav A och B.
    A ∩ B betecknar snittet av båda händelser och omfattar alla utfall
    som finns med i både A och B.
    Två händelser A och B är disjunkta (eller oförenliga) om A ∩ B = ∅
    Händelser A1 , A2 , . . . är parvis disjunkta (oförenliga) om
    Ai ∩ Aj = ∅ för alla i 6= j.


      Farrukh Javed                Föreläsning 2                         15 / 42

---

<!-- page 14 -->

                    Sannolikhet



Venn diagram




    Farrukh Javed         Föreläsning 2   16 / 42

---

<!-- page 15 -->

                                Sannolikhet



Kolmogorovs axiomer för sannolikheter


Låt S vara ett utfallsrum, och A, A1 , A2 , . . . godtyckliga händelser.
  1   P(A) ≥ 0
  2   P(S) = 1
  3   Om A1 , A2 , A3 , . . . är parvis disjunkta händelser (alltså Ai ∩ Aj = ∅
      för i 6= j) så gäller           [  X
                                   P     Ai =      P(Ai )




        Farrukh Javed                 Föreläsning 2                           17 / 42

---

<!-- page 16 -->

                             Sannolikhet



Omedelbara konsekvenser


Från Kolmogorovs axiomer följer direkt en hel rad enkla relationer: Låt
A, B ⊆ S vara godtyckliga händelser.

    P(∅) = 0

    P(A) = 1 − P(A)

    P är monoton, dvs. för A ⊆ B gäller: P(A) ≤ P(B).

    0 ≤ P(A) ≤ 1




      Farrukh Javed                Föreläsning 2                          18 / 42

---

<!-- page 17 -->

                            Sannolikhet



Inklusion/Exklusion
    För godtyckliga händelser A, B ⊆ S gäller:
                     P(A ∪ B) = P(A) + P(B) − P(A ∩ B)
    Är A, B disjunkta blir det
                          P(A ∪ B) = P(A) + P(B).



    För godtyckliga händelser A, B, C ⊆ S gäller:
            P(A ∪ B ∪ C ) = P(A) + P(B) + P(C )
                                 −P(A ∩ B) − P(A ∩ C ) − P(B ∩ C )
                                 +P(A ∩ B ∩ C )



     Farrukh Javed                Föreläsning 2                      19 / 42

---

<!-- page 18 -->

                            Sannolikhet




Exempel
Låt oss kasta en häftstift, som landar på huvudet (H) med slh 0.6 och på
sidan (N) med slh 0.4, tre gånger och notera utfallen.


Vad är sannolikheten att den landar på sidan minst en gång?




      Farrukh Javed               Föreläsning 2                       20 / 42

---

<!-- page 19 -->

                             Sannolikhet



Likformig fördelning på ändligt S (Laplace-experiment)



Antag att vi har ett slumpmässigt försök med ändligt många möjliga
utfall, sådant att alla utfall i S har samma sannolikhet. Man säger då att
sannolikheten är likformigt fördelad. Sannolikheten att händelsen A
inträffar ges då av
                                          |A|
                                   P(A) =     ,
                                          |S|
där |M| betecknar antalet element i mängden M (“antalet utfall då A
inträffar genom antalet möjliga”).




      Farrukh Javed                Föreläsning 2                        21 / 42

---

<!-- page 20 -->

                            Sannolikhet




Exempel
Låt oss kasta en symmetrisk tärning.

A =“utfallet är jämnt” och B =“visar fler än 2 ögon”.
Beräkna P(A ∪ B), P(A ∩ B) och P(A ∩ B).




      Farrukh Javed               Föreläsning 2         22 / 42

---

<!-- page 21 -->

                            Betingad sannolikhet



Betingad sannolikhet


Exempel
I en tillverkningsprocess för en viss produkt kontrolleras kvaliteten, och en
produkt klassificeras, för enkelhets skull, som antingen “duglig” eller
“defekt”. Man har data tillgängligt både för en maskin i processen av äldre
typ och en av nyare slag, se tabellen nedan. Totalt valdes ut 300 produkter
slumpmässigt.
                                          Duglig           Defekt   Totalt
                      Äldre maskin         170              10       180
                       Ny maskin           115               5       120
                         Totalt            285              15       300




      Farrukh Javed                        Föreläsning 2                     24 / 42

---

<!-- page 22 -->

                            Betingad sannolikhet




Exempel
                                          Duglig           Defekt   Totalt
                      Äldre maskin         170              10       180
                       Ny maskin           115               5       120
                         Totalt            285              15       300
A =”Slumpvis produkt är duglig”
B =”Slumpvis vald produkt är tillverkad med äldre maskin”
C =”Slumpvis vald produkt är duglig, givet tillverkad med äldre maskin”

P(A) =                och   P(B) =




      Farrukh Javed                        Föreläsning 2                     25 / 42

---

<!-- page 23 -->

                            Betingad sannolikhet




Exempel
                                          Duglig           Defekt   Totalt
                      Äldre maskin         170              10       180
                       Ny maskin           115               5       120
                         Totalt            285              15       300

Händelsen C involverar såväl A som B, och vi skriver C = A|B, där A|B
utläses som ”A, givet B”. Från tabellen ovan kan vi finna genom avläsning
i raden för “Äldre maskin”.
                                                   170   P(A ∩ B)
                       P(C ) = P(A|B) =                =
                                                   180    P(B)




      Farrukh Javed                        Föreläsning 2                     26 / 42

---

<!-- page 24 -->

                        Betingad sannolikhet



Betingad sannolikhet


Att betinga på en händelse A motsvarar då alltså en reducering av
utfallsrummet S på enbart utfall i A. Observera att detta leder till en
förändring i sannolikheterna för andra händelser!

Definition
För två händelser A, B med P(B) > 0 defineras den betingade
sannolikheten för A, givet att händelsen B inträffar genom

                                               P(A ∩ B)
                            P(A|B) =                    .
                                                P(B)




      Farrukh Javed                    Föreläsning 2                      27 / 42

---

<!-- page 25 -->

                        Betingad sannolikhet




Exempel
Låt oss kasta en symmetrisk tärning.
A =“utfallet är jämnt” och B =“visar fler än 2 ögon”.
Vi vet sedan tidigare att P(A) = 21 , P(B) = 23 och P(A ∩ B) = 31 .

Bestäm P(A|B) och P(B|A).




      Farrukh Javed                    Föreläsning 2                  28 / 42

---

<!-- page 26 -->

                           Betingad sannolikhet



Multiplikationsregel



Sats
För två händelser A, B gäller

                   P(A ∩ B) = P(A|B) · P(B) = P(B|A) · P(A).

Med det kan man länka ihop båda betingade sannolikheter:
Sats
                                             P(B|A) · P(A)
                           P(A|B) =                        .
                                                P(B)




       Farrukh Javed                      Föreläsning 2        29 / 42

---

<!-- page 27 -->

                        Betingad sannolikhet




Exempel
I en industrilokal finns ett brandlarm. Det är förhållandevis pålitligt, men
ibland sker falsklarm och en brand kan även missas. Låt B=“Brand i
lokalen” och L=“Larm ljuder” har motsvarande sannolikheter P(B) = 0.05
och P(L|B) = 0.98, och P(L|B) = 0.10. Beräkna P(B|L).




      Farrukh Javed                    Föreläsning 2                     30 / 42

---

<!-- page 28 -->

                          Betingad sannolikhet



Total sannolikhet...

Låt A1 , A2 , . . . , An vara en partition av S (dvs. parvis disjunkta händelser
vars union är hela S) och B en godtycklig händelse. Då gäller följande:
Sats
                                          n
                                          X
                             P(B) =              P(B ∩ Ai ).
                                           i=1




       Farrukh Javed                     Föreläsning 2                        31 / 42

---

<!-- page 29 -->

                          Betingad sannolikhet



... och Bayes formel


Sats (Bayes)
Låt A1 , A2 , . . . , An vara en partition av S och B en händelse med
P(B) > 0. Då gäller för varje j = 1, . . . , n:

                                    P(B|Aj ) · P(Aj )
                       P(Aj |B) = Pn                     .
                                   i=1 P(B|Ai ) · P(Ai )




       Farrukh Javed                     Föreläsning 2                  32 / 42

---

<!-- page 30 -->

                         Betingad sannolikhet




Exempel
En sällsynt sjukdom kan upptäckas med hjälp av ett snabbtest. Vid
pågående infektion ger testet ett positivt resultat i 98% av fallen. Har
personen som testas inte sjukdomen ger testet ett felaktigt positivt
resultat i 0.5% av fallen.
För binära klassifikationstest är sensitivitet och specificitet ett statistiskt
mått för tillförlitligheten av testmetoden.
Här: sensitivitet 98%, specificitet 99.5%.

Antag att bara en utav 10 000 människor som testas lider av sjukdomen
och beräkna sannolikheten att en slumpmässigt utvald, positivt testad
person faktiskt har sjukdomen.




       Farrukh Javed                    Föreläsning 2                       33 / 42

---

<!-- page 31 -->

                           Oberoende händelser



Oberoende


Definition
Två händelser A och B kallas oberoende om och endast om

                            P(A ∩ B) = P(A) · P(B).


Observera att det inte ändrar sannolikheten att betinga på en oberoende
händelse: För oberoende A, B gäller

                      P(A|B) =

Kunskap om att B inträffade tillför alltså ingen extra information om
huruvida A inträffade eller ej.


      Farrukh Javed                      Föreläsning 2                  35 / 42

---

<!-- page 32 -->

                       Oberoende händelser




Exempel
Låt oss kasta en tärning ännu en gång.
A =“utfallet är jämnt” och B =“visar fler än 2 ögon”.

Är dessa händelser oberoende?




      Farrukh Javed                  Föreläsning 2      36 / 42

---

<!-- page 33 -->

                     Monte Hall Problemet



Monte Hall Problem
   På jakt efter en ny bil väljer den tävlande dörr 1 (A).
   Monty väljer nu att visa att bakom dörr 3 (C) finns en get.
   Ska den tävlande byta dörr eller inte?




     Farrukh Javed                  Föreläsning 2                38 / 42

---

<!-- page 34 -->

                     Monte Hall Problemet



Monte Hall Problem




                               På Mentimeter




     Farrukh Javed                  Föreläsning 2   39 / 42

---

<!-- page 35 -->

                     Monte Hall Problemet



Steg I: Prior Sannolikheten
                          Prior: Slh för en bil
                          bakom dörren
                          P(Bil på . . .)


                                                      1
                                     P(Bil på A) =
                                                      3



                                                      1
                                     P(Bil på B) =
                                                      3




                                                      1
                                     P(Bil på C ) =
                                                      3


     Farrukh Javed                  Föreläsning 2         40 / 42

---

<!-- page 36 -->

                           Monte Hall Problemet



Steg II: Prior + Händelse
   Prior: Slh för en bil                  Händelse: Slh att Monty
   bakom dörren                           öppnar dörren B
   P(Bil på . . .)                        (du valde dörren A)
                                          P(Öppnar B | Bil på . . .)∗
                                           ∗
                                               Monty öppnar aldrig en dörr som döljer bilen
                            1
              P(Bil på A) =
                            3
                                                                                      1
                                                  P(Öppnar B | Bil på A) =
                                                                                      2
                                 1
              P(Bil på B) =
                                 3
                                                  P(Öppnar B | Bil på B) = 0




                                 1                P(Öppnar B | Bil på C ) = 1
              P(Bil på C ) =
                                 3

     Farrukh Javed                        Föreläsning 2                                       41 / 42

---

<!-- page 37 -->

                                             Monte Hall Problemet



Steg III: Prior → Posterior Sannolikheterna


 Prior: Slh för en bil        Händelse: Slh att Monty                   Posterior Slh: slh för
 bakom dörren                 öppnar dörren B                           bilens placering efter händelsen
 P(Bil på . . .)              (du valde dörren A)                       P(Bil på . . . | Öppnad B)
                              P(Öppnar B | Bil på . . .)∗

                               ∗
                                 Monty öppnar aldrig en dörr
                               som döljer bilen
                       1                                                                                                    1
                                                                                                                              × 13
                                                                                                                                     
         P(Bil på A) =                                                                                                      2                            1
                       3                                                 P(Bil på A | Öppnad B) =          1
                                                                                                                                                  =
                                                             1                                             2
                                                                                                             × 13       + 0 × 13 + 1 × 13                3
                                    P(Öppnar B | Bil på A) =
                                                             2
                          1
         P(Bil på B) =                                                                                                      0 × 13
                                                                                                                                     
                          3
                                                                         P(Bil på B | Öppnad B) =          1
                                                                                                                                                   =0
                                    P(Öppnar B | Bil på B) = 0                                             2
                                                                                                             × 13       + 0 × 13 + 1 × 13


                                                                                                                                     
                          1                                                                                                 1 × 13                       2
         P(Bil på C ) =             P(Öppnar B | Bil på C ) = 1          P(Bil på C | Öppnad B) =          1
                                                                                                                                                  =
                          3                                                                                2
                                                                                                             × 13       +   0 × 13       + 1 × 13        3




             Farrukh Javed                                     Föreläsning 2                                                                             42 / 42
