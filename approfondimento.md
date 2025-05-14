# 📝 Approfondimento Tecnico

## 🏗️ Architettura del Sistema

Il sistema è composto da due unità principali interconnesse:

### 🛟 Boa di Superficie
- Equipaggiata con Raspberry Pi 5
- Possibilità di integrare un sistema GPS per la navigazione
- Interfaccia di controllo principale
- Gestione waypoints e percorsi
- Alimentazione principale
- Comunicazione con la base attraverso WiFi

### 🤿 Unità Sottomarina
- Controllata da Arduino R4 WiFi
- Sensori ambientali
- Camera subacquea
- Sistema di propulsione
- Controllo di profondità

## 🔌 Sistema di Connessione

Due cavi principali collegano la boa all'unità sottomarina:
1. **Cavo Ethernet**: 
   - Comunicazione ad alta velocità
   - Trasmissione dati dei sensori
   - Comandi di controllo
   
2. **Cavo USB**:
   - Streaming video dalla camera
   - Alimentazione backup

## 🎯 Sistema di Navigazione

1. **Programmazione Percorso**:
   - Impostazione waypoints GPS sulla boa
   - Definizione profondità per ogni punto
   - Pianificazione missione

2. **Esecuzione Automatica**:
   - La boa naviga tra i waypoints
   - L'unità sottomarina segue mantenendo la profondità
   - Raccolta dati continua durante il percorso
   - Ritorno automatico al punto di partenza

## 🎛️ Divisione Compiti

### Raspberry Pi (Boa):
- Gestione GPS e navigazione
- Elaborazione dati
- Interfaccia utente
- Comunicazione con la base
- Storage primario

### Arduino (Sottomarino):
- Controllo motori
- Lettura sensori
- Gestione camera
- Controllo stabilità
- Sistema di sicurezza
