# chicago-crime-and-census-sql-analysis
SQL analysis of Chicago socioeconomic indicators, public school performance data, and crime records using Python and SQLite.
# Chicago Crime, Schools & Socioeconomic SQL Analysis

> **Credential Note:** Completed as part of the **IBM Data Science Professional Certificate** on Coursera.

## 📌 Project Overview
This project performs an exploratory data analysis combining three real-world relational datasets from the City of Chicago Data Portal: Crime Incidents, Public School Performance Metrics, and Socioeconomic Indicators. 

Using SQL queries and Python data processing, the project analyzes spatial and demographic crime patterns, evaluates school safety performance, and explores correlations between socioeconomic hardship and criminal activity across Chicago community areas.

---

## 📊 Datasets Used
1. **Chicago Crime Data:** Incident-level record of reported crimes, including primary types, locations, and arrest statuses.
2. **Chicago Public Schools Data:** School performance metrics, safety scores, and attendance rates.
3. **Chicago Socioeconomic Data:** Community-level census indicators, including per capita income, hardship index, and poverty rates.

---

## 🛠️ Key Technical Features & SQL Operations
- **Relational Data Joining:** Executed multi-table `INNER JOIN` and `LEFT JOIN` operations across community areas and school IDs.
- **Aggregation & Grouping:** Utilized `GROUP BY`, `HAVING`, and aggregate functions (`COUNT`, `AVG`, `SUM`) to rank high-density crime zones and evaluate hardship scores.
- **Subqueries & Nested Logic:** Applied nested SQL queries to identify community areas with above-average hardship indices and low safety scores.
- **Data Integration in Python:** Ran embedded SQL queries using Python database connectors (DB-API / SQLAlchemy) and analyzed results using Pandas.

---

## 🔍 Key Insights & Findings
- **Socioeconomic Correlation:** Community areas with higher Hardship Index scores exhibited a higher frequency of property and violent crime incidents.
- **School Safety & Academic Performance:** Schools located in areas with lower crime density consistently reported higher overall safety scores and attendance rates.
- **Crime Distribution:** A small cluster of community areas accounted for a disproportionately large percentage of total reported narcotics and theft offenses.

---

## 🧰 Tech Stack & Tools
- **Language:** Python 3.x, SQL
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SQLite / DB-API
- **Platform & Certification:** Coursera (IBM Data Science Professional Certificate)
- **Environment:** Jupyter Notebook / IBM Skills Network Labs
- **Version Control:** Git & GitHub

---

## 🚀 How to Run the Notebook
1. Clone this repository:
   ```bash
   git clone [https://github.com/ayekhan1331-a11y/chicago-crime-and-census-sql-analysis.git](https://github.com/ayekhan1331-a11y/chicago-crime-and-census-sql-analysis.git)

## 🚀 How to Run the Notebook
1. Clone this repository:
   ```bash
   git clone [https://github.com/ayekhan1331-a11y/chicago-crime-and-census-sql-analysis.git](https://github.com/ayekhan1331-a11y/chicago-crime-and-census-sql-analysis.git)
