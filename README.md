# Frequent-Patterns-Outlier-Analysis
# 🧠 Data Mining & Outlier Detection Projects

This repository contains a set of projects from my MSc in Big Data Science coursework. The notebook showcases data mining techniques such as frequent pattern mining using the Apriori algorithm, Z-score based outlier detection, anomaly detection with One-Class SVM, text mining, and time series forecasting.

---

## 🔍 Key Projects

### 1. 🔗 Association Rule Mining with Apriori
- Implemented frequent itemset generation with support pruning.
- Used Apriori property to reduce candidate search space.
- Compared rule support: `{boarding pass, passport} ⇒ flight` vs `{boarding pass} ⇒ flight`.

### 2. 🚨 Outlier Detection
- **Z-score Method**: Identified rainfall anomalies in Tower Hamlets dataset.
- **One-Class SVM**: Detected anomalies in stock percentage change data.
- 3D scatter plot and histogram used to visualise outliers.
- ~17.8% data classified as outliers.

### 3. 🧹 Web Scraping & Cleaning
- Scraped income and shopping data using BeautifulSoup.
- Converted HTML tables to pandas DataFrames.
- Cleaned missing or malformed entries.

### 4. 📈 Time Series Forecasting
- Used daily births dataset from 1959–60.
- Applied 7-day trailing moving average smoothing.
- Forecasted first 5 days of 1960 using:
  - AR (AutoRegressive) model with `p=2`
  - ARMA model with `p=2, q=2`

### 5. 📝 Text Mining & Document-Term Matrix
- Tokenised and cleaned documents.
- Created document-term matrix (DTM).
- Calculated inverse document frequency (IDF) values for all words.

---

## 🛠 Technologies Used
- Python (Jupyter Notebooks)
- Scikit-learn
- Pandas / NumPy / Matplotlib / Seaborn
- Statsmodels (for AR/ARMA)
- BeautifulSoup
- HTML Scraping
- Association Rule Mining

---

## 📁 Folder Structure
├── Frequent-Patterns-Outlier-Analysis
├── notebooks/
│ └── datamining_assignment2.ipynb
├── data/
│ └── stocks.csv, births.csv
├── Report.pdf
