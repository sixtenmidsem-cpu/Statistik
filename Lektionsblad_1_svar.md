# Lektionsblad_1_svar

> Source: `Lektionsblad_1_svar.pdf` (4 pages). Auto-converted from PDF text layer; formulas and multi-column layouts may be imperfect.


---

<!-- page 1 -->

Lunds universitet
Ekonomihögskolan
Statistiska institutionen


         STAA40:1 Statistik: Grundkurs, Delkurs 1: Grunder, HT-26
                   STAA41 Statistik: Grundkurs 1, HT-26
                             Svar till Lektion 1
        Beskrivande statistik och Grundläggande Sannolikhetslära

                                             Del I


 1   Centralmått:: C

 2   Medianen och Medelvärdet: C

 3   Standardavvikelse: Genomsnittlig avvikelse blir 2 och s blir 2.53

 4   Standardavvikelse: Medelvärdet blir 5 och s blir 1.2649

 5   Variation:: Rätt svar i ordning är B, C, A, B, A, B, A, A, B, A, A

 7   Jämföra grupper:: a) 75 %, b) mellan 45 och 62 år, c) symmetrisk, d) A=män och
     B=kvinnor, e) Q3-Q1, f) 11 år, g) Påverkas inte av outliers, h) Kvinnor är yngre, i) Ungefär
     samma.




                                                                                   2026-09-03 FJ

---

<!-- page 2 -->

Statistik: Grundkurs 1, HT-26                                                                                   2


                                                      Del II


 1   Utfallsrum och händelse: Det finns 36 utfall:

                             S = {(1, 1), . . . , (1, 6), (2, 1), . . . , (2, 6), . . . , (6, 6)}
                              1
     och alla har samma slh 36  .
                     
                 A = (1, 1), (1, 3), (1, 5), (2, 2), (2, 4), (2, 6), (3, 1), (3, 3), (3, 5),
                         (4, 2), (4, 4), (4, 6), (5, 1), (5, 3), (5, 5), (6, 2), (6, 4), (6, 6)

     Resterande 18 par ingår i A.

 2   Kombinatorik: Gör vi som beskrivet, finns det N ! sätt att ordna N element. Nu tar vi
     dock bara de första n (i sin ordning) och själva ordningen på resterande N − n element
     påverkar inte detta urval med ordning. Vi dubbelräknar alltså varje sådan (N − n)! många
     gånger (antalet ordningar på de element vi inte väljer).
     Om vi bortser från ordningen leder n! olika urval med ordning (permutation) till samma
     urval utan ordning (kombination): Det finns ju exakt n! många sätt att vårt urval. Sym-
     metrin i binomialkoefficienten kan förklaras med att det är likvärdigt att välja n element
     ur en mängd med N olika eller bestämma istället N − n många som inte ska tas.
     Bilarna kan parkeras på 5 · 4 · 3 = 53 · 3! = 60 olika sätt. Antingen man räknar antalet
                                              

     platser varje bil kan välja ifrån, eller så väljer man 3 platser som ska vara upptagna och
     gångrar med antalet sätt man kan parkera 3 olika bilar på dessa valda 3 platser.

 3   de Morgans regler:
     Med B = “den blåa tärningen visar inte fler än 4 prickar” fås
                             
         (A ∪ B) = A ∩ B = (2, 5), (4, 5), (6, 5), (1, 6), (3, 6), (5, 6) .

     Alltså finns det 6 utfall i (A ∪ B), och därmed

           |A ∪ B| = 36 − 6 = 30.

     Således
                           30  5
           P (A ∪ B) =        = .
                           36  6
     Med additionsformeln

           P (A ∪ B) = P (A) + P (B) − P (A ∩ B)

     fås
                           18 24 12   30  5
           P (A ∪ B) =       +  −   =    = .
                           36 36 36   36  6




                                                                                                    2026-09-03 FJ

---

<!-- page 3 -->

Statistik: Grundkurs 1, HT-26                                                                               3



 4   Sannolikhet: Händelserna A och B som definerats ovan är inte disjunkta: t.ex. gör utfallet
     (1, 1) att både A och B inträffar.
     I och med att (A ∪ B) innehåller 6 utfall (se ovan), finns det resterande 36 − 6 = 30 utfall
     i komplementärhändelsen A ∪ B. Då vi utför ett så-kallat Laplace-experiment (alla utfall
     har samma slh) följer det direkt P (A ∪ B) = 30     5
                                                    36 = 6 .
     Alternativt kan vi med |A| = 18, |B| = 24 och |A∩B| = 12 räkna med inklusion/exklusion-
     formeln:
                        P (A ∪ B) = P (A) + P (B) − P (A ∩ B) = 21 + 23 − 31 .

 5   Betingade sannolikheter: Enligt definitionen är

                                               P (A ∩ B)   12/36  1
                                  P (A|B) =              =       = .
                                                 P (B)     24/36  2

     Det är samma som P (A) och innebär att A och B är oberoende händelser.

 6   Total sannolikhet och Bayes sats: Lättast att räkna på är de betingade sannolikheterna
     P (R|U1 ) resp. P (R|U2 ). Om vi nämligen vet vilken urna det drogs ifrån är det ett enkelt
     Laplace-experiment och vi får

                                  P (R|U1 ) = 21    resp. P (R|U2 ) = 41 .

     Med lite fantasi kan man se hela experimentet som att dra från en urna med 8 bollar
     (3 röda, 5 svarta), då myntet är symmtriskt, och slå fast P (R) = 38 . Vi vill dock istället
     använda formeln om total sannolikhet och får då

      P (R) = P (R ∩ U1 ) + P (R ∩ U2 ) = P (R|U1 ) · P (U1 ) + P (R|U2 ) · P (U2 ) = 21 · 12 + 14 · 12 .

     Enligt Bayes sats gäller
                                                                           1 1
                                        P (R|U1 ) P (U1 )                  2 · 2    2
                  P (U1 |R) =                                       = 1 1 1 1 =
                              P (R|U1 ) P (U1 ) + P (R|U2 ) P (U2 )   2 · 2 + 4 · 2
                                                                                    3

     och på samma sätt P (U2 |R) = 1/8   1
                                   3/8 = 3 = 1 − P (U1 |R).

 7   Kluring: Om båda tärningar är vita (och inte går att skilja åt), sammanfaller t.ex. (1, 2)
     och (2, 1) till (1, 2). Nu består S av alla (21) par där den första siffran är mindre eller lika
                                                                                  1
     den andra. Är siffrorna samma (som i (3, 3) t.ex.) är slh fortfarande 36       , om inte (som i
                                               1
     (3, 4) t.ex.), så är slh nu det dubbla 18 , då i så fall två resultat (från första experiment)
     sammanfaller till ett.




                                                                                           2026-09-03 FJ
