# 🌐 Scraping Data Sandbox - A.A. 2025/2026

Benvenuti nel repository ufficiale per le esercitazioni di **Web Scraping e Data Analysis del laboratorio HES ELIS**. 
Questo sito è stato progettato specificamente per permettere agli studenti di testare i propri script di automazione (**Selenium**) e analisi dati (**Pandas, Numpy, Matplotlib**) in un ambiente controllato, privo di blocchi anti-bot e CAPTCHA.

---

## 🎯 Obiettivi dell'Esercitazione

Il progetto mira a simulare un flusso di lavoro reale da **Data Analyst**:
1. **Estrazione**: Navigazione, gestione della paginazione e cattura dati tramite Selenium WebDriver.
2. **Data Cleaning**: Pulizia delle stringhe (es. simboli valuta), gestione dei valori mancanti (NaN) e conversione dei tipi con Pandas.
3. **Analisi**: Elaborazione statistica, raggruppamenti (groupby) e calcoli con Numpy.
4. **Visualizzazione**: Creazione di grafici (istogrammi, torte, scatter plot) con Matplotlib.

---

## 📊 Dataset Disponibili

Il portale **ScrapLab** offre diverse sezioni tematiche. Ogni pagina contiene tabelle con 7 colonne di dati generati da AI, ottimizzati per diverse tecniche di analisi:

| Pagina | Argomento | Focus Didattico Suggerito |
| :--- | :--- | :--- |
| `hardware.html` | **Hardware PC** | Prezzi, Wattaggi e Benchmark. Ottimo per raggruppamenti per Brand (Nvidia/AMD/Intel). |
| `stati.html` | **Indicatori Globali** | PIL, Popolazione e Aspettativa di vita. Ideale per correlazioni e Scatter Plot. |
| `libri.html` | **Classifica Libri** | Analisi per genere letterario e anno di pubblicazione. |
| `film.html` | **Database Cinema** | Incassi ($) e Voti IMDb. Perfetto per pulizia stringhe complesse e medie ponderate. |
| `calciatori.html` | **Sport Stats** | Valori di mercato e statistiche fisiche. Utile per ordinamenti e filtri top-performers. |
| `missioni_spaziali.html` | **Space Exploration** | Date di lancio e agenzie. Ottimo per serie storiche (Time Series) con Pandas. |
| `farmaci.html` | **Farmaceutica** | Principi attivi e categorie mediche. Ideale per conteggi di frequenza. |
| `videogiochi.html` | **Gaming Industry** | Voti Metacritic e copie vendute. Analisi del successo commerciale vs critica. |

---

## 🛠️ Stack Tecnologico Richiesto

Per completare le esercitazioni, assicurati di avere installato l'ambiente Python con le seguenti librerie:

```bash
pip install selenium pandas numpy matplotlib openpyxl
```

## 🚀 Note per gli Studenti
- **Paginazione**: Molte tabelle utilizzano una paginazione dinamica (15 righe per pagina). Lo script di scraping dovrà interagire con i pulsanti della paginazione per estrarre il dataset completo.
- **Dati Dinamici**: Alcuni dati vengono filtrati lato client; assicuratevi che Selenium attenda il caricamento completo degli elementi della tabella (`WebDriverWait`).
- **Finalità**: Tutti i dati sono generati sinteticamente per scopi didattici.

---
*Laboratorio HES ELIS – Trasformare i dati in insight.*
