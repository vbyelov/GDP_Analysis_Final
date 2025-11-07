# 🌍 Global GDP Analysis (2005–2025)

### Data Analytics Final Project — Alfatraining Data Analyst Program

This repository presents a complete **Data Analytics workflow** applied to the analysis of **Global GDP data (2005–2025)**, covering data cleaning, exploratory analysis, and interactive visualization.  
It is structured into **three Jupyter Notebooks**, each representing a key analytical phase of the project.

---

## 📘 Project Overview

**Objective:**  
To analyze global GDP trends between 2005 and 2025, identify key growth patterns across countries and regions, and visualize long-term economic developments using interactive dashboards.

**Dataset:**  
- Source: [Kaggle – World GDP Dataset (2005–2025)](https://www.kaggle.com/)  
- Format: CSV (`GDP_2005_2025_final.csv`)  
- 196 countries, annual GDP (in USD), 21 years (2005–2025)  
- Cleaned version saved as `GDP_cleaned_long.csv`

**Tools & Libraries:**  
- **Python:** pandas, numpy, matplotlib, seaborn, plotly  
- **Dashboard:** Dash / Plotly Express  
- **IDE:** JupyterLab (Windows standalone)  
- **Version Control:** Git & GitHub (SSH authentication)  

---

## 🧮 Project Structure

### 🥇 Notebook 1 — *Data Preparation*
**File:** `01_Data_Preparation.ipynb`  
Tasks:
- Load and inspect raw GDP data  
- Handle missing values and outliers  
- Convert wide format → long format  
- Interpolate missing years and standardize column names  
- Save the cleaned dataset (`daten/GDP_cleaned_long.csv`)

Output:
- Clean dataset ready for EDA  
- No missing values, 196 countries × 21 years  

---

### 🥈 Notebook 2 — *Exploratory Data Analysis (EDA)*
**File:** `02_Exploratory_Data_Analysis.ipynb`  
Tasks:
- Distribution and density plots (GDP per country and year)  
- Correlation heatmaps and pairplots  
- Top/Bottom 10 countries by GDP  
- Regional aggregation (continents, income levels)  
- Descriptive statistics and growth summaries  

Output:
- Visual understanding of GDP distribution  
- Identification of growth trends and outliers  
- Exported summary data (`daten/Dataset_region.csv`, `daten/Dataset_country.csv`)  

---

### 🥉 Notebook 3 — *Visualization & Interpretation*
**File:** `03_Visualization_and_Interpretation.ipynb`  
Tasks:
- Build interactive visual dashboard using Plotly  
- Dynamic country and year selection  
- Global GDP trends, growth analysis, and comparison  
- Regression analysis (GDP ~ Year) for long-term forecasting  
- Presentation-ready layout  

Output:
- Interactive GDP Dashboard (Jupyter-based Dash app)  
- Regression summary (`daten/regression_summary.csv`)  
- Final interpretation and project conclusions  

---

## 📊 Key Findings

- Dataset covers **196 countries** and shows a steady upward GDP trend from 2005–2025.  
- Global GDP growth **accelerates after 2010**, driven primarily by **China and the United States**.  
- GDP distribution is **highly right-skewed** (logarithmic scaling essential).  
- Emerging economies exhibit strong growth but still remain below G7 levels.  
- Global economic recovery post-2020 visible in most regions.  

---

## 🧠 Conclusions

> *“Economic data becomes meaningful only when visualized in context.”*  
This analysis demonstrates how data cleaning, exploration, and visualization complement each other in uncovering global macroeconomic patterns.  

- Data cleaning ensured consistency and accuracy.  
- EDA revealed structure, correlation, and outliers.  
- Visualization transformed data into insight — enabling interpretation of long-term GDP growth and regional disparities.  

---

## 🗂️ Repository Structure

```
GDP_Analysis_Final/
│
├── 01_Data_Preparation.ipynb
├── 02_Exploratory_Data_Analysis.ipynb
├── 03_Visualization_and_Interpretation.ipynb
├── daten/
│   ├── GDP_2005_2025_final.csv
│   ├── GDP_cleaned_long.csv
│   ├── Dataset_country.csv
│   ├── Dataset_region.csv
│   └── regression_summary.csv
├── .gitignore
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone git@github.com:vbyelov/GDP_Analysis_Final.git
   cd GDP_Analysis_Final
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly dash
   ```
3. Open the notebooks in JupyterLab.
4. For the dashboard, run:
   ```bash
   jupyter lab
   ```
   and execute the dashboard cell inside Notebook 3.

---

## 👤 Author

**Volodymyr Byelov**  
Data Analyst (Alfatraining Program, Germany)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/volodymyr-byelov-76a5b2377)
🔗 [GitHub Profile](https://github.com/vbyelov)

---

## 🏁 Status
✅ Project completed and ready for final review and presentation.
