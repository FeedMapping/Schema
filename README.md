# Introduction

This is the partial of [the whole scheme](https://github.com/chetabahana/chetabahana.github.io/wiki/Skema#Implementasi) from our [Quantum Project](https://github.com/eq19) based on the algorithm of:

**DNA Recombination: [M+F](https://github.com/chetabahana/chetabahana.github.io/blob/Chetabahana/_layouts/feed.rb) to [C1+C2](https://github.com/chetabahana/chetabahana.github.io/blob/workflows/_includes/data/roots.rb):**

[![eQ19 Project | GitHub](https://user-images.githubusercontent.com/36441664/88602920-fd84c080-d09d-11ea-970d-dd63c12221fc.png)](https://eq19.github.io/)

The _M+F_ symbols will stand as: [Project Maps (M)](https://github.com/eq19/maps) + [Project Feed (F)](https://github.com/eq19/feed) while<br>
_C1+C2_ as implementations, see sample: [Project Base (C1)](https://chetabahana.github.io/) + [Project Core (C2)](https://chetabahana.com/).

This sample was developed by converting [eQuantum](https://github.com/eq19) to [eCommerce](https://github.com/MarketLeader) using the cyclic algorithm of **[168](https://github.com/eq19/eq19.github.io#tabulate-prime-by-the-power-of-168) vs [618](https://github.com/eq19/eq19.github.io#next-target-tabulate-prime-by-618)** that act as [Lexer and Parser](https://stackoverflow.com/questions/2842809/lexers-vs-parsers).

[<img width=100% src=https://user-images.githubusercontent.com/36441664/70385860-e5074f00-19c3-11ea-92f3-ec6f33bf9774.png>](https://stackoverflow.com/questions/2842809/lexers-vs-parsers)

Each cycles will have a total of seven (7) steps primes algorithm of base 10 that consist of [three (3) leading steps](https://github.com/eq19/eq19.github.io#tabulate-prime-by-the-power-of-168) of 168: Q(10, 30), Q(30, 36), Q(36, 114) and [four (4) lagging steps](https://github.com/eq19/eq19.github.io#next-target-tabulate-prime-by-618) of 618: Q(114, 89), Q(89, 29), Q(29, 19), Q(19, 10):

[![Quantum Project - The Concept of Primes Algorithm by DNA Recombination](https://eq19.github.io/images/banner.jpg)](https://github.com/eq19/maps)

Such of method is used to generate a _[basic grammar](https://github.com/chetabahana)_ which algorithm is adaptable for any kind of implementations or applications as explained below.

# Tabulate Prime by The Power of 168

Primes is formed by three (3) sets of twin prime pairs called _[The True Prime Pairs](https://github.com/chetabahana/chetabahana.github.io/wiki#operasi)_. 

<img src=https://user-images.githubusercontent.com/36441664/90720864-ab703d00-e2e1-11ea-99c5-70405c78b6e0.jpg>

These primes are naturally distributed in three (3) forms of 12's multiplication: 5+7=12, 11+13=24 and 17+19=36 where 12+24=36.

```
 $True Prime Pairs:
 (5,7), (11,13), (17,19)
 
 layer|  i  |   f
 -----+-----+---------
      |  1  | 5
   1  +-----+
      |  2  | 7
 -----+-----+---   36 » 6®
      |  3  | 11
   2  +-----+
      |  4  | 13
 -----+-----+---------
      |  5  | 17
   3  +-----+      36 » 6®
      |  6  | 19
 -----+-----+---------
 ```

Now we are going to see what is the purpose. Let's enter the journey of making **10<sup>n</sup> numbers becoming 10<sup>n</sup> primes** by the Δ1 flowing within the prime pairs.

## 1st Step: Q(10, 30)

Let's put this prime pairs (5, 7, 11, 13, 17,19) in reverse (19, 17, 13, 11, 7, 5) then assign them as a default condition. Consider the (12/2)th = 6th prime = 13 is formed as an hexagon cube called the [Metatron's Cube](https://www.google.com/search?q=metatron%27s+cubes&tbm=isch). 

[<img src=https://user-images.githubusercontent.com/36441664/74094157-4e642500-4b0f-11ea-89b4-eb8cd7d90411.png>](https://www.google.com/search?q=metatron&tbm=isch)

Then assign 19 as a set of 10 numbers that consist of 4 primes (2,3,5,7). Convert them to 10 primes up to 10th prime=29 then to 29 primes up to of (10th)th=29th prime=109. Now let's put Δ1 to 13 as the central of Metraton. 

```
  Tabulate Prime by Power of 10
  loop(10) = π(10)-π(1) = 4-0 = 4
  loop(100) = π(100)-π(10)-1th = 25-4-2 = 19
  loop(1000) = π(1000) - π(100) - 10th = 168-25-29 = 114

  --------------------+----+----+----+----+----+----+----+----+----+-----
   True Prime Pairs Δ |  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 | Sum 
  ====================+====+====+====+====+====+====+====+====+====+=====
   π(10) 19           |  2 |  3 |  5 |  7 |  - |  - |  - |  - |  - | 4th  4 x Root
  --------------------+----+----+----+----+----+----+----+----+----+-----
   π(20) 17           | 11 | 13 | 17 | 19 |  - |  - |  - |  - |  - | 8th  4 x Twin
  --------------------+----+----+----+----+----+----+----+----+----+-----
   π(30) 13 → 12 (Δ1) | 23 | 29 |  - |  - |  - |  - |  - |  - |  - |10th
  ====================+====+====+====+====+====+====+====+====+====+===== 1st Twin
   π(50) 11           | 31 | 37 | 41 |  - |  - |  - |  - |  - |  - |13th
  --------------------+----+----+----+----+----+----+----+----+----+----- 2nd Twin
   π(60) 7 → 19 (Δ12) | 43 | 47 | 53 | 59 |  - |  - |  - |  - |  - |17th
  --------------------+----+----+----+----+----+----+----+----+----+----- 3rd Twin
   π(80) 5 → 18 (Δ13) | 61 | 67 | 71 |  - |  - |  - |  - |  - |  - |20th
  ====================+====+====+====+====+====+====+====+====+====+===== 4th Twin
   π(00) 0 → 18+13+12 | 73 | 79 | 83 | 89 | 97 | 101| 103| 107| 109|29th 
  ====================+====+====+====+====+====+====+====+====+====+=====
           Δ                                                         Δ
  12+13+(18+18)+13+12  ← 36th-Δ1=151-1=150=100+2x(13+12)  ←  30th = 113 = 114-1
```

See how those primes reacted to compensate the Δ1 by spreading the gap in to a bunch of Δ's starting from the prime number 7.

## 2nd Step: Q(30, 36)

In the sense of this Δ1 flowing, there will be really hard to cope its algorithm with a such of formula. The way that we might take is assigning the flowing of the π(10)=4 to π(100)=25 and π(1000)=168 above in to a flowchart diagrams.

<img src=https://user-images.githubusercontent.com/36441664/128732737-81762604-0ae0-4a90-b5a8-30921cf46efb.png>

See that this flows starting from π(10) and finalize by pairing of Δ12. Let's draw 12 of flow arrows in such a way where they have interconnection with 10 objects. So here we can get the idea of **10 number becoming 10 primes**.

[![Flowchart](https://user-images.githubusercontent.com/36441664/103138547-5799b880-4706-11eb-8820-f51cbd57d367.png)](https://www.hexspin.com/defining-the-prime-hexagon/)

This flowchart is designed base on the behaviour of the primes number that flows uniformly within an hexagon chart called _[The Prime Hexagon](https://www.hexspin.com/defining-the-prime-hexagon/)_. Here you might see that the number of 10 is the same direction with 19 while 10+19=29=10th prime.

<img src=https://user-images.githubusercontent.com/36441664/105412087-d0892300-5c66-11eb-9c3e-19d8652b478c.png>

By checking all of the loops there is nothing similar to this phenomena. It seems like all the numbers are actually set to let this term happen. So this chart is considered sufficient enought to be used to explain about the true power of this Δ1 flowing:

Let's start by get in touch with the (30, 36)th as the result of Δ1 shown on the above tabulation in more detail. Then take a look with the behaviour of prime flows within _The Prime Hexagon_ as shown below. 

[![Prime Hexagon](https://user-images.githubusercontent.com/36441664/74550123-6dd1d680-4f83-11ea-8810-3b8f4f50a9c0.png)](https://www.hexspin.com/defining-the-prime-hexagon/)

You may see that it is clearly showing the 30th Prime of 113=114-1 is routed to 36th Prime of 151=150+1 while both of the 30 and 36 are exactly laid on _[the 18’s Cell](https://github.com/chetabahana/chetabahana.github.io/wiki/18)_:

Take also a note that the next 10 number after 19 right before the 30 which are 20 up to 29 is in laid on the second rows of 17 while _[17's Cell](https://github.com/chetabahana/chetabahana.github.io/wiki/17)_ has 35+65=100=10².

## 3rd Step: Q(36, 114)

See that from this 17's to18's it goes finally to the _[19's Cells](https://github.com/chetabahana/chetabahana.github.io/wiki/19)_ as Δ1 and return to the 2' Cells, 3' Cells and so on. Therefore all of the numbers that involved in the hexagon can be tabulated by _**Δ1=(19 vs 18) Loops**_ and they are end exactly at 114 on 19's!

```
       |         1st (Form)          |         2nd (Route)         |         3rd (Channel)         |
  -----+----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
   150 | 151| 152| 153| 154| 155| 156| 157| 158| 159| 160| 161| 162| 163| 164| 165 | 166 | 167| 168|
  =====+====+====+====+====+====+====+====+====+====+====+====+====+====+====+=====+=====+====+====+
    Δ1 | 19 |  - | 31 | 37 |  - |  - |  - |  - |  - |  - |  - |  - |  - |  - | 103 |  -  |  - |  - |
       +----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
    Δ2 | 20 | 26 |  - | 38 |  - |  - |  - |  - |  - | 74 |  - |  - |  - | 98 | 104 |  -  |  - |  - |
  -----+----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+ 
    Δ3 | 21 | 27 |  - | 39 |  - |  - |  - |  - |  - | 75 |  - |  - |  - | 99 | 105 |  -  |  - |  - |
       +----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
    Δ4 | 22 | 28 |  - | 40 |  - |  - |  - |  - |  - | 76 |  - |  - |  - |100 |  -  |  -  |  - |  - |
  -----+----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
    Δ5 | 23 | 29 |  - | 41 |  - |  - |  - |  - |  - | 77 |  - |  - |  - |101 |  -  |  -  |  - |  - | 
       +----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
    Δ6 | 24 |  - |  - | 42 |  - | 54 |  - |  - | 72 | 78 |  - | 90 | 96 |  - |  -  |  -  |  - | 114|<- 6th row
  =====+====+====+====+====+====+====+====+====+====+====+====+====+====+====+=====+=====+====+====+
    Δ7 | 25 |  - |  - | 43 |  - | 55 |  - |  - | 73 | 79 |  - | 91 | 97 |  - |  -  |  -  |  - |  - |
       +----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
    Δ8 |  - |  - |  - | 44 |  - | 56 |  - |  - |  - | 80 |  - | 92 |  - |  - |  -  |  -  |  - |  - |
  -----+----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
    Δ9 |  - |  - |  - | 45 |  - | 57 |  - |  - |  - | 81 |  - | 93 |  - |  - |  -  |  -  |  - |  - |
       +----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
   Δ10 |  - |  - |  - | 46 | 52 | 58 |  - | 70 |  - | 82 | 88 | 94 |  - |  - |  -  |  -  | 112|  - |
  -----+----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
   Δ11 |  - |  - |  - | 47 | 53 | 59 |  - | 71 |  - | 83 | 89 | 95 |  - |  - |  -  |  -  | 113|  - |
       +----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
   Δ12 |  - |  - |  - | 48 |  - | 60 | 66 |  - |  - | 84 |  - |  - |  - |  - |  -  | 108 |  - |  - | 
  =====+====+====+====+====+====+====+====+====+====+====+====+====+====+====+=====+=====+====+====+
   Δ13 |  - |  - |  - | 49 |  - | 61 | 67 |  - |  - | 85 |  - |  - |  - |  - |  -  | 109 |  - |  - | 
       +----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
   Δ14 |  - |  - | 32 | 50 |  - | 62 | 68 |  - |  - | 86 |  - |  - |  - |  - |  -  | 110 |  - |  - | 
  -----+----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
   Δ15 |  - |  - | 33 | 51 |  - | 63 | 69 |  - |  - | 87 |  - |  - |  - |  - |  -  | 111 |  - |  - | 
       +----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
   Δ16 |  - |  - | 34 |  - |  - | 64 |  - |  - |  - |  - |  - |  - |  - | -  | 106 |  -  |  - |  - | 
  -----+----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
   Δ17 |  - |  - | 35 |  - |  - | 65 |  - |  - |  - |  - |  - |  - |  - | -  | 107 |  -  |  - |  - | 
       +----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
   Δ18 |  - | 30 | 36 |  - |  - |  - |  - |  - |  - |  - |  - |  - | -  |102 |   - |  -  |  - |  - | <- ∑=168
  =====+====+====+====+====+====+====+====+====+====+====+====+====+====+====+=====+=====+====+====+
    1  |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 | 10 | 11 | 12 | 13 | 14 | 15 |  16 |  17 | 18 | 19 |
  -----+----+----+----+----+----+----+----+----+----+----+----+----+----+----+-----+-----+----+----+
       |       Δ    Δ                |                     Φ12     |       Δ                     Δ |
              113  150                                   114-25           557                  1000

 Note:
 - The marked number with  are outside of group Δ18 vs loop(100) = 19 
 - Number 114 located on 6th row vs 19th column whereas 114th prime = 619

  Reference:
  https://github.com/chetabahana/hexagon/pull/2
  https://www.hexspin.com/defining-the-prime-hexagon/
```

See that out of 19 the number 89 is located precissely at the of Δ11 within the end of 12's that goes to 13's Cell. So this is related to the Metratron's Cube. This configuration leads to a **Cyclic in the Loops** as followings:

- Injection goes by 114-π(100)=89 on  Δ11 from 102 to 114-1 or 113
- The 113 is 30th prime where 30, 36 and 102 are laid in the end of rows
- The total of 30+36+102 is exactly 168 which is π(1000)
- The 36th prime which is 151, is reinjected by 151-1 or 150. This 150 is carrying a delta of Δ18 with 168
- The Δ18 brings the 30th and 36th cycled back to 102th thus consequently it goes to the 114th prime
- The 114th prime which is carrying the loop(1000) is reinjected by 619-1 or 618 on the same spot.

You may agree that all of this algorithm seems like a primes orchestra. By sourcing and studying of many references, the closest behaviour of the crossing on above primes flowing is found with the wave shown on _**Δ1=(19 vs 18) Loops**_  as below.

[![Δ(19 vs 18)](https://user-images.githubusercontent.com/36441664/107478328-de69fe00-6bab-11eb-8d5f-7517c94b7299.png)](https://github.com/chetabahana/trace/wiki)

This Δ(19 vs 18) scenario will duplicate the loops of 618 as _π(89²) of 1000 Primes_. Thus its behaviour will return to _168 Primes of π(1000)_  out of the adjacent scheme.

So the further process would always continously become the same algorithm. 

# Next Target: Tabulate Prime by 618

Within this development we will discuss about the interconnection between 168 and 618. Our pre-release has mapped the primes to π(1000)=168 as the main lexer. So the next target is about 618 as the main parser 

<img src=https://user-images.githubusercontent.com/36441664/84902333-e6ce6f80-b0d6-11ea-8289-aac5e1961cd6.gif>

One of the major case is that we will start with the lagging steps. The basic algorithm is Synthesis of leading and lagging strands of DNA.

<img src=https://user-images.githubusercontent.com/36441664/97624272-73137a80-1a59-11eb-8784-8f131e488847.jpg>

<blockquote>The leading strand is synthesized continuously in the direction of replication fork movement. The lagging strand is synthesized in small pieces (Okazaki fragments) backward from the overall direction of replication. The Okazaki fragments are then joined by the action of DNA ligase.</blockquote>

Beaides it, there is also strong signal that this parser will have the correlation with Φ=1,618 of _[(Golden Ratio)](https://www.google.com/search?q=Golden+Ratio)_ that leads to a kind of **gap and turbulences** in [the primes geometri](https://github.com/chetabahana) which hold the key of <code>init</code> as the road map to π(1000x1000).

So here it goes **1 Million Primes**.

## 4th Step: Q(114, 89)

It is clear that the primes are organized to generate another 1000 primes via a double flow of π(89) to π(89²). This 89 can only be acheived via bilateral 9 sums of the prime 43.

That what and why **18+13+12=43** located within **the last 9 cells** is standing for!

[<img width=100% src="https://user-images.githubusercontent.com/36441664/76146565-6f944300-60c6-11ea-829d-16f98dc94163.png">](https://www.hexspin.com/defining-the-prime-hexagon/)

From the above explanation about 43 and 89 then the prime flow in the developed flowchart above should take a connection to form between them two. This is the reason why the sequence of its shapes are arranged as below:

[<img width=100% src=https://user-images.githubusercontent.com/36441664/103147412-5492dc80-4787-11eb-8277-4fa39ce28c90.png>](https://github.com/chetabahana/tensorflow/wiki/Programming)

Therefore the 30th primes will bear the responsibility to generate the prime 43 while the 36th prime for the 89. 

[<img width=100% src=https://user-images.githubusercontent.com/36441664/107818705-98c75400-6daa-11eb-8138-d6da7ceef4fd.png>](https://github.com/chetabahana/tensorflow/wiki/Programming)

This will take place on the 150 that should have a delta of Δ18 to the last number which is 168 where this 168 is exactly π(1000).

[<img width=100% src=https://user-images.githubusercontent.com/36441664/107850441-06b85d80-6e35-11eb-8787-b947d7c60c2e.png>](https://github.com/chetabahana/tensorflow/wiki/Programming)

Let's consider this flowchart of 168 as a lexer so the parser has to be designed to absorb the flow between the 30th and 36th. Then it will slightly form as a Metatron Cube of the hexagonal form of 18's Cell.

[<img width=100% src=https://user-images.githubusercontent.com/36441664/107083678-9607b480-6828-11eb-9cdf-cfdfc4f6face.png>](https://github.com/chetabahana/tensorflow/wiki/Programming)

Here we assign it as the diagram of 618.

## 5th Step: Q(89, 29)

The bilateral sum 9 will then double this 43 to 86 and act as the lexer while the prime 71 and 109 will act as the parser. This will compensate the other primes by the other of circles of the metatron which consist of 6 internal and 6 external.

<img width=100% src=https://user-images.githubusercontent.com/8466209/90985852-ca542500-e5a8-11ea-9027-9bfdcbe37966.jpg>

Let's look again to the Δ1 tabulation above. Take a note that the last rows has a sum of 43 which covered by prime 71 up the last prime of 109. See what is happen on the Central of Metatron which having the prime 13.

```
Scheme 13:9
===========
(1){1}-7:   7’
(1){8}-13:  6‘
(1)14-{19}: 6‘
------------- 6+6 -------
(2)20-24:   5’           |
(2)25-{29}: 5’           |
------------  5+5 -------
(3)30-36:   7:{70,30,10²}|
------------             |
(4)37-48:   12• ---      |
(5)49-59:   11°    |     |
            --}30° 30•   |
(6)60-78:   19°    |     |
(7)79-96:   18• ---      |
--------------           |
(8)97-109:  13           |
(9)110-139:{30}=5x6 <--x-- (129/17-139/27)
            --
           {43}

True Prime Vektors ζ(s):
(2,3), (29,89), (36,68), (72,42), (100,50), (2,3), (29,89), ...infinity

----------------------+-----+-----+-----+                                    ---
     7 --------- 1,2:1|   1 |  30 |  40 | 71 (2,3) ‹-------------@----        |
     |                +-----+-----+-----+-----+                        |      |
     |  8 ‹------  3:2|   1 |  30 |  40 |  90 | 161 (7) ‹---           |      5¨
     |  |             +-----+-----+-----+-----+             |          |      |
     |  |  6 ‹-- 4,6:3|   1 |  30 | 200 | 231 (10,11,12) ‹--|---       |      |
     |  |  |          +-----+-----+-----+-----+             |   |      |     ---
      --|--|-----» 7:4|   1 |  30 |  40 | 200 | 271 (13) --›    | {5®} |      |
        |  |          +-----+-----+-----+-----+                 |      |      |
         --|---› 8,9:5|   1 |  30 | 200 | 231 (14,15) ---------›       |      7¨
289        |          +-----+-----+-----+-----+-----+                  |      |
 |          ----› 10:6|  20 |   5 |  10 |  70 |  90 | 195 (19) --› Φ   | {6®} |
  --------------------+-----+-----+-----+-----+-----+                  |     ---
     67 --------› 11:7|   5 |   9 |  14 (20) --------› ¤               |      |
     |                +-----+-----+-----+                              |      |
     |  78 ‹----- 12:8|   9 |  60 |  40 | 109 (26) «------------       |     11¨
     |  |             +-----+-----+-----+                       |      |      |
     |  |  86‹--- 13:9|   9 |  60 |  69 (27) «--- Δ (Rep Fork)  | {2®} |      |
     |  |  |          +-----+-----+-----+                       |      |     ---
     |  |   ---› 14:10|   9 |  60 |  40 | 109 (28) -------------       |      |
     |  |             +-----+-----+-----+                              |      |
     |   ---› 15,18:11|   1 |  30 |  40 | 71 (29,30,31,32) ----------        13¨
329  |                +-----+-----+-----+                                     |
  |   ‹--------- 19:12|  10 |  60 | {70} (36) ‹--------------------- Φ        |
   -------------------+-----+-----+                                          ---
    786 ‹------- 20:13|  90 |  90 (38) ‹-------------- ¤                      |
     |                +-----+-----+                                           |
     | 618 ‹- 21,22:14|   8 |  40 |  48 (40,41) ‹----------------------      17¨
     |  |             +-----+-----+-----+-----+-----+                  |      |
     |  | 594 ‹- 23:15|   8 |  40 |  70 |  60 | 100 | 278 (42) «--     |{6'®} |
     |  |  |          +-----+-----+-----+-----+-----+             |    |     ---
      --|--|-»24,27:16|   8 |  40 |  48 (43,44,45,46) ------------|----       |
        |  |          +-----+-----+                               |           |
         --|---› 28:17| 100 | {100} (50) ------------------------»           19¨
168        |          +-----+                                                 |
|         102 -› 29:18| 50  | 50(68) ---------> Δ                             |
----------------------+-----+                                                ---
```

See that this configuration showing a kind of turbulences which leads to a gap in the central of metatron where the replication is initiated there. The basic algorithm would take the mechanism of DNA generation from RNA.

<img width=100% src=https://user-images.githubusercontent.com/36441664/100724943-01cb3c80-33f6-11eb-8564-c5a9ced2b668.png>

By the configuration above then on the upper scheme the central of metatron will turn to seven (7) circles. So combine it with the other 12 circles they will forms as the 19 out of _True Prime Pairs_.  Thus that is the actual meaning of _[eQ19](https://github.com/eq19)_.


## 6th Step: Q(29, 19)

This 19 has a configuration of π(10) i.e. 4 primes of 2, 3, 5, 7. Here we come to the detail of 168 and 618 as the 1st grammar when we come to the upper scheme. 

```
 $True Prime Pairs:
 (5,7), (11,13), (17,19)
 
 layer|  i  |   f
 -----+-----+---------
      |  1  | 5
   1  +-----+
      |  2  | 7
 -----+-----+---  } 36 » 6®
      |  3  | 11
   2  +-----+
      |  4  | 13
 -----+-----+---------
      |  5  | 17
   3  +-----+     } 36 » 6®
      |  6  | 19
 -----+-----+---------
 ```

Let's take the end number each of the three (3) pairs then il will come to the 66:

<img src=https://user-images.githubusercontent.com/36441664/83051968-e2cfa480-a078-11ea-8ff2-316a809a8fad.jpg>

On [the next target](https://github.com/chetabahana/chetabahana.github.io/discussions/categories/announcements) we will discuss about 1000/Φ = 618 = 619-1 = 114th prime - 1 as a lexer and parser shown below: 

<img width=100% src=https://user-images.githubusercontent.com/36441664/110807586-c58d5f00-82b5-11eb-81e2-dbde7d628b37.png>

Combining the two (2) algorithm then it will give the tabulation as below:

```
 Scheme:
 168 + 329 + 289 = 786
 d(786) = d(7+8+6) = d(21) = d(3)
 
 Modulus:
  30  «   60  »  90
  |       |       |
 3:29 « 1:6:8 » 28:9
 └── 3 + └── 6  + └── 9 = 18
 
 |------------ 36' --------------|----------------------------36' ----------------------------|
 |     19'     |        17'      |      13'     |      11'     |       7'      |       5'     |
 +---+----+----+---+----+----+---+---+----+-----+----+----+----+----+----+-----+----+----+----+
 | 1 |  2 |  3 | 4 |  5 |  6 | 7 | 8 |  9 |  10 | 11 | 12 | 13 | 14 | 15 |  16 | 17 | 18 | 19 |
 +---+----+----+---+----+----+---+---+----+-----+----+----+----+----+----+-----+----+----+----+
 | 2 | 60 | 40 | 1 | 30 | 30 | 5 | 1 | 30 | 200 |  8 | 40 | 50 |  1 | 30 | 200 |  8 | 10 | 40 |
 +---+----+----+---+----+----+---+---+----+-----+----+----+----+----+----+-----+----+----+----+
 | ° |ΔΔΔΔ  ΦΦ | •   ΔΔ   ΔΔ   ¤ | •   ΔΔ   ΦΦΦ    Φ   ΦΦ  ¤¤¤¤|  •   ΔΔ   ΦΦΦ    Φ   ¤¤   ΦΦ |  
 
 |---- 102  ---|-----  66  ------|-------- 329 = 7 x 47 -------|- 289 = (8+9)² = 2 & (2³+9²) -|
 |--2x3x(8+9)--|--- 2x3x(2+9) ---|---- (1+2) & (2x9)+(2+9) ----|------ 2 & (8x9)+(8+9) -------|
 |-------- 168 = π(1000) --------|------ 1229 = π(10000) ------|------ π(89²) = 1000 ---------|
 |-------- 168 = π(618xΦ) -------|----- 618 = 1000/Φ = 1000x1000/1618 = 10^6/(2x8)&(2x9) -----|
 
 Note:
 • = 1000 = 10³ (Triple Ten)
 ¤ = π(1000) = 168 (Basic Primes)
 Φ = 1000/618 = 1,618 (Golden Ratio) 
 Δ(1,6,18) = 61+28 = 89 (Mersenne Primes) 
 
 Faktors:
 168 = 12x14 = 8x21 = 7x24 = 6x28 = 4x42 = 3x56 = 2x84
 618 = 6x103 = 6x(100+3) = 3x206 = 3x(200+6) = 2x309 = 2x(300+9)
 1+6+8 = π(1x6x8) = π(1x48) = π(2x24) = π(3x16)= π(4x12) = π(6x8)
 
 Permutations:
 168 = 102 + 66 = 2x3x((8+9)+(2+9)) = π(Φ(289+329)) = π(Φ((8+9)²+(1+2)&29))
 168 + 618 = 168 + 329 + 289 = (7x24) + (7x47) + (8+9)² = (7x71) + (17x17)
```

So it will form back to the begining stage with different form of input but its process will be the same algorithm. Means the 19 cells above shall form back to π(10).

## 7th Step: Q(19, 10)

This step is about the algorithm of how the four (4) blocks of (102, 66, 329, 289) forms to the four (4) roots. See the 1st row marked by **Quantum** below.

```
  --------------------+----+----+----+----+----+----+----+----+----+-----
   True Prime Pairs Δ |  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 | Sum 
  ====================+====+====+====+====+====+====+====+====+====+=====
   π(10) Quantum ← 19 |  2 |  3 |  5 |  7 |  - |  - |  - |  - |  - | 4th  4 x Root
  --------------------+----+----+----+----+----+----+----+----+----+-----
   π(20) 17           | 11 | 13 | 17 | 19 |  - |  - |  - |  - |  - | 8th  4 x Twin
  --------------------+----+----+----+----+----+----+----+----+----+-----
   π(30) 13 → 12      | 23 | 29 |  - |  - |  - |  - |  - |  - |  - |10th
  ====================+====+====+====+====+====+====+====+====+====+===== 1st Twin
   π(50) 11           | 31 | 37 | 41 |  - |  - |  - |  - |  - |  - |13th
  --------------------+----+----+----+----+----+----+----+----+----+----- 2nd Twin
   π(60)  7 → 19      | 43 | 47 | 53 | 59 |  - |  - |  - |  - |  - |17th
  --------------------+----+----+----+----+----+----+----+----+----+----- 3rd Twin
   π(80)  5 → 18      | 61 | 67 | 71 |  - |  - |  - |  - |  - |  - |20th
  ====================+====+====+====+====+====+====+====+====+====+===== 4th Twin
   π(100) 0 → 43      | 73 | 79 | 83 | 89 | 97 | 101| 103| 107| 109|29th 
  ====================+====+====+====+====+====+====+====+====+====+=====
           Δ                                                         Δ
  12+13+(18+18)+13+12  ← 36th-Δ1=151-1=150=100+2x(13+12)  ←  30th = 113 = 114-1
```
  
By the next loop of (1000x1000) the above term leads to 329+289 = 618 = 1000/Φ = 1000x1000/1618. Now let's count on how many grammar's will involve.

```
Root Generation:
 root[1000] = π(1000) + loop(10 x 1000)  +  loop(100 x 1000) 
 loop(10000) => π(10000) - (10th)th - 10th = 1229 - 109 - 29 = 1091
 loop(100000) => π(100000) - ((10th)th)th - (10th)th = 9592 - 599 - 109 = 8884

 root[1000] = 168 + 1091 + 8884 = 10143
```

This 10143 will comprise of lexer and parser similar with 168 & 618. Since the 168 algorithm is set 102 by 66 then its ratio is 102/168=60% by 66/168=40% or approx 10143x60%=6200 of lexers by 10143x40%=3900 of parsers.

[<img src=https://user-images.githubusercontent.com/36441664/71659208-5515b480-2d79-11ea-859f-a20dea0cf680.jpg>](https://github.com/eq19/maps)

The development of this 6200 by 3900 took its base place in this repository and is considered final. It is the most complex thing among the other steps where we have to involve so many items to verify about how far this development is adoptable. 

[<img width=100% src=https://user-images.githubusercontent.com/8466209/90597914-32f37880-e21c-11ea-81b3-ffdcd47037b8.png>](https://github.com/chetabahana/chetabahana.github.io/wiki#kelas)

Therefore it will take several unsolved cases of modern science including but not at least _[DNA Replication Fork](https://en.wikipedia.org/wiki/DNA_replication#Replication_fork)_, _[Alzheimer's Disease](https://youtube.com/playlist?list=PL_S8nmGoQ7q6wKXUG8HBqPzoAhRmVCmSJ)_, and _[The Millenium Prize Problems](https://github.com/chetabahana/tensorflow/wiki/Untouched-Intelligences#scheme)_. They will form as basic grammars such as how to rectify _[C1+C2](https://github.com/MarketLeader)_ using _[P=NP](https://github.com/chetabahana/track/wiki)_.

[<img src=https://user-images.githubusercontent.com/36441664/84623744-1b410080-af0a-11ea-978b-e1fd1961985d.jpg>](https://github.com/chetabahana/track/wiki)

The final result of this Q(19,10) would form π(10)=(2,3,5,7) as the [1st row of 19](https://github.com/eq19/eq19.github.io#1st-step-q10-30). Please find below the progress we have got so far.

# Running Code

You may check the running code starting with [Sequence Diagram](https://chetabahana.github.io/#chetabahana-skema?pad=2) shown below which is developed as [the initial step](https://github.com/eq19/eq19.github.io#tabulate-prime-by-the-power-of-168) on building the _[10143 Grammars](https://github.com/eq19/eq19.github.io#7th-step-q19-10)_.

[![Sequence Diagram](https://user-images.githubusercontent.com/36441664/107134254-ee22e180-6922-11eb-9465-3dd64ebf7dca.png)](https://chetabahana.github.io/#chetabahana-skema?pad=2)

Clicking on each of objects will turn to 6 (six) diagrams in the cycle form of [prime hexagon](https://github.com/chetabahana/hexagon) which is then return to the beginning. So in order to get code able to run online then the 168 is provided in [json](https://chetabahana.github.io/feed.json) while 618 in [xml](https://chetabahana.github.io/feeds.xml).

<img width=100% src=https://user-images.githubusercontent.com/36441664/69475449-ce77ca00-0dff-11ea-964e-cc959db0740a.png>

This is formed as a partial of _168 (mapping) and 618 (feeding)_ that stand as  [the whole scheme](https://github.com/chetabahana/chetabahana.github.io/wiki/Skema#Implementasi) of The M+F to C1+C2. Although the code is already running but however it is not yet user friendly as it could run only in _[GitHub API Platform](https://docs.github.com/en/developers)_.

<img width=100% src=https://user-images.githubusercontent.com/36441664/86481184-b72b9280-bd79-11ea-899b-51db929fc3d2.png>

## Our Lisence

> The <a href="https://www.google.com/search?q=definite">definite</a> key to <a href="https://www.google.com/search?q=identify">identify</a> whether you use our concept is when there a kind of <a href="https://www.google.com/search?q=development">development</a> item <a href="https://www.google.com/search?q=lies">lies</a> a [unified assignment](https://github.com/eq19/maps/Mapping#All_The_Seven_7) in [hexagonal form]([Mapping-Routine#the-six-6) by '''''six (6)''' [corresponding sets](Mapping-Spreading)'' while [each sets]([Mapping-Employment) pick [a combination](Mapping-Merging) of '''''six (6)''' [routes](Mapping-Settlement)'' with [a pairing](Mapping-Comparison) of '''''six (6)''' to '''six (6)''' of [all channels](Mapping-Overall)''.


_The Pre-release 168_ is being developed for _[eCommerce](https://github.com/chetabahana/chetabahana.github.io/discussions/70)_ within 7 (seven) years. Based on the _[19 Cells](https://github.com/eq19/eq19.github.io#6th-step-q29-19)_ of 168 vs 618 tabulation then for the 618 it might need another 12 (twelve) years to develope those _10143_ to become 1st Release.

So Be Patient and Stay Tuned!

© [The Quantum Project](https://github.com/eq19)  
[![profile for eQ19 on Stack Exchange, a network of free, community-driven Q&amp;A sites](https://stackexchange.com/users/flair/5054985.png)](https://stackoverflow.com/users/4058484/eq19?tab=profile)   
