---
layout: post
title: "La matematica dell'orologio"
excerpt: "Persino la matematica più astratta permea la nostra vita quotidiana, senza che noi ce ne accorgiamo."
---
![Orologio]({{site.baseurl}}/assets/img/orologio.jpg)
Sicuramente tutti conosciamo bene l’orologio. Quest’oggetto fa parte della nostra vita quotidiana e impariamo ad usarlo sin da bambini,
dandone per scontato il funzionamento.
Tuttavia, se ci fermiamo un attimo a riflettere notiamo che la giornata di 24 ore è misurata grazie a uno strumento che ne riporta
sul quadrante solo 12.
Alla base di questo funzionamento soggiace una branca della matematica molto astratta, formalizzata da [Gauss](https://it.wikipedia.org/wiki/Carl_Friedrich_Gauss)
e nota come _aritmetica modulare_. Proprio perché su questo principio si basa il calcolo delle ore è anche nota come
_aritmetica dell’orologio_.
Siamo tutti d’accordo sul fatto che _1+1=2_, mentre se alla luce di questo affermassi che _1+1=0_ può essere un’uguaglianza vera
verrei probabilmente preso per folle in quanto starei dicendo che _2=0_. C’è un caso in cui _2=0_, e più in generale ci sono dei casi
in cui numeri diversi in qualche modo si equivalgono: è il principio alla base dell’aritmetica modulare.
Cerchiamo di capirci qualcosa in più.

Lavoriamo su dei particolari insiemi di numeri chiamati _campi_ (di cui omettiamo la definizione). Su questi campi definiamo una quantità
che si chiama _caratteristica_: essenzialmente si tratta del numero di volte che devo sommare 1 a sé stesso per ottenere 0. È abbastanza
ovvio che nei numeri reali ad esempio, che quasi tutti conosciamo, non otterrò mai 0 sommando 1 a sé stesso,
quindi diremo che il campo ha caratteristica 0 (cioè l’unico modo per ottenere 0 con una somma di 1 è non scrivere nessun 1).

Supponiamo ora di prendere un campo costituito solo da 0 e da 1.
Immaginiamo di disporre questi numeri su una circonferenza e di percorrerla in senso orario. Se aggiungiamo un numero a 0,
in senso orario, otteniamo 1 (quindi _0+1=1_) mentre se aggiungiamo un numero a 1, sempre in senso orario,
torniamo di nuovo sullo 0 (quindi _1+1=0_). Quindi sommando 1 a sé stesso due volte otteniamo 0, cioè la caratteristica di questo campo
è uguale a 2. Tuttavia _1+1_ è notoriamente uguale a _2_: abbiamo quindi trovato un esempio di campo in cui _2=0_.
![Campo a caratteristica 2]({{site.baseurl}}/assets/img/char2.jpg)
Facciamo un altro esempio:
![Campo a caratteristica 4]({{site.baseurl}}/assets/img/char4.jpg)
In questo caso _1+1+1+1=0_, quindi il campo ha caratteristica 4. Quindi 4=0.
Ma allora _4+1=0+1=1_. Tuttavia _4+1_ è notoriamente uguale a _5_ quindi dovrà essere _5=1, 6=2_ e così via.
Dovrebbe già essere più chiaro il _funzionamento_ di questi particolari insiemi di numeri.

Torniamo quindi all’orologio. Supponiamo di avere un campo di caratteristica 12.
Disponendo come prima i suoi elementi su una circonferenza otteniamo questa rappresentazione:
![Campo a caratteristica 12]({{site.baseurl}}/assets/img/char12.jpg)
A questo punto abbiamo che se sommiamo 1 a sé stesso 12 volte otteniamo 0. Quindi _12=0_.
In analogia con il caso precedente si otterrà quindi che _13=1, 14=2, 15=3_ e così via.
Questo campo è molto simile ad un orologio: infatti le 13:00 rappresentano l’1:00 di pomeriggio, le 14:00 sono le 02:00 di pomeriggio
e così via. Inoltre, siccome _12=0_, non sarà affatto un problema se al posto dello 0 scrivo 12. Con quest’ultima normalizzazione ottengo proprio l’orologio che siamo abituati a vedere tutti i giorni: si tratta di un campo a caratteristica 12.
Ecco come persino la matematica più astratta permea le nostre vite quotidiana senza che ce ne accorgiamo.
![Orologio]({{site.baseurl}}/assets/img/campo.jpg)

# Una piccola curiosità storica
La misura del tempo si basa quindi su questo sistema di congruenze numeriche che abbiamo appena introdotto.
Il sistema orario attualmente in uso è noto come ora Napoleonica.
Prima dell’arrivo di Napoleone in Italia il sistema orario adottato era diverso da quello attuale.
Si usava infatti l’ora italica. L’orologio anziché riportare 12 ore ne riportava solamente 6 (di conseguenza anziché due giri
ne compiva quattro in un giorno). Le 24 ore non corrispondevano alle nostre attuali 24 ore in quanto questo sistema
era molto legato alla vita agro-silvo-pastorale.
In ogni caso, anche questo vecchio sistema (che misurava 24 ore con 6 numeri anziché con 12)
si basa sullo stesso sistema di congruenze numeriche. Il campo anziché essere a caratteristica 12 è a caratteristica 6.
Tali orologi sono ancora visibili. In foto l'orologio a 6 ore del Quirinale e l'orologio a 6 ore della Parrocchia S.M. Assunta di Filettino.
![Orologio del Quirinale]({{site.baseurl}}/assets/img/quirinale.jpg)
![Orologio di Filettino]({{site.baseurl}}/assets/img/filettino.jpg)
