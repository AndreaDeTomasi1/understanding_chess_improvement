# ♟️ Understanding Chess Improvement

Questo progetto si concentra sull’analisi del miglioramento negli scacchi attraverso un processo di **data ingestion**, **pulizia**, **aggregazione** e **preparazione di dataset** da utilizzare in **grafici** e **dashboard Power BI**.

---

## 🔄 Pipeline del Progetto

### 1. Data Ingestion
- Raccolta dei dati da fonti eterogenee: chiamate API verso la piattaforma Lichess e scraping del sito ufficiale FIDE.
- Salvataggio dei file grezzi in una struttura organizzata: è stato scelto il formato JSONL affinchè fosse possibile lavorare con file di grandi dimensioni senza sovraccaricare la memoria della macchina.

### 2. Pulizia e Aggregazione
- Normalizzazione dei dati.
- Rimozione di valori inconsistenti o mancanti.
- Creazione di dataset coerenti e strutturati.

### 3. Creazione CSV di Supporto
- Esportazione in file `.csv` ottimizzati per:
  - Analisi esplorativa.
  - Grafici e visualizzazioni.
  - Dashboard interattive in Power BI.

---

## 📊 Output Finale
- Dataset puliti e pronti per l’analisi.
- CSV di appoggio per Power BI.
- Dashboard e grafici per comprendere l’evoluzione e i pattern di miglioramento negli scacchi.

---

## 📑 Documentazione
Tutte le fasi del progetto e le scelte metodologiche sono illustrate in una **presentazione PowerPoint** inclusa nella repository.

---

## 📂 Struttura della Repository
understanding_chess_improvement/
│
├── data_clean/ # Dataset puliti e aggregati
├── csv_support/ # CSV di appoggio per Power BI
├── dashboards_and_plots/ # File e report Power BI
├── docs/ # Presentazione PowerPoint e documentazione
└── README.md # Descrizione del progetto

---

## 🚀 Obiettivo
Fornire una pipeline chiara e replicabile per analizzare il miglioramento negli scacchi e renderlo facilmente interpretabile tramite strumenti di **data visualization**.
