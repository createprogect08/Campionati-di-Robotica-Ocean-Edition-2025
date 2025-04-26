# Documentazione Battery Pack per Drone Sottomarino (Configurazione Cilindrica per Alloggiamento Impermeabile)

Questo documento descrive le specifiche e la configurazione del battery pack progettato per alimentare il drone sottomarino, ottimizzato per un alloggiamento di forma cilindrica all'interno di un tubo in plexiglass impermeabile.

## Specifiche delle Celle

* **Modello:** 18650
* **Voltaggio Nominale:** 3.7V per cella
* **Capacità:** 2500mAh per cella

[Datasheet](datasheet/celle_litio.pdf)

## Sufficienza per l'Alimentazione del Drone Sottomarino (Motori a 12V)

La scelta di queste 20 celle, combinate nella configurazione descritta di seguito, fornisce l'energia necessaria al funzionamento dei motori a 12V del drone sottomarino all'interno di un alloggiamento cilindrico impermeabile (tipicamente un tubo in plexiglass per garantire l'isolamento dall'acqua). La capacità totale utilizzabile del pacco batteria garantisce un'autonomia adeguata per le operazioni subacquee, mentre il voltaggio nominale di circa 11.1V è compatibile con i motori a 12V (rientrando nelle tolleranze operative tipiche).

![Immagine_batterie](image.png)

## Scheda di Protezione della Batteria 3S 12V 40A

L'utilizzo di una **Scheda di Protezione della Batteria (BMS) 3S 12V 40A con bilanciamento della carica** è cruciale per garantire la sicurezza e la longevità del pacco batteria all'interno dell'ambiente sigillato. Questa BMS è specificamente progettata per gestire pacchi batteria con tre gruppi principali collegati in serie, fornendo la tensione nominale di circa 11.1V necessaria per alimentare i motori a 12V. La BMS monitora e bilancia la carica e la scarica di ciascun gruppo, proteggendo le celle da sovraccarico, scarica eccessiva e cortocircuiti, elementi critici in un sistema sigillato.

[Datasheet](datasheet/Scheda_protezione_celle.pdf)

## Disposizione delle Celle (Serie e Parallelo per Alloggiamento Cilindrico)

Le 20 celle sono disposte in sei gruppi, che vengono poi combinati per formare tre blocchi in serie, gestiti dalla BMS 3S. Questa configurazione è ottimizzata per adattarsi alla forma cilindrica dell'alloggiamento impermeabile. La disposizione è la seguente:

* **Gruppo 1:** 3 celle in parallelo
* **Gruppo 2:** 4 celle in parallelo
* **Gruppo 3:** 3 celle in parallelo
* **Gruppo 4:** 3 celle in parallelo
* **Gruppo 5:** 4 celle in parallelo
* **Gruppo 6:** 3 celle in parallelo

Questi gruppi sono collegati in serie a coppie per formare i tre blocchi gestiti dalla BMS, fornendo il voltaggio necessario per i motori a 12V:

* **Blocco 1 (Serie 1 della BMS):** Gruppo 1 (3 celle in parallelo) **in serie con** Gruppo 4 (3 celle in parallelo).
* **Blocco 2 (Serie 2 della BMS):** Gruppo 2 (4 celle in parallelo) **in serie con** Gruppo 5 (4 celle in parallelo).
* **Blocco 3 (Serie 3 della BMS):** Gruppo 3 (3 celle in parallelo) **in serie con** Gruppo 6 (3 celle in parallelo).

![Immagine_disposizione_batterie](disposizione_celle.png)

## Caratteristiche del Pacco Batteria all'interno del Tubo in Plexiglass

* **Voltaggio Nominale Totale:** Circa 11.1V (3 blocchi in serie, ognuno con un voltaggio nominale di 3.7V x 2 celle in serie), compatibile con i motori a 12V.
* **Capacità Totale Utilizzabile:** 7500mAh (limitata dal blocco con la capacità inferiore, derivato dai gruppi con 3 celle in parallelo). La capacità garantisce un'operatività prolungata per le missioni subacquee.

## Considerazioni sulla Disposizione e sull'Alloggiamento Impermeabile

La disposizione non uniforme delle celle in parallelo tra i blocchi è una conseguenza della necessità di adattarsi alla geometria interna del tubo in plexiglass, garantendo al contempo un fissaggio sicuro e la protezione delle celle dall'ambiente acquatico. L'alloggiamento in plexiglass fornisce un isolamento elettrico essenziale e protegge il pacco batteria dalla pressione dell'acqua. La BMS 3S, alloggiata anch'essa all'interno del tubo impermeabile, è vitale per la gestione sicura ed efficiente dell'energia fornita ai motori a 12V, bilanciando le tensioni e prevenendo condizioni operative pericolose all'interno del sistema sigillato.

## Modello realizzato

![Modello_realizzato](modello_realizzato/modello_finale.jpg)