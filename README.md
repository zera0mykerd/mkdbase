# 🗄️ EU-Kinesis CRM & PC Optimizer 🗃️

[![Author](https://img.shields.io/badge/Author-zera--mykerd-green.svg)](mailto:zera0mykerd@gmail.com)
[![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg)]()
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)]()

> **EU-Kinesis** non è solo un database gestionale; è un'interfaccia olistica progettata per la gestione documentale di corsisti e l'ottimizzazione radicale del sistema operativo tramite script integrati.

---

## 🌟 Visione Generale
Il software nasce come una soluzione "all-in-one" per la gestione di record anagrafici (specificamente orientati a autoscuole o centri di formazione) integrando strumenti avanzati di import/export JSON e un potente modulo di manutenzione PC nascosto sotto forma di script batch.

---

## 🛠️ Caratteristiche Principali

### 1. Gestione Database (CRM)
Il cuore pulsante dell'applicazione permette di gestire ogni singolo dettaglio di un cliente/corsista:
* **Anagrafica Completa:** ID, Nome, Cognome, Sesso.
* **Dati Temporali e Geografici:** Data di nascita, Luogo di nascita, Residenza.
* **Comunicazione:** Numero di telefono, Email.
* **Dettagli Tecnici:** Tipo di patente, Stato del corso, Risultati degli esami.
* **Contabilità:** Stato del pagamento, Data di inizio, Importo residuo ("Da versare").

### 2. Strumenti di Manutenzione Dati
* **Persistenza JSON:** Funzionalità completa di caricamento e download del database in formato `.json` per la portabilità dei dati.
* **Sistema di Logging Avanzato:**
    * `Scarica Logs`: Esporta l'attività in file `.log`.
    * `Visualizza Log`: Monitora le azioni in tempo reale.
    * `Riscrivi Logs`: Permette la sovrascrittura o pulizia della cronologia.
* **Filtro Intelligente:** Barra di ricerca avanzata con debounce (ritardo di 1250ms) per query dinamiche e veloci.

### 3. Funzionalità "Power User" (PC Optimizer)
All'interno del codice è integrato il modulo **Panda Quizer**, uno script batch (`.bat`) codificato in Base64 progettato per:
* **Elevazione Privilegi:** Gestione automatica dell'UAC per l'esecuzione come Amministratore.
* **Ottimizzazione Sistema:** Disattivazione servizi non essenziali e modifica dei parametri di configurazione del PC per massimizzare la velocità.
* **Interfaccia ASCII Art:** Schermate di benvenuto personalizzate con grafica retrò e informativa legale.

---

## 🎨 Design e UI/UX
L'interfaccia è stata curata per essere tanto funzionale quanto visivamente gratificante:
* **Animazioni Dinamiche:** Titolo con effetti `pulse` e `explode` al click.
* **Feedback Visivo:** * Celle della tabella interattive con effetti di saturazione e traslazione al passaggio del mouse.
    * Counter dei record dinamico con effetto `brightness` al passaggio del mouse.
* **Responsive Design:** Layout adattabile per dispositivi mobili e desktop.
* **Scrollbar Personalizzata:** Estetica coordinata con il tema "Mint/Aquamarine".
* **Sicurezza:** Reindirizzamento automatico verso `HTTPS` per proteggere l'integrità dei dati.

---

## 🚀 Dettagli Tecnici
* **Linguaggi:** HTML5, CSS3, JavaScript (ES6+).
* **Meta Tags:** Ottimizzazione per bot (no-translate) e gestione rigorosa della cache (Pragma: no-cache).
* **Integrazione Batch:** Script di ottimizzazione integrato tramite `BAT_CONTENT_BASE64`.
* **Controlli di Validazione:** Gestione degli importi numerici con controllo preventivo per evitare valori negativi.

---

## 📖 Modalità d'Uso
1.  **Apertura:** Aprire il file `mkdbase.html` in qualsiasi browser moderno.
2.  **Inserimento:** Compilare il modulo "Aggiungi Record" e premere il pulsante per salvare.
3.  **Ricerca:** Utilizzare la barra superiore per filtrare istantaneamente migliaia di record.
4.  **Backup:** Scaricare periodicamente il file JSON per non perdere i dati.
5.  **Manutenzione:** Cliccare sull'icona SVG `KinesisQuiz` per accedere alle funzioni di gestione esami e log PC.

---

## 👤 Autore e Contatti
* **Developer:** zera-mykerd
* **Designer:** zera-mykerd
* **Email:** [zera0mykerd@gmail.com](mailto:zera0mykerd@gmail.com)
* **Copyright:** © zera0mykerd

---

## ⚖️ Note Legali
Il software è fornito per uso privato e personale. L'autore non si assume responsabilità per eventuali danni derivanti dall'uso degli script di ottimizzazione sistema contenuti nel modulo batch..
