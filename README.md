# 🏏 Test Cricket Batting Data Analysis

This project focuses on **analyzing Test cricket batting performance using real-world data scraped from ESPN Cricinfo**. It covers end-to-end workflow including **web scraping, data cleaning, feature engineering, and exploratory data analysis (EDA)** to uncover trends and patterns among Test cricketers across countries.

---

## 📂 Project Structure
📁 Test Cricket Data Analysis

├─ 🧹 WS_project_data_extraction.ipynb → Web scraping & data cleaning

├─ 📊 WS_project_EDA.ipynb → Exploratory Data Analysis

├─ 📄 scraped_data.csv → Final cleaned dataset

└─ 📘 README.md

---

## 🎯 Objective
To understand how Test cricket players perform across different countries by **collecting and analyzing real batting statistics**, revealing performance trends, career patterns, and player insights using data-driven visualizations.  
:contentReference[oaicite:1]{index=1}

---

## 🗂 Dataset Details
- **Source:** ESPN Cricinfo  
- **Total records scraped:** 3,182 players  
- **Scraping method:** BeautifulSoup & Requests  
- **Cleaning steps:**
  - Handling missing values, duplicates & mixed-country labels (e.g., *AUS/ENG*) :contentReference[oaicite:2]{index=2}
  - Converting highest scores like `"248*"` into numeric format
  - Creating new feature columns: `Start_year`, `End_year`, `Career_Span`, `HS_Num`, etc.

---

## 🛠 Tech Stack
| Category | Tools |
|---------|-------|
| Programming | Python |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn, BeautifulSoup |
| Environment | Jupyter Notebook |

---

## 🔍 Exploratory Data Analysis (Highlights)

Key questions answered through data visualizations:

### 👥 Country-level Analysis
- Top 10 countries with most Test players  
- England produces the highest number of Test cricketers :contentReference[oaicite:3]{index=3}
- Australia leads in batting averages overall :contentReference[oaicite:4]{index=4}

### 🏅 Player Performance Insights
- Top 10 players by **total career runs**
- Top 10 players by **highest individual score**
- Top players by **batting average** (including qualified criteria) :contentReference[oaicite:5]{index=5}

### 📌 Career Patterns
- Career span box plot reveals: majority of players play **5–10 years**, while very few last **20+ years** :contentReference[oaicite:6]{index=6}
- Longest international careers visualized

### 📈 Statistical Relationships
- **Matches vs Total Runs** — positive correlation  
- **Highest Score vs Batting Average** — largely upward trend :contentReference[oaicite:7]{index=7}
- **Effect of Not Outs on Batting Average** — significant influence detected

### 🔥 Additional Findings
- 50s and 100s by country — major differences in conversion rate :contentReference[oaicite:8]{index=8}
- Heatmap showing correlations between batting statistics :contentReference[oaicite:9]{index=9}

---

## 📌 Key Insights Summary
- Longer careers and more innings lead to significantly higher run totals :contentReference[oaicite:10]{index=10}
- Players with **50+ averages** demonstrate elite consistency :contentReference[oaicite:11]{index=11}
- Australia dominates in **batting efficiency**, while England produces the **highest number of Test players** :contentReference[oaicite:12]{index=12}
- Only a handful of players score **300+** in Test cricket — extreme high-score outliers observed :contentReference[oaicite:13]{index=13}

---
## 📌 Future Enhancements

- Player ranking based on weighted performance metrics
- Interactive dashboard using Plotly / Power BI
- Predictive modeling to estimate player career longevity

## 👤 Author

**Anurag Patil**
Test Cricket Batting Data Analysis — 2025
