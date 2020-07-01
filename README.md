# Browser version of SpurguX

This is an browser version of the classic Finnish roguelike game
[SpurguX](https://fi.wikipedia.org/wiki/SpurguX), implemented with help of
[JavaScript version of DOSBox](https://js-dos.com/).

## Running locally

This is how you can install and run the game locally.

```bash
$ npm install
$ npm start
```

Then point your browser to http://localhost:5000

## Instructions

(Unfortunately in Finnish. Translations welcome.)

```

                             SpurguX Vs 1.17
                              (C) 1987 P.N.


     SpurguX on tositapahtumiin perustuva seikkailupeli, jossa antisankari
  kahlaa kaupunginosien halki etsien konjakkipulloa, jonka huhutaan olevan
  tasolla 50, seuranaan ainoastaan kova jano. Kaduilla hän törmää mitä
  erilaisimpiin olentoihin, joilla kaikilla on omat tapansa, sekä saattaa
  löytää erilaisia kapistuksia, joista on hyötyä tai sitten ei. Pelaajan
  on kerättävä kaikki tason pisteet (.) ennen seuraavalle tasolle pääsyä.
  Mikäli pelaajalla on aggressivisia taipumuksia, hän voi hakata edellä-
  mainittuja olentoja - tai vaikka seinää - liikkumalla niitä päin, eri
  asia on, mitä siitä seuraa ...

     Pienenä vinkkinä alkoholiin tottumattomille sanottakoon, ettei sitä
  kannata juoda aivan holtittomasti, muttei peli oikein luista aivan selvin
  päinkään.

     Kaikki kommentit - esim. huomatut bugit tai parannus/lisäysehdotukset -
  pelistä otetaan ilolla vastaan, käyttäjätunnukseni Clinetissä on pate.


                                                             <lissää>

                                 OBJEKTIT:

  & = Lonkka          @ = Pelaaja         C = Lainvartija
  % = Kalja           # = Sähköaita       M = Vanhahko nainen
  Þ = Konjakki        █ = Seinä           N = Neekeri
  ( = Makkara         ± = Hauta           T = Teekkari
  ! = Pamppu          õ = Haalarit        P = Punkkari (Ñ = Punkkarien kingi)
  \ = Stiletti        ¸ = Vesialue        K = Kake
  ß = Ketjut          æ = Kökköä          V = Taskuvaras
  $ = Rahaa (mk)      E = Vankikarkuri    D = Koira
   = Maito             = Aave            B = Pisteennielijä
  o = Omena           Û = Portsari        H = Hintti
  ý = Suklaata        G = Gorilla         O = Skinhead
  Ø = Silakka         Q = Trokari         S = Käärme
  Ú = Camel-Boots     I = Hippi           > = Portti seuraavalle tasolle
  ¿ = Vihje           A = Aidsinkantaja   ^ = Metroasema
  . = Piste           J = Juppi





                                                             <lissää>

                                   OHJAUS

     Ohjaus noudattaa huomattavasti erään Hack-nimisen pelin ohjausta,
  mutta muita yhtäläisyyksiä ei sitten olekaan, sillä SpurguX perustuu
  tosielämään, kun taas Hack on pelkkää fiktiota.


  H,h = vasemmalle     Y,y = luode         q = juo            e = syö
  J,j = alas           U,u = koillinen     i = inventaario    v = version
  K,k = ylös           N,n = kaakko        > = tasonvaihto    ? = help
  L,l = oikealle       B,b = lounas        . = odota          Q = itsemurha
                       t = heitä           / = sepustus

  Nyt ovat myös nuolinäppäimet käytössä liikuttaessa yksitellen, ja lisäksi
  Del = . ja Ins = i.

  Huom! Kun heität jotain, anna inventaariossa oleva järjestysnumero taikka
  kalja = a, lonkka = b, makkara = c, 0 = ei heittoa.
```
