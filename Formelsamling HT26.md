# Formelsamling HT26

> Source: `Formelsamling HT26.pdf` (6 pages). Auto-converted from PDF text layer; formulas and multi-column layouts may be imperfect.


---

<!-- page 1 -->

LUNDS UNIVERSITET                                                                STAA40:1/STAA41
STATISTISKA INSTITUTIONEN
                                                                                 2026-08-17




Formelsamling till STAA40:1/STAA41

Beskrivande statistik                                                 Variationskoefficient
                                                                                                    
Relativ frekvens                                                              Standardavvikelse
                                                                                                × 100 %                   (3.10)
                                                                                 Medelvärde
                                      Klassens frekvens
      Relativ frekvens för en klass =                     (2.1)
                                              n                       Standardisering
Approximativ klassbredd                                                            xi − x̄
                                                                            zi =                                          (3.11)
      Största datavärde − Minsta datavärde                                            s
                                                          (2.2)
                   Antal klasser                                      Stickprovskovarians
Stickprovsmedelvärde                                                              Pn
                                                                                       (xi − x̄)(yi − ȳ)
          Pn                                                                sXY = i=1                                     (3.12)
               xi                                                                        n−1
      x̄ = i=1                                            (3.1)
            n                                                         Populationskovarians
Populationsmedelvärde                                                                PN
                                                                                        i=1 (xi − μX )(yi − μY )
           PN                                                               σXY =                                         (3.13)
             i=1 xi                                                                              N
      μ=                                                  (3.2)
             N                                                        Pearsons produktmomentkorrelationskoefficient: stickprov
Vägt medelvärde                                                                      sXY
          Pn                                                                rXY =                                         (3.14)
                wi xi                                                               sX sY
     x̄ = Pi=1
             n                                            (3.3)
             i=1 wi                                                   Pearsons produktmomentkorrelationskoefficient: population
Geometriskt medelvärde                                                                σXY
                                                                            ρXY =                                         (3.15)
          √                                                                          σX σY
    x̄g = n x1 × x2 × · · · × xn                          (3.4)

Ordningstal för p:te percentilen                                      Sannolikhetslära
          p 
     i=           n                                                   Fakultet
           100
                                                                            n! = n(n − 1) · · · (1)
Kvartilavstånd
                                                                      Räkneregel för kombinationer
      IQR = Q3 − Q1                                       (3.5)
                                                                                   
                                                                           N        N         N!
Populationsvarians                                                          Cn =        =                                  (4.1)
                                                                                     n    n!(N − n)!
             PN            2
               i=1 (xi − μ)
      σ2 =                                                (3.6)       Räkneregel för permutationer
                    N
                                                                                     
Stickprovsvarians                                                          N          N        N!
                                                                            Pn = n!      =                                 (4.2)
           Pn                                                                         n     (N − n)!
                (xi − x̄)2
      s2 = i=1                                            (3.7)       Sannolikhet för komplement
               n−1
Standardavvikelse                                                           P(A) = 1 − P(Ā)                               (4.5)
                                         √
      Populationsstandardavvikelse = σ = σ2               (3.8)       Additionssatsen
                                        √
       Stickprovsstandardavvikelse = s = s2               (3.9)             P(A ∪ B) = P(A) + P(B) − P(A ∩ B)              (4.6)


                                                                  1

---

<!-- page 2 -->

Betingad sannolikhet                                                      För-första-gången fördelning (geometrisk på N)
                   P(A ∩ B)                                                         p(x) = π(1 − π)x−1 för x = 1, 2, . . .
      P(A|B) =                                                (4.7)
                     P(B)                                                                  1                 1−π
                                                                                   E(X ) = ,      Var(X ) =
Multiplikationssatsen                                                                      π                  π2

      P(A ∩ B) = P(A)P(B|A) = P(B)P(A|B)                     (4.11)       Poissonfördelningen
                                                                                           μx −μ
