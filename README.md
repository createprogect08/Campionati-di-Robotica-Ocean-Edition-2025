# 🛠️ Campionati di Robotica - Ocean Edition 2025

## 🤖 Progetto: Drone Subacqueo per Analisi e Reperimento Dati Marini

---

### 📌 Descrizione
Il progetto prevede la realizzazione di un drone subacqueo in grado di effettuare analisi ambientali marine, raccogliendo vari dati e mostrandoli in una piattaforma pubblica.

---

### 🎯 Obiettivi
- Rilevare temperatura, salinità, qualità dell’acqua e pressione  
- Analizzare il territorio marino con una telecamera  
- Inviare i dati in superficie in tempo reale  
- Visualizzare i dati in un sito web pubblico

---

### ⚙️ Caratteristiche Tecniche
- **Computer:** Raspberry Pi 5  
- **Microcontrollore:** Arduino R4 WiFi  
- **Propulsione:** 5 motori (scegliere se usare DC o B)  
- **Energia:** Batteria Li-Ion 3S-10P  
- **Sensori:**  
  - Sensore temperatura  
  - Sensore TDS (Keyestudio)  
  - Sensore pressione (0-0.5 Mpa)  
  - Sensore giroscopio  
  - Sensore accelerometro  
  - Sensore salinità  
- **Comunicazione:**  
  - Trasmissione via cavo Ethernet  
  - Logging dati su SD  
  - Possibile trasmissione tramite LoRa  
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
- [Documentazione completa](doc/ocean2025_project.pdf)  
- [batteria](progetto/elettronica/batterie/documentazione_batteria.md)  
- [sensori](datasheet/)

---

> 🧠 *“Esplorare gli abissi per capire la superficie.”*
