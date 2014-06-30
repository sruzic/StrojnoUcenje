Projekt-Strojno
===============

LDA i sLDA

Sadržaj foldera LDA:<br>
-osnovnu implementaciju LDA modela<br>
-originalni README te implementacije<br>
-pokreni.txt sadrži naredbu za učenje modela koju smo koristili i primjer naredbe za prikaz dobivenih rezultata<br>
-makefile za kompajliranje<br>

Folder rezultati sadrži naučen model <br>
Folder ispis top 10 u folderu rezultati sadrži najčešćih 10 riječi nekih tema nakon 0,5,20 i 48 iteracija.

Nije potrebno korisiti vanjske biblioteke. Pokretanje i zadavanje parametara je opisano u README. 

Sadržaj foldera SLDA:<br>
-implementacija nadziranog LDA<br>
-originalni README<br>
-makefile za kompajliranje<br>
-pokreni.txt sadrži naredbu kojom je učen model s 10 tema i alfom koja nije fiksna<br>
-train-data.dat - podaci trening skupa<br>
-train-label.dat - labele trening skupa<br>
-test-data.dat - podaci testnog skupa<br>
-test-label.dat - labele testnog skupa<br>
-CONFUSION.m je Octave skripta za dobivanje konfuzijske tablice iz predviđanja(.dat datoteka s labelama u folderu dobivenom izvođenjem naredbe u infer.txt) i pravih labela(test-label.dat)

Od vanjskih biblioteka potrebna je biblioteka gsl(gls-devel i/ili libgs10-dev). Pokretanje učenja modela i zadavanje parametara je opisano u README. 










