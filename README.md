# Data_Analysis_Project
# 📱 Digital Addiction Trends by Country and Age Group

## 🧠 Project Overview

**Goal:**  
This project analyzes digital addiction patterns—particularly phone and social media usage—across different countries and age groups. It correlates screen time with sleep disorders, anxiety levels and productivity loss using publicly available datasets and APIs.

**Impact:**  
The resulting analysis and dashboard aim to inform public health policies, education campaigns and mental wellness programs addressing tech overuse and digital burnout.

---

## 🚨 Problem Statement

With increasing screen time and 24/7 connectivity, digital addiction has become a global issue. The problem is particularly alarming among teenagers and working adults, affecting attention spans, mental health, sleep quality and job performance.

---

## 🗂️ Project Structure
digital-addiction-analysis/
├── data/
│ ├── raw/
│ └── processed/
├── notebooks/
│ ├── 01_data_collection.ipynb
│ ├── 02_cleaning_transforming.ipynb
│ └── 03_analysis_visualization.ipynb
├── scripts/
│ ├── fetch_statista_data.py
│ └── sleep_anxiety_merge.py
├── dashboard/
│ └── digital_addiction_dashboard.pbix
├── README.md
└── Project.md


---

## 🧪 Tools & Technologies

- **Languages**: Python (Pandas, Matplotlib, Seaborn), SQL  
- **APIs & Data Sources**:
  - [Statista](https://www.statista.com/)
  - [WHO Mental Health Data](https://www.who.int/data)
  - [Sleep Foundation Reports](https://www.sleepfoundation.org/)
  - [Our World In Data](https://ourworldindata.org/)
- **Database**: PostgreSQL or Google BigQuery  
- **Visualization**: Power BI / Tableau / Plotly Dash  
- **ETL Tools**: Python scripts, Pandas

---

## 🔄 Workflow Overview

1. **Data Collection**  
   - Extract screen time and internet usage statistics by country/age
   - Get mental health and sleep disorder indicators
   - Normalize datasets for joining on country and age

2. **ETL Pipeline**
   - Clean, transform, and join datasets
   - Store in PostgreSQL/BigQuery for query optimization

3. **Analysis**
   - Compare screen time vs anxiety/sleep metrics
   - Identify high-risk countries and age groups
   - Use correlation and clustering to find behavioral patterns

4. **Dashboard**
   - Filter by region, age group, screen time and health outcome
   - Highlight hotspots with high addiction and poor wellness

---

## 📊 Key Questions

- Which countries and age groups exhibit the highest screen time?
- Is there a visible correlation between phone usage and sleep quality or mental health issues?
- Which populations are most vulnerable to digital burnout?
- Can we recommend intervention targets for public health outreach?

---

## ✅ Output

- 📈 Power BI Dashboard showing usage trends, sleep and anxiety scores
- 📁 CSV/SQL datasets for future research
- 📄 Technical article/insight report for social impact audiences

---

## 🤝 Contributions

Feel free to open issues or suggest improvements via pull requests.