Multiplikationssatsen för oberoende händelser                                       p(x) =    e   för x = 0, 1, 2, . . .                  (5.15)
                                                                                           x!
      P(A ∩ B) = P(A)P(B)                                    (4.13)                E(X ) = μ,    Var(X ) = μ
Bayes sats                                                                Hypergeometrisk fördelning
                              P(Ai )P(B|Ai )                                             r N −r
                                                                                               
      P(Ai |B) =                                             (4.14)                            x    n−x
                   P(A1 )P(B|A1 ) + · · · + P(An )P(B|An )                            p(x) =       N
                                                                                                           för x = 0, 1, . . . , n†      (5.16)
                                                                                                   n
                                                                                                     r 
Diskreta sannolikhetsfördelningar                                                   E(X ) = μ = n
                                                                                                   N
                                                                                                                                          (5.17)
                                                                                                                     
                                                                                              2
                                                                                                    r    r  N −n
Diskret likformig sannolihetsfunktion                                              Var(X ) = σ = n       1−                               (5.18)
                                                                                                    N       N    N −1
      p(x) = 1/n                                              (5.3)
                                                                          †
                                                                              Egentligen för x = Max[0, n − (N − r)], . . . , Min[n, r]
där n = antal möjliga utfall
Väntevärde
                    X                                                     Kontinuerliga
      E(X ) = μ =       xp(x)                                 (5.4)
                                                                          sannolikhetsfördelningar
Varians
                           X                                              Likformig kontinuerlig fördelning
      Var(X ) = σ2 =           (x − μ)2 p(x)                  (5.5)                      
                                                                                          1       för a ≤ x ≤ b
Kovarians mellan två slumpvariabler X och Y                                       f (x) = b − a                                            (6.1)
                                                                                         0        för övrigt
                                            
     Cov(X , Y ) = σXY = E (X − μX )(Y − μY )
                                                                                             a+b
                   1                                                              E(X ) =
                 = Var(X + Y ) − Var(X ) − Var(Y )            (5.6)                            2
                   2                                                                         (b − a)2
Korrelation mellan två slumpvariabler X och Y                                      Var(X ) =
                                                                                                12
                σXY                                                       Normalfördelning
      ρXY =                                                   (5.7)
               σX σY
                                                                                              1        2    2
Väntevärde av en linjärkombination av slumpvariabler X och                           f (x) = √ e −(x−μ) /2σ                                (6.2)
                                                                                            σ 2π
Y
                                                                                    E(X ) = μ
      E(aX + bY ) = aE(X ) + bE(Y )                           (5.8)                Var(X ) = σ2
Varians av en linjärkombination av slumpvariabler X och Y                 Konvertering till den standardiserade normalfördelningen
                       2              2
   Var(aX + bY ) = a Var(X ) + b Var(Y ) + 2abCov(X , Y ) (5.9)                          X −μ
                                                                                   Z=                                                      (6.3)
Antal experiment med exakt x lyckade försök av n                                           σ
       
        n        n!                                                       Exponentialfördelning
           =                                                 (5.10)
        x    x!(n − x)!                                                                     1 −x/μ
                                                                                     f (x) =  e           för x ≥ 0, μ ≥ 0                 (6.4)
Binomialfördelningen                                                                        μ
                                                                                  E(X ) = μ
                n x
       p(x) =      π (1 − π)n−x för x = 0, . . . , n         (5.12)                Var(X ) = μ2
                x
          E(X ) = μ = nπ                                     (5.13) Fördelningsfunktion för exponentialfördelning
                   2
      Var(X ) = σ = nπ(1 − π)                                (5.14)                F (x0 ) = P(X ≤ x0 ) = 1 − e −x0 /μ                     (6.5)


                                                                      2

---

<!-- page 3 -->

Stickprov och stickprovsfördelningar                                Testfunktion för hypotestest av populationsmedelvärde: σ
                                                                    okänd
