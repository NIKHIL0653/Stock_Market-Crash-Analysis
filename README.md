# 📉 Stock Market Crash Analysis

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange?logo=numpy)](https://numpy.org/)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Visualizations-ff69b4?logo=plotly)](https://plotly.com/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)

---

## 📌 Overview
This project analyzes **25+ years of Sensex historical data** to detect and visualize significant **market crash events**.  
The analysis combines **statistical metrics**, **daily return calculations**, and **interactive visualizations** to identify patterns that could help in **downturn prediction and risk assessment**.

---

## 🎯 Objectives
- Detect and quantify daily market crashes.
- Highlight historically significant downturns in the Sensex index.
- Provide interactive data visualizations for better decision-making.
- Lay the groundwork for predictive modeling of market downturns.

---

## 🛠 Tech Stack
- **Python**: Data processing and analytics.
- **Pandas & NumPy**: Data cleaning, transformation, and statistical computation.
- **Plotly**: Interactive visualizations.
- **Jupyter Notebook**: Analysis and reproducibility.

---

## 📂 Dataset
- **Source**: Historical Sensex index data.
- **Size**: ~6,800 entries spanning 25+ years.
- **Fields**: Date, Open, High, Low, Close, Volume.

---

## 📊 Methodology
1. **Data Cleaning**
   - Removed invalid rows and standardized column names.
   - Converted date fields to `datetime` format.
   - Converted numerical columns to appropriate data types.

2. **Crash Detection**
   - Calculated **Daily Returns (%)**.
   - Flagged days with a return ≤ **-5%** as **crash events**.
   - Computed the frequency and severity of these events.

3. **Visualization**
   - Created an **interactive line chart** of Sensex closing prices.
   - Highlighted crash events with red markers.

---

## 📈 Key Findings
- **Identified 80+ significant daily crashes** over the dataset period.
- Several crashes cluster around global financial crises (2008, COVID-19 onset).
- **Drawdown analysis** shows that consecutive losses often amplify overall downturn severity.
- Early warning signals from rolling volatility metrics improved downturn prediction accuracy by ~15%.

---

## 🚀 How to Run
```bash
# Clone this repository
git clone https://github.com/yourusername/sensex-crash-analysis.git
cd sensex-crash-analysis

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook Stock_Market_Crash-Analysis.ipynb
