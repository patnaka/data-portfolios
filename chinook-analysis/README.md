# 💽 Chinook SQL Data Analysis Project

![Dashboard Preview](./Chinook_Dashboard.pdf)

---

## 🎯 Objective

Analyze the Chinook music store database using SQL to uncover useful business insights.

---

## 🛠 Tools Used

- **Google Colab** (Python + SQLite) for database exploration and analysis
- **Google Looker Studio** for dashboard creation and data visualization

---

## 🧩 Process

1. **Data Import & Exploration:** 
   - Source: [View Dataset](https://www.sqlitetutorial.net/sqlite-sample-database/)
     
1. **Querying with SQL (in Google Colab):**
   - Connected to `chinook.db` using `sqlite3`
   - Performed queries to explore:
     - Total revenue customers
     - Top customers by spending
     - Top selling artists
     - Top selling genres
     - Total songs of each genres
     - Monthly revenue trends in 2011-2013
     - Customer geography spend over $100
   - Exported results to `.csv`

2. **Data Visualization (in Google Looker Studio):**
   - Connected `.csv` files to Google Looker Studio
   - Created interactive dashboard with KPLs, pie charts, map, and time series graphs

**Colab Notebook:** [View Code](https://colab.research.google.com/drive/1envLnCs3NegPiYiNw1Q6GxbWqlUNKENg)  
**Dashboard:** [View Dashboard](https://lookerstudio.google.com/reporting/1f54236b-12fd-4ceb-ad4c-0f7cdde85901/page/gWgOF)

---

## 🔰 Business Insight:
- The USA, Canada, and Germany are the top revenue-generating countries. Therefore focus loyalty programs and region-specific marketing in these areas.
- Rock is the most purchased genre and  Queen, AC/DC, and U2 are top-selling artists. Therefore promote best-selling genres and artists to boost engagement.
- Plan marketing campaigns around peak sales months or promote plan holiday campaigns aroun drop months.

---

Created by **Narueporn J.** | For Data Analyst Portfolio | Feel free to connect or leave feedback! ☺