Väntevärde för X̄                                                             x̄ − μ0
                                                                          t= √                                             (9.4)
                                                                               s/ n
      E(X̄ ) = μ                                        (7.1)
                                                                    Antal frihetsgrader = n − 1
Standardavvikelse för X̄ (medelfel)                                 Testfunktion för hypotestest av populationsandel
           Ändlig population     Oändlig population                           p − π0
                   r                                                     z=q                                              (9.6)
                 σ      N −n                σ           (7.2)                       π0 (1−π0 )
       σX̄ = √                      σX̄ = √                                              n
                  n     N −1                 n
                                                                    Stickprovsstorlek för ett ensidigt hypotestest av
Väntevärde för P                                                    populationsmedelvärde

      E(P) = π                                          (7.4)                    (zα + zβ )2 σ2
                                                                           n=                                               (9.9)
                                                                                  (μ0 − μ1 )2
Standardavvikelse för P (medelfel)
                                                                    Vid tvåsidigt test ersätts zα med zα/2
          Ändlig
           r population
                     r                Oändligrpopulation
      σP =
             π(1 − π) N − n
                                      σP =
                                               π(1 − π) (7.5)       Statistisk inferens vid två
                 n     N −1                       n
                                                                    populationer
Intervallskattning                                                  Punktskattning av μ1 − μ2

Intervallskattning av populationsmedelvärde: σ känd                        X̄1 − X̄2                                       (10.1)

                σ                                                   Medelfel för X̄1 − X̄2
      x̄ ± zα/2 √                                       (8.1)
                  n
                                                                                     s
                                                                                       σ21  σ2
                                                                         σX̄1 −X̄2 =       + 2                             (10.2)
Intervallskattning av populationsmedelvärde: σ okänd                                    n1  n2

                 s                                                  Intervallskattning av μ1 − μ2 : σ1 och σ2 kända
      x̄ ± tα/2 √                                       (8.2)
                     n                                                                        s
                                                                                                σ21  σ2
Antal frihetsgrader = n − 1                                               (x̄1 − x̄2 ) ± zα/2       + 2                    (10.4)
                                                                                                n1   n2
Stickprovsstorlek för intervallskattning av
populationsmedelvärde                                               Testfunktion för hypotestest av μ1 − μ2 : σ1 och σ2 kända
                                                                                 (x̄1 − x̄2 ) − D0
           (zα/2 )2 σ2                                                     z=       q 2                                    (10.5)
      n=                                                (8.3)                          σ1      σ22
              E2                                                                       n1 + n2

Intervallskattning av populationsandel                              Intervallskattning av μ1 − μ2 : σ1 och σ2 okända
                 r                                                                            s
                     p(1 − p)                                                                   s12   s2
      p ± zα/2                                          (8.6)             (x̄1 − x̄2 ) ± tα/2       + 2                    (10.6)
                        n                                                                       n1   n2

Stickprovsstorlek för intervallskattning av populationsandel        Antal frihetsgrader är
                                                                                                        2
                                                                                                    s22
                                                                                                 2
         (zα/2 )2 π∗ (1 − π∗ )                                                                 s1
                                                                                               n1 + n2
      n=                                                (8.7)              df   =                                         (10.7)
                   E2                                                                      2 2 
                                                                                            s1
                                                                                                                2 2
                                                                                                                 s2
                                                                                      1                    1
                                                                                   n1 −1    n1    +     n2 −1    n2
Hypotesprövning                                                     Testfunktion för hypotestest av μ1 − μ2 : σ1 och σ2 okända
Testfunktion för hypotestest av populationsmedelvärde: σ                         (x̄1 − x̄2 ) − D0
känd                                                                       t=        q2                                    (10.8)
                                                                                       s1      s22
                                                                                       n1 + n2
           x̄ − μ0
      z=       √                                        (9.1)       Antal frihetsgrader ges av (10.7)
           σ/ n

                                                                3

