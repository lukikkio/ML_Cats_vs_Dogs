# ML_Cats_vs_Dogs
DataSet preso dalla seguente competizione su kaggle:

https://www.kaggle.com/competitions/dogs-vs-cats/overview

Eseguito in una settimana come esercitazione per Openjobmetis.


Problematiche principali: 

1. Alla prima esecuzione sembra avere una percentuale intorno il 75% e l'85% 
   ma se riavviamo il kernel e rimandiamo in esecuzione supera anche il 90%

2. Al momento non gestisce immagini che non siano cani o gatti. In particolare ho provato con
   il trifoglio nel dataset e mi restituisce gatto.

3. Su Linux al momento bisogna mettere a posto i paths, in quanto il codice attuale va bene
   per Windows e Google Colabs(Raccomandato per utilizzare la GPU e velocizzare l'allenamento del modello).
    * Non ho ancora capito su Mac come si comporta 