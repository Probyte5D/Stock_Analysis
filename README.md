# Stock Analysis - Tesla & GameStop

Questo progetto analizza i dati storici e finanziari di Tesla (TSLA) e GameStop (GME) utilizzando Python e librerie come `yfinance`, `pandas`, `matplotlib` e `plotly`.  

I dati vengono scaricati direttamente da Yahoo Finance.

## Contenuto del progetto

- `stockanalysis.ipynb` → Notebook principale con analisi dei prezzi, medie mobili, grafici a candele e ricavi trimestrali.
- `requirements.txt` → Elenco delle librerie necessarie per eseguire il notebook.
- `.gitignore` → File per ignorare cartelle o file locali non necessari su GitHub (es. `Plots/`).

## Istruzioni

1. Clona questo repository:
```bash
git clone https://github.com/tuo-username/StockAnalysis.git
Crea un ambiente virtuale (opzionale ma consigliato):

bash
Copia
Modifica
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
Installa le dipendenze:

bash
Copia
Modifica
pip install -r requirements.txt
Apri il notebook stockanalysis.ipynb con Jupyter o Google Colab.

Librerie principali utilizzate
yfinance → per scaricare dati azionari e finanziari

pandas → per la manipolazione dei dati

matplotlib / seaborn → per grafici statici

plotly → per grafici interattivi

requests / BeautifulSoup → (opzionale, per scraping)

Note
I grafici vengono salvati nella cartella Plots/ se generati con Matplotlib.

I dati finanziari sono aggiornati automaticamente scaricando da Yahoo Finance.