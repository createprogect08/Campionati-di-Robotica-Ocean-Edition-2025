# 🛠️ Campionati di Robotica - Ocean Edition 2025

## 🤖 Progetto: Drone Subacqueo per Analisi e Reperimento Dati Marini

---

### 📌 Descrizione
Il progetto prevede la realizzazione di un drone subacqueo autonomo in grado di effettuare analisi ambientali marine, raccogliere dati biologici e geologici e mappare il fondale in tempo reale.

---

### 🎯 Obiettivi
- Rilevare temperatura, salinità e PH dell’acqua
- Analizzare la biodiversità marina con telecamere e sensori ottici
- Creare mappe 3D del fondale utilizzando sonar
- Inviare i dati in superficie in tempo reale

---

### ⚙️ Caratteristiche Tecniche
- **Microcontrollore:** ESP32 waterproof o Raspberry Pi Zero 2 W in box stagno
- **Propulsione:** 4 motori brushless in configurazione X
- **Energia:** Batteria Li-Ion 3S ad alta capacità
- **Sensori:**
  - Temperatura e PH (DF Robot o Atlas Scientific)
  - Sonar o LIDAR subacqueo
  - IMU e bussola digitale
- **Comunicazione:**
  - Trasmissione a 433 MHz / 2.4 GHz (in superficie)
  - Logging dati su SD
- **Visione:** Camera subacquea + Deep Learning per riconoscimento fauna

---

### 🖼️ Schema del Sistema
![Schema Funzionale](img/schema-drone-sub.png)

---

### 🛠️ Stato Attuale
- [x] Progetto CAD del telaio completato
- [x] Scelta dei componenti principali
- [ ] Assemblaggio meccanico
- [ ] Programmazione firmware e raccolta dati
- [ ] Test in acqua e calibrazione

---

### 📈 Output previsti
- Tabelle e grafici dei parametri raccolti
- Immagini e video del fondale
- Mappa 3D dell’area esplorata

---

### 👥 Team
- Giorgio Perini – Progettazione, elettronica e firmware
- [Altri membri se ci sono...]

---

### 📅 Timeline
| Fase | Data Inizio | Data Fine | Stato |
|------|-------------|-----------|--------|
| Progettazione meccanica | 01/03/2025 | 15/03/2025 | ✅ |
| Sviluppo elettronica | 16/03/2025 | 31/03/2025 | ✅ |
| Assemblaggio & test | 01/04/2025 | 20/04/2025 | 🟡 |
| Concorso finale | 30/04/2025 | 30/04/2025 | 🔜 |

---

### 📂 File utili
- [Documentazione completa](doc/ocean2025_project.pdf)
- [Codice sorgente](src/main.cpp)
- [Datasheet sensori](datasheet/)

---

> 🧠 *“Esplorare gli abissi per capire la superficie.”*

