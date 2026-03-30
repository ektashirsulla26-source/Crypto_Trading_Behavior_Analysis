<div align="center">

# 📊 Crypto Trading Behavior Analysis
### Fear vs. Greed — How Market Sentiment Shapes Trader Decisions

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Status](https://img.shields.io/badge/Status-Completed-22C55E?style=for-the-badge)]()

<br/>

| 📦 Dataset | 📉 Fear Phase | 📈 Greed Phase | 📑 Output |
|:---:|:---:|:---:|:---:|
| **Historical Crypto + F&G Index** | **Reduced trade sizes** | **Volume spikes** | **PDF Report + Charts** |

</div>

---

## 📌 Project Overview

This project analyzes **crypto trading behavior** under different market sentiment conditions. Using the **Fear & Greed Index** alongside real trader transaction data, we study how traders adjust their **strategies, risk tolerance, and position sizes** across sentiment regimes — Fear vs. Greed.

> 💡 Key Question: *Does market sentiment (Fear or Greed) meaningfully change how traders behave — and by how much?*

---

## ✅ Deliverables

| # | Deliverable | Description |
|:--|:-----------|:------------|
| 1 | 📓 **EDA Notebook** | Sentiment & trading activity patterns |
| 2 | 📊 **Visualizations** | Volume trends, trade size distributions, sentiment shifts |
| 3 | 🔬 **Statistical Insights** | Hypothesis testing across Fear vs. Greed phases |
| 4 | 📑 **Summary Report (PDF)** | Key findings, charts, and explanations |

---

## 📂 Project Structure
```
data-science-assignment/
│
├── ds-ekta/
│   ├── notebooks/                  # Jupyter / Colab notebooks
│   │   └── notebook_1.ipynb
│   │
│   ├── data/
│   │   ├── raw/                    # Original unmodified datasets
│   │   │   ├── historical_data.csv
│   │   │   └── fear_greed_index.csv
│   │   └── processed/              # Cleaned & intermediate data
│   │
│   ├── outputs/                    # Generated charts & results
│   │   ├── trade_volume_by_sentiment.png
│   │   └── avg_trade_size.png
│   │
│   └── report/                     # Final report
│       └── ds_report.pdf
│
├── .gitignore
└── README.md
```

---

## ⚙️ Methods & Analysis Pipeline
```
01 → Data Collection        Historical market data + Fear & Greed Index values
02 → Data Preprocessing     Missing value handling, volume & size normalization
03 → EDA                    Volume trends, trade size analysis, sentiment detection
04 → Statistical Analysis   Fear vs. Greed comparison, hypothesis testing
05 → Visualization          Charts for all key metrics and distributions
06 → Report Generation      PDF summary with insights and conclusions
```

---

## 📈 Key Insights

- 📉 **Fear phases** → traders reduce position sizes and act more conservatively
- 📈 **Greed phases** → trading volume spikes as risk appetite increases
- 🔄 **Sentiment shifts** strongly influence short-term trading activity patterns
- 📊 Statistical testing confirms behavioral differences across sentiment regimes are significant

---

## 🚀 How to Run
```bash
# 1. Clone the repository
git clone https://github.com/ektashirsulla26-source/data-science-assignment.git
cd data-science-assignment

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open the notebook
jupyter notebook ds-ekta/notebooks/notebook_1.ipynb
```

---

## 📊 Outputs Preview

| Chart | Description |
|:------|:------------|
| `trade_volume_by_sentiment.png` | Total trading volume across Fear vs. Greed phases |
| `avg_trade_size.png` | Average trade size distribution by sentiment regime |
| `ds_report.pdf` | Full written analysis with annotated visuals |

---

## 👤 Author

**Ekta Shirsulla** — Data Scientist · Crypto Markets · Behavioral Analysis

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ekta-shirsulla/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ektashirsulla26-source)

---

<div align="center">
<sub>Built with 🐍 Python · 📓 Jupyter · 📊 Pandas · 📉 Matplotlib</sub>
</div>
