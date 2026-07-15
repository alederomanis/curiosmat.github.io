---
layout: post
title: "Dall'arte alla crittografia: un assaggio di geometria proiettiva"
excerpt: "Una teoria matematica nata per disegnare in prospettiva che oggi trova applicazione anche tra le moderne tecnologie."
---
Questo articolo sarà particolarmente breve poiché non ritengo utile fornire nozioni matematiche sull'argomento in quanto, data la loro astrattezza, sarebbero comprensibili
solo da _addetti ai lavori_ e non rivestirebbero quindi un carattere divulgativo.

Se parlate con un matematico questo senz'ombra di dubbio sosterrà che _"La matematica è bella"_ e che in un certo senso _"La matematica è una forma d'arte"_. Un grande matematico
italiano, Renato Caccioppoli, affermava che _"La matematica è poesia"_.
Non è neanche difficile sentire affermare che c'è un'armonia matematica ovunque (nella letteratura, nella musica, nell'arte ecc.). Tuttavia, a chi di matematica ne mastica poca,
questo legame non risulterà poi così evidente. In questo articolo introdurremo quindi un legame molto interessante tra l'arte e la matematica.

Siamo nel Rinascimento e degli artisti cercano di sviluppare una tecnica per _dipingere in prospettiva_. Il loro obiettivo è _rappresentare sul foglio lo spazio reale così come noi
lo vediamo_. Il primo a scoprire le regole della rappresentazione fu Filippo Brunelleschi.
![La città ideale]({{site.baseurl}}/assets/img/prospettiva.jpeg)

Pensate di guardare due rette parallele nella vita quotidiana, ad esempio i binari di un treno: vi sembrerà che allontanandosi questi tendano ad incontrarsi in un punto. È
proprio su quest'idea intuitiva che gli artisti del Rinascimento si basano nello studio della prospettiva. Questo punto a cui _convergono_ le linee che noi vediamo nello spazio
prenderà il nome di _punto di fuga_.
![Binari che sembrano incontrarsi in un punto]({{site.baseurl}}/assets/img/binari.jpeg)

Partendo da quest'osservazione si costruisce così una nuova geometria in cui non esiste il concetto di parallelismo: la geometria proiettiva.

![La proiezione su un piano di ciò che vediamo nella realtà]({{site.baseurl}}/assets/img/geo_proiettiva.png)
Con _prospettiva_ si intende un insieme di proiezioni di oggetti su un piano, in modo tale che quanto è disegnato corrisponda agli oggetti come noi li vediamo nello spazio.
Queste proiezioni su cui si basa il disegno prospettico esistono in geometria proiettiva e sono le _proiezioni centrate in un punto su un iperpiano proiettivo_.
In generale, in uno spazio di dimensione _n_, un iperpiano è un oggetto di dimensione _n-1_. Ecco quindi che se siamo nello spazio (che ha 3 dimensioni) un iperpiano è
un oggetto di 2 dimensioni, cioè un piano. Stiamo quindi proiettando i punti dello spazio su un piano (nel caso degli artisti il foglio) in modo che il risultato finale sia
_"uguale"_ a ciò che vediamo nella realtà.
![Proiezione di punti su un piano proiettivo]({{site.baseurl}}/assets/img/proiezione.gif)

Questa costruzione geometrica può essere anche vista come una generalizzazione della geometria a cui siamo abituati, come la _classica_ geometria euclidea: possiamo infatti
interpretare un piano proiettivo come un piano euclideo con l'aggiunta di un _"punto all'infinito"_ (notare l'analogia con il _punto di fuga_).

In sintesi, con lo scopo di dipingere in prospettiva ha avuto inizio lo sviluppo di una teoria matematica piuttosto complessa, che ancora oggi trova numerose applicazioni.
La _crittografia_, che offre degli strumenti per proteggersi dagli attacchi informatici, è proprio uno dei moderni campi di ricerca in cui la geometria proiettiva trova applicazione.

Possiamo quindi dire che l'arte del Rinascimento ha in qualche modo aperto la strada alle moderne tecnologie e che la matematica fa da ponte tra questi due mondi.

I più curiosi, coraggiosi e ferrati in matematica possono approfondire le tematiche di geometria proiettiva consultando il testo _Geometria 1_ di Edoardo Sernesi.

## Riferimenti bibliografici
- G. CRICCO, F.P. DI TEODORO, _Itinerario nell'arte vol. 2, Dal Gotico Internazione all'età barocca. Versione azzurra - Quarta edizione_, Zanichelli (2017);
- E. SERNESI, _Geometria 1. Seconda edizione riveduta e ampliata_, Bollati Boringhieri (2000).
