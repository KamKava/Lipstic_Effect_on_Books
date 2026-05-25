# 📊 Lipstick Effect on Books & Consumer Goods: Economic Cycles vs Consumption Behaviour

## Project Overview

This project investigates whether a “lipstick effect” exists in consumer behaviour during economic cycles — specifically whether discretionary spending remains stable or shifts during periods of economic decline.

Rather than focusing only on books, the project expands the analysis to multiple categories of consumer expenditure to better capture behavioural responses to macroeconomic changes.

The study combines:
- Macroeconomic indicators (GDP)
- Retail consumption categories (Eurostat)
- Time-series analysis
- Data visualisation and dashboard development

The goal is to understand how different types of consumption respond to economic fluctuations across countries and time.

---

## 🧠 Research Question

How do different categories of consumer spending behave during economic cycles, and is there evidence of a “lipstick effect” in discretionary consumption?

Sub-questions:
- Do discretionary goods remain stable during recessions?
- Do consumers shift spending between essentials and non-essentials?
- How does consumption volatility compare to GDP changes?

---

## 📦 Datasets Used

### 1. GDP and Macroeconomic Indicators
- Source: Eurostat / Kaggle (historical GDP dataset)
- Description: Time-series GDP data used to represent economic cycles
- Indicator: Gross Domestic Product (B1GQ / CLV_PCH_PRE)

---

### 2. Consumer Retail Expenditure (Eurostat)

- Source: Eurostat (European Commission)
- Licence: European Union Open Data Licence (EU ODL)
- Dataset: Structural Business Statistics / Retail Trade

Selected categories:

#### 🟡 G472 – Essential consumption
Retail sale of food, beverages and tobacco

#### 🟠 G47_NF_HLTH – Personal care & pharmacy goods
Retail sale of pharmaceuticals, cosmetics, and personal care products

#### 🟢 G476 – Discretionary cultural goods
Retail sale of cultural and recreational goods (e.g. books, games, entertainment goods)

---

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebooks
- SQL Server (data storage & querying)
- Power BI (interactive dashboarding)
- Git & GitHub (version control)

---

## 🧹 Data Cleaning & Preparation

Key preprocessing steps:

- Standardisation of country codes and time formats
- Handling missing and inconsistent values
- Converting SDMX / Eurostat formats into analysis-ready tables
- Aligning multi-country time series datasets
- Removing duplicates and ensuring consistent panel structure
- Normalising indices for cross-category comparison

---

## 📊 Analytical Approach

The analysis focuses on comparing consumption behaviour across three categories:

- Essential spending (G472)
- Semi-discretionary personal care (G47_NF_HLTH)
- Discretionary cultural goods (G476)

These are analysed alongside GDP to evaluate:

- Sensitivity of consumption to economic cycles
- Relative stability of discretionary vs essential spending
- Evidence of substitution effects during downturns

Methods used:
- Time-series analysis
- Correlation analysis
- Cross-category comparison
- Country-level comparison

---

## 📈 Dashboard (Power BI)

The Power BI dashboard includes:

- GDP trends over time
- Consumption trends by category
- Comparative analysis of essential vs discretionary spending
- Country-level filters and time-series exploration
- Economic cycle visualisation (recession periods vs recovery)

---

## 📌 Key Insights (to be completed after analysis)

- Behavioural differences between essential and discretionary consumption
- Evidence of consumption smoothing or trade-down effects
- Country-level variation in economic resilience
- Sensitivity of cultural goods to economic downturns

---

## 📁 Project Structure

Lipstick_Effect_on_Consumption/
│
├── data/
│ ├── raw/
│ ├── processed/
│
├── notebooks/
│ ├── 01_gdp_cleaning.ipynb
│ ├── 02_sales_cleaning.ipynb
│ ├── 03_EDA.ipynb
│ ├── 04_exploratory_analysis.ipynb
│ ├── 05_visualisation.ipynb
│
├── sql/
│ ├── schema.sql
│ ├── queries.sql
│
├── powerbi/
│ ├── dashboard.pbix
│
├── README.md


---

## 📜 Data Sources & Licensing

This project uses publicly available datasets:

- Eurostat datasets are used under the **European Union Open Data Licence (EU ODL)**
- Kaggle datasets are used under their respective dataset licenses
- No raw proprietary data is redistributed in this repository

---

## 🚀 Future Improvements

- Incorporate inflation-adjusted real consumption indices
- Apply regression analysis to quantify elasticity of demand
- Introduce lag analysis between GDP and consumption responses
- Expand dataset to include non-EU countries for comparison
- Deploy Power BI dashboard online (Power BI Service)

---

## 👤 Author

Kamile Kavaliauskaite  
Data Analytics Portfolio Project