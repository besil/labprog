Palindroma
==========

Descrizione
-----------

Una parola si dice palindroma quando è uguale a sé stessa se letta dall'ultima
alla prima lettera.

Ad esempio, sono palindrome le parole

	otto, abba, etnagigante

mentre non lo sono le parole

	nove, alba, montebianco

Scrivete un programma che *senza fare uso di cicli*, data una parola nel flusso
di ingresso, emetta nel flusso di uscita `si` se e solo se tale parola è
palindroma.


Vincoli
-------

Il flusso di uscita deve contenere `si`, oppure essere vuoto. Nel programma non
devono essere presenti istruzioni `for` o `while`.


Esempio
-------

Eseguendo `soluzione` e avendo `otto` nel flusso di ingresso, il programma
emette `si` nel flusso di uscita, mentre eseguendo `soluzione` e avendo `pippo`
nel flusso di ingresso, il programma non emette nulla.


Suggerimenti
------------

Per decidere se una parola è palindroma basta verificare che il primo e ultimo
carattere siano uguali e sia palindroma la parola che si ottiene eliminandoli.
