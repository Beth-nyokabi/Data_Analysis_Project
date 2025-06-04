# 📱 Digital Addiction Trends by Country and Age Group

## Capstone Project Summary

### 🎯 Problem

Excessive screen time—especially on phones and social media platforms—has become a growing global concern. It's been linked to increased anxiety, sleep disorders, attention deficits and reduced productivity, especially among teenagers and working adults.

Despite this, few public dashboards or data models show where digital addiction is most prevalent and how it correlates with mental health or productivity indicators.

---

### 🧠 Objective

Build an end-to-end data analytics pipeline that:

- Collects data on screen time by country and age group
- Correlates it with indicators of sleep health, anxiety and economic productivity
- Visualizes risk areas and high-risk groups
- Supports health organizations and digital wellness campaigns

---

### 🧰 Tools and Technologies

| Component | Tool |
|----------|------|
| Data Sourcing | Statista, WHO, Sleep Foundation, Our World In Data |
| ETL | Python (Pandas, Requests), PostgreSQL |
| Data Analysis | Python, Jupyter, Seaborn, Matplotlib |
| Visualization | Power BI / Tableau |
| Deployment | GitHub for versioning, Docker (optional) for reproducibility |

---

### 🔄 Workflow

1. **Data Collection**  
   - Scrape or pull APIs from trusted sources
   - Screen time by age & country (Statista)
   - Anxiety, depression, sleep disorder prevalence (WHO)
   - Sleep quality & productivity (Sleep Foundation, OECD)

2. **ETL & Cleaning**  
   - Standardize formats (age brackets, countries)
   - Merge datasets on common fields
   - Calculate key metrics (screen time per day, depression rates, sleep hours)

3. **Analysis**  
   - Correlation between screen time and mental health
   - Clustering to find risk groups
   - Time-series comparison if historical data is available

4. **Dashboard**
   - Filters: country, age group, risk type
   - Visuals: Choropleth maps, scatter plots, KPI cards
   - Downloads: CSV reports for policymakers

---

### 📈 Expected Insights

- Country-level map of digital addiction risk
- List of most vulnerable age groups
- Statistical correlation between screen time and anxiety
- Sleep disorder prevalence among high-usage populations

---

### 🧭 Social Impact

- Public health departments can target digital hygiene campaigns more precisely
- NGOs can prioritize sleep and mental health outreach programs
- Schools and employers can implement screen time management strategies

---


### 📌 Bonus Ideas (Optional)

- Use machine learning to predict addiction risk scores
- Add sentiment analysis from Reddit or Twitter for behavioral trends
- Visualize productivity vs screen time over time

---

### 🙌 Acknowledgements

- WHO, Statista and the Sleep Foundation for open/public data
- Professors and course mentors for guidance