---

<!-- page 4 -->

Testfunktion för hypotestest vid parvisa observationer                  Enkel linjär regression
           d̄ − μd                                                      Enkel linjär regressionsmodell
      t=       √                                           (10.9)
           sd / n
                                                                              Y = β0 + β1 x + ε                                (14.1)
Punktskattning av π1 − π2                                               Enkel linjär regressionsekvation
      P1 − P2                                             (10.10)             E(Y ) = β0 + β1 x                                (14.2)

Medelfel för P1 − P2                                                    Skattad enkel linjär regressionsekvation
                s                                                             ŷ = b0 + b1 x                                   (14.3)
                  π1 (1 − π1 ) π2 (1 − π2 )
     σP1 −P2 =                +                           (10.11)
                       n1           n2                                  Minsta kvadratkriterium
                                                                                  X
Intervallskattning av π1 − π2                                                Min     (yi − ŷi )2                              (14.5)
                          s                                             Skattad riktningskoefficient och intercept
                              p1 (1 − p1 ) p2 (1 − p2 )
      (p1 − p2 ) ± zα/2                   +               (10.13)                   P
                                                                                      (xi − x̄)(yi − ȳ)
                                                                                                          P        P P
                                                                                                            xi yi − xi yi /n
                                   n1           n2                            b1 =                       = P                 (14.6)
                                                                                       P
                                                                                          (xi − x̄)2               P 2
                                                                                                             xi2 −   xi /n
Medelfel för P1 − P2 då π1 = π2 = π
                                                                              b0 = ȳ − b1 x̄                                  (14.7)
                s                   
                             1    1                                     Residualkvadratsumma
     σP1 −P2 = π(1 − π)         +                         (10.14)
                             n1   n2                                                X
                                                                             SSE =      (yi − ŷi )2 = SST − SSR               (14.8)
Poolad skattning av π då π1 = π2 = π
                                                                        Total kvadratsumma
           n1 p1 + n2 p2                                                             X               X       X 2
      p=                                                  (10.15)             SST =     (yi − ȳ)2 =   yi2 −   yi /n           (14.9)
             n1 + n2

Testfunktion för hypotestest av π1 − π2                                 Kvadratsumma för regressionen
                                                                                   X                   X
               (p1 − p2 ) − D0                                               SSR =    (ŷi − ȳ)2 = b1   (xi − x̄)(yi − ȳ)   (14.10)
      z=r                                               (10.16)
              p(1 − p) n11 + n12                                        Relation mellan kvadratsummor

                                                                              SST = SSR + SSE                                 (14.11)
Inferens om populationsvarianser                                        Determinationskoefficient

Intervallskattning av σ2                                                                   SSR     SSE
                                                                              r 2 = R2 =       =1−                            (14.12)
                                                                                           SST     SST
      (n − 1)s2       (n − 1)s2
          2     ≤ σ2 ≤ 2                                   (11.7) Stickprovskorrelationskoefficient
        χα/2           χ1−α/2                                                                 √
                                                                        rXY = (tecken för b1 ) r 2                            (14.13)
Antal frihetsgrader = n − 1
Testfunktion för hypotestest av σ2                                      Medelkvadratfel (skattning av σ2 )
                                                                                                SSE
             (n − 1)S 2                                                       s2 = MSE =                                      (14.15)
      χ2 =                                                 (11.8)                               n−2
                σ20
                                                                        Skattningens medelfel
Antal frihetsgrader = n − 1
                                                                                 √
                                                                                           r
Testfunktion för hypotestest av σ21 = σ22                                                     SSE
                                                                              s = MSE =                                       (14.16)
                                                                                              n−2
         S2
      F = 12                                              (11.10)       Standardavvikelse för b1
         S2
                                                                                       σ
                                                                              σb1 = pP                                        (14.17)
