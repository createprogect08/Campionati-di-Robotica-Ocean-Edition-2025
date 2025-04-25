## Documentazione Battery Pack per Drone Sottomarino

Questo documento descrive le specifiche e la configurazione del battery pack progettato per alimentare il drone sottomarino.

**Specifiche delle Celle:**

* **Voltaggio Nominale:** 3.7V per cella
* **Capacità:** 2500mAh per cella

**Sufficienza per l'Alimentazione del Drone Sottomarino:**

La scelta di queste celle, combinate nella configurazione descritta di seguito, è stata effettuata per fornire l'energia necessaria al funzionamento del drone sottomarino per una durata adeguata. La capacità totale del pacco batteria, ottenuta collegando le celle in parallelo, garantisce un'autonomia sufficiente per le operazioni tipiche del drone. Il voltaggio totale, ottenuto collegando gruppi di celle in serie, fornisce la potenza richiesta dai motori e dall'elettronica del drone.

**Scheda di Protezione della Batteria 3S 12V 40A:**

L'utilizzo di una **Scheda di Protezione della Batteria (BMS) 3S 12V 40A con bilanciamento della carica** è cruciale per garantire la sicurezza e la longevità del pacco batteria. Le ragioni principali per l'impiego di questa BMS specifica sono:

* **Protezione da Sovraccarico:** Impedisce che le celle vengano caricate oltre il loro limite massimo di voltaggio, prevenendo potenziali danni, surriscaldamento o incendi.
* **Protezione da Scarica Eccessiva:** Interrompe la scarica quando il voltaggio delle celle scende al di sotto del limite minimo, evitando danni irreversibili alle celle e prolungandone la vita utile.
* **Protezione da Sovracorrente:** Limita la corrente erogata dal pacco batteria, proteggendo le celle e l'elettronica del drone da correnti eccessive che potrebbero causare danni.
* **Bilanciamento della Carica:** Durante il processo di carica, la BMS monitora il voltaggio di ogni gruppo di celle in serie e interviene per assicurare che tutte raggiungano lo stesso livello di carica. Questo è fondamentale per mantenere l'efficienza del pacco batteria, massimizzare la sua capacità e prevenire squilibri che potrebbero portare a un'usura prematura di alcune celle.

La sigla "3S" indica che la BMS è progettata per gestire pacchi batteria con **tre gruppi di celle collegate in serie**. La specifica "12V" si riferisce al voltaggio nominale del pacco batteria risultante dalla configurazione in serie. La capacità di corrente di "40A" indica la massima corrente continua che la BMS può gestire in sicurezza.

**Spiegazione della Disposizione delle Celle (Serie e Parallelo):**

L'immagine mostra una configurazione di celle che combina collegamenti in **serie** e in **parallelo**. Analizzando la disposizione:

1.  **Gruppi in Serie:** Si possono identificare **tre gruppi** distinti di celle collegate in serie. Ogni gruppo è composto da più celle i cui poli positivi e negativi sono collegati in sequenza (+ al -, + al -, ecc.). Questo collegamento in serie ha lo scopo di **aumentare il voltaggio totale** del gruppo. Poiché ogni cella ha un voltaggio nominale di 3.7V, ogni gruppo in serie fornirà approssimativamente $3 \times 3.7V = 11.1V$. Questo valore è coerente con la necessità di un sistema a "12V" (il valore nominale può variare leggermente a seconda dello stato di carica).

2.  **Celle in Parallelo all'interno dei Gruppi:** All'interno di ciascuno dei tre gruppi in serie, le celle sono collegate in **parallelo**. Questo significa che i poli positivi di più celle sono collegati tra loro, così come i poli negativi. Il collegamento in parallelo ha lo scopo di **aumentare la capacità totale (mAh)** del gruppo, mantenendo lo stesso voltaggio della singola cella (3.7V). Nell'immagine, sembra che ogni gruppo in serie sia composto da **due celle collegate in parallelo**. Pertanto, ogni gruppo in serie avrà una capacità di $2 \times 2500mAh = 5000mAh$ e un voltaggio di circa 11.1V.

3.  **Configurazione Totale:** Combinando i tre gruppi in serie, ciascuno con una capacità di 5000mAh e un voltaggio di circa 11.1V, si ottiene un pacco batteria con un **voltaggio nominale totale di circa $3 \times 3.7V = 11.1V$ (che viene gestito dalla BMS come un sistema "12V") e una capacità totale di 5000mAh**.

**In sintesi, la configurazione è 3S2P (3 Serie, 2 Parallelo).** Questo significa che ci sono tre gruppi di due celle in parallelo, e questi tre gruppi sono poi collegati in serie.

Questa configurazione è stata scelta per bilanciare la necessità di un voltaggio adeguato per alimentare il drone (ottenuto con il collegamento in serie) e una capacità sufficiente per garantire una buona autonomia operativa (ottenuta con il collegamento in parallelo all'interno dei gruppi in serie). La BMS 3S è essenziale per gestire correttamente questo sistema a tre gruppi in serie, proteggendo ogni gruppo e assicurando una carica e scarica bilanciata per massimizzare le prestazioni e la durata del pacco batteria.