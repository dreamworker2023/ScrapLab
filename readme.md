# 🌐 Scraping Data Sandbox - A.A. 2025/2026

Benvenuti nel repository ufficiale per le esercitazioni di **Web Scraping e Data Analysis del laboratorio HES ELIS**. 
Questo sito è stato progettato specificamente per permettere agli studenti di testare i propri script di automazione (Selenium) e analisi dati (Pandas, Numpy, Matplotlib) in un ambiente controllato, privo di blocchi anti-bot e CAPTCHA.

---

## 🎯 Obiettivi dell'Esercitazione

Il progetto mira a simulare un flusso di lavoro reale da **Data Analyst**:
1. **Estrazione**: Navigazione e cattura dati tramite Selenium WebDriver.
2. **Data Cleaning**: Pulizia delle stringhe, gestione dei valori mancanti (NaN) e conversione dei tipi con Pandas.
3. **Analisi**: Elaborazione statistica e calcoli con Numpy.
4. **Visualizzazione**: Creazione di grafici esplicativi con Matplotlib.

---

## 📊 Dataset Disponibili

Il sito è diviso in diverse sezioni tematiche, ognuna con tabelle ricche di dati (minimo 8 colonne):

| Pagina | Argomento | Focus Didattico |
| :--- | :--- | :--- |
| `hardware.html` | **Hardware PC** | Prezzi in $, Wattaggi e Benchmark. Ottimo per raggruppamenti per Brand. |
| `stati.html` | **Macroeconomia** | PIL, Popolazione e Aspettativa di vita. Ideale per grafici a dispersione (Scatter Plot). |
| `calcio.html` | **Sport & Finance** | Statistiche di club europei e valori di mercato. Perfetto per ordinamenti e filtri. |
| `libri.html` | **Editoria & Shop** | Titoli, Autori e Rating. Sfida: convertire recensioni testuali (es. "4 stelle") in numeri. |
| `film.html` | **Cinema & Box Office** | Registi, Durate e Incassi. Sfida: parsing di durate (es. "2h 15m") e date di uscita. |

---

---

## 🛠️ Stack Tecnologico Richiesto

Per completare le esercitazioni, assicurati di avere installato l'ambiente Python con le seguenti librerie:

```bash

pip install selenium pandas numpy matplotlib openpyxl