Antal frihetsgrader = n1 − 1 i täljaren och n2 − 1 i nämnaren                         (xi − x̄)2

                                                                    4

---

<!-- page 5 -->

Skattad standardavvikelse för b1                                         Skattad multipel regressionsekvation
                  s
      sb1 = pP                                            (14.18)              ŷ = b0 + b1 x1 + b2 x2 + · · · + bp xp                  (15.3)
                (xi − x̄)2
t-testfunktion                                                           Minsta kvadratkriterium
           b1                                                                      X
       t=                                                 (14.19)             Min     (yi − ŷi )2                                      (15.4)
           sb1
Antal frihetsgrader = n − 2                                              Relation mellan kvadratsummor
Medelkvadratsumma för regressionen
                                                                               SST = SSR + SSE                                          (15.7)
                              SSR
      MSR =                                                (14.20)
                  Antal förklarande variabler                            Förklaringsgrad
F -testfunktion
                                                                                        SSR     SSE
              MSR                                                              R2 =         =1−                                         (15.8)
       F=                                                  (14.21)                      SST     SST
              MSE
Antal frihetsgrader är = 1 i täljaren och n − 2 i nämnaren               Justerad förklaringsgrad
Konfidensintervall för E(Yp )
                                                                                                           n−1      MSE
                    s                                                          adjR 2 = 1 − (1 − R 2 )          =1−                     (15.9)
                      1     (xp − x̄)2                                                                    n−p−1     MST
       ŷp ± tα/2 s     +P                                 (14.22)
                      n       (xi − x̄)2
                                                                         Medelkvadratsumma för regressionen
Antal frihetsgrader = n − 2
Prediktionssintervall för yp                                                                SSR
                                                                               MSR =                                                (15.12)
                   s                                                                         p
                        1    (xp − x̄)2
       ŷp ± tα/2 s 1 + + P                               (14.23)        Medelkvadratfel
                        n      (xi − x̄)2
                                                                                                   SSE
Antal frihetsgrader = n − 2                                                    MSE = s2 =                                           (15.13)
Residual för observation i                                                                        n−p−1

      yi − ŷi                                            (14.24)        F -testfunktion
Standardavvikelse för residual i                                                       MSR
                                                                               F=                                                   (15.14)
                 p
     syi −ŷi = s 1 − hi                                  (14.26)                      MSE

där hi anges i (14.31)                                                   Antal frihetsgrader är p i täljaren och n − p − 1 i nämnaren
Standardiserad residual för observation i                                t-testfunktion
       yi − ŷi                                                                       bi
                                                          (14.28)              t=                                                   (15.15)
        syi −ŷi                                                                      sbi
Första ordningens autokorrelation                                        Antal frihetsgrader = n − p − 1
      εt = ρεt−1 + zt                                     (14.29)        VIF
Durbin-Watsons testfunktion                                                                     1
                                                                               VIF(Xj ) =                                           (15.16)
         Pn
              (et − et−1 )2                                                                  1 − Rj2
     d = t=2Pn 2                                          (14.30)
                t=1 et                                                   Standardiserad residual för observation i
Hävstångseffekt för observation i
                                                                                yi − ŷi
          1  (xi − x̄)2                                                                                                             (15.24)
      hi = + P                                            (14.31)                syi −ŷi
          n   (xi − x̄)2
                                                                         Standardavvikelse för residual i
Multipel regression                                                                       p
                                                                              syi −ŷi = s 1 − hi                                   (15.26)
Multipel regressionsmodell
                                                                  där hi anges i (14.31)
      Y = β0 + β1 x1 + β2 x2 + · · · + βp xp + ε           (15.1) Cookavstånd
Multipel regressionsekvation
                                                                                           (yi − ŷi )2 hi
      E(Y ) = β0 + β1 x1 + β2 x2 + · · · + βp xp           (15.2)              Di =                                                 (15.27)
                                                                                        (p + 1)s2 (1 − hi )2

                                                                     5
