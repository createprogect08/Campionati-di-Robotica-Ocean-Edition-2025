# 🛠️ Campionati di Robotica - Ocean Edition 2025

## 🤖 Progetto: Drone Subacqueo per Analisi e Reperimento Dati Marini

---

### 📌 Descrizione
Il progetto prevede la realizzazione di un drone subacqueo collegato a una Boa in grado di effettuare analisi ambientali marine, raccogliendo vari dati e mostrandoli in una piattaforma.

---

### 🎯 Obiettivi
- Rilevare temperatura, salinità, qualità dell’acqua e pressione  
- Analizzare il territorio marino con una telecamera  
- Inviare i dati in superficie
- Visualizzare i dati

---

### ⚙️ Caratteristiche Tecniche
- **Computer:** Raspberry Pi 5  
- **Microcontrollore:** Arduino R4 WiFi  
- **Propulsione:** 5 motori (scegliere se usare DC o B)  
- **Energia:** Batteria Li-Ion 6S3P  
- **Sensori:**  
  - Sensore temperatura  
  - Sensore TDS (Keyestudio)  
  - Sensore pressione (0-0.5 Mpa)  
  - Sensore giroscopio  
  - Sensore accelerometro  
  - Sensore salinità  
- **Comunicazione:**  
  - Trasmissione via cavo Ethernet e usb
  - Logging dati su SD  
  - Possibile trasmissione tramite Wifi e GPS
- **Visione:** Camera subacquea + Deep Learning per riconoscimento fauna

---

### 🖼️ Schema del Sistema
![Schema Funzionale](img/schema-drone-sub.png)

---

### 🛠️ Stato Attuale
- [] Progetto CAD del telaio completato  
- [x] Scelta dei componenti principali  
- [ ] Assemblaggio meccanico  
- [ ] Programmazione firmware e raccolta dati  
- [ ] Test in acqua e calibrazione

---

### 👥 Team
- Giorgio Perini  
- Luca Cominelli  
- Mirco Lorizzo

---

### 📅 Timeline

| Fase                                   | Data Inizio     | Data Fine        | Stato |
|----------------------------------------|------------------|------------------|--------|
| Registrazione e citizen science        | 01/03/2025       | 18/04/2025       | ✅ |
| Progettazione e sviluppo del prototipo | 01/04/2025       | 10/05/2025       | 🟡 |
| Upload documentazione e video          | 01/05/2025       | 10/05/2025       | 🔜 |
| Consegna dati citizen science          | —                | 18/05/2025       | 🔜 |
| Selezione finalisti                    | —                | 20/05/2025       | 🔜 |
| Evento finale - Ocean Day              | 06/06/2025       | 06/06/2025       | 🔜 |

---

### 📂 File utili
- [modello 3D sottomarino](progetto/modello_3D/scocca_sottomarino/modello.md)  
- [Cablaggio Batteria](progetto/elettronica/elettronica_sottomarino/batterie/documentazione_batteria.md)  
- [Cablaggio elettrico totale sottomarino](progetto/elettronica/elettronica_sottomarino/schema_sottomarino.jpg)

- [modello 3D boa](progetto/modello_3D/modello.md)  
- [Cablaggio elettrico totale boa](progetto/elettronica/elettronica_boa/collegamento_boa.png)

- [Materiale utilizzato](prezzi.pdf)

- [Approfondimento](approfondimento.md)

---

> 🧠 *“Esplorare gli abissi per capire la superficie.”*
