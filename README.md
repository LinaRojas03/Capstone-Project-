# NASDAQ-100 Institutional Investment Decision Support System

## 1. About the Project
This project addresses a critical operational friction in financial portfolio management: market analyst research for NASDAQ-100 equities is heavily fragmented, unstructured, and non-standardized across brokerage platforms. Portfolio managers traditionally face manual overhead when attempting to gauge collective market sentiment, audit analyst forecasting accuracy, or track rating momentum (*upgrades/downgrades*).

To solve this, we built a centralized, single-source-of-truth **Investment Decision Support System**. The dashboard aggregates and standardizes raw market data into an intuitive 3-page decision workflow:
* **Page 1 (Overview):** Market-wide macro context, activity volume, and Top Momentum identification.
* **Page 2 (By Company):** Asset-level deep dive, consensus depth, and implied price target upside validation.
* **Page 3 (By Analyst):** Performance auditing (*Hit Rate, Bias, Percentile Ranking*) to weight analyst recommendations based on historical accuracy.

---

## 2. My Role
As the Lead Data Analyst and Dashboard Architect on this project, my main contributions included:
* **Data Transformation & Cleaning:** Pipeline design for data type corrections, entity resolution, and missing value recovery.
* **Taxonomy Normalization:** Standardizing non-uniform broker rating scales (*Overweight, Outperform, Buy*) into a unified classification model.
* **Ethical Data Governance:** Establishing strict imputation guardrails to preserve financial data integrity.
* **Dashboard Design & Architecture:** Translating portfolio manager workflows into an interactive, 3-page decision-support interface.
* **Executive Communication:** Presenting business value, technical methodology, and governance alerts to senior stakeholders.

---

## 3. Key Skills & Tools
* **Data Transformation & Wrangling:** Python (`Pandas`, `NumPy`), SQL (Lookup tables, entity mapping) 
* **Business Intelligence & Visualization:** Power BI, DAX (Calculated measures, dynamic filtering)
* **Statistical & Financial Analysis:** Consensus Scoring, Momentum tracking, Analyst Hit Rate auditing 
* **Data Governance & QA:** Ethical imputation, taxonomy mapping, pipeline auditing

---

## 4. Project Highlights
* **Standardized Market Taxonomy:** Successfully mapped disparate brokerage terminology into a unified rating taxonomy, reducing rating missingness from 75% to 65%.
* **Entity Resolution via Lookups:** Built unique deterministic lookup tables mapping stock tickers and analyst IDs to recover ~500 missing metadata entries.
* **Analyst Credibility Framework:** Introduced historical accuracy auditing (*Hit Rate, Bias, Percentile Ranking*), enabling portfolio managers to weight consensus by analyst performance rather than treating all opinions equally.
* **Identified Critical Data Governance Gap:** Flagged an underlying 50%–70% raw data missingness rate in legacy datasets, pitching a strategic roadmap transition toward direct automated API ingestion pipelines.

---

## 5. How to Navigate the Repo
```text
├── dashboard/              # Power BI report files (.pbix) and dashboard screenshots
├── code/                   # Data cleaning, ETL, and transformation scripts (Python/SQL)
├── data/                   # Sample anonymized datasets and lookup tables
├── docs/                   # Business methodology, metric definitions, and executive speech scripts
└── README.md               # Project documentation homepage
