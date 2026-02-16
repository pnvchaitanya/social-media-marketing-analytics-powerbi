# Social Media Ad Performance Dashboard  
**Power BI | Python | DAX | Star Schema Modeling**

## Project Overview
This project is an end-to-end **Business Intelligence solution** built to analyze and optimize **social media advertising performance**.

Starting from raw CSV files, I:
- Cleaned and transformed the data using **Python**
- Designed a **star schema data model**
- Built a **5-page interactive Power BI dashboard**
- Delivered **actionable marketing and ROI insights**

The dashboard answers key business questions such as:
- Who engages with ads?
- Which ads and campaigns perform best?
- Where is ad budget being wasted or underutilized?
- How does ad performance change over time?

This project mirrors a **real-world marketing analytics workflow** used by BI and analytics teams.

---

## Data Source
**Kaggle – Social Media Advertisement Dataset**

### Raw Data Includes:
- Ads  
- Campaigns  
- Users  
- Ad Events  
  *(impressions, clicks, likes, comments, shares, purchases)*

---

## Data Cleaning & Transformation (Python)
All preprocessing was performed using **Pandas** to ensure clean, analysis-ready data.

### Key Steps:
- Removed duplicate records
- Fixed inconsistent user attributes
- Validated event-level data
- Split raw data into analytical tables
- Exported cleaned datasets for Power BI

### Final Tables:
- `dim_ad`
- `dim_campaign`
- `dim_user`
- `fact_ad_events`

---

## Data Modeling (Power BI)
A **star schema** was designed to ensure:
- High performance
- Simple relationships
- Clean DAX calculations
- Scalable reporting

### Schema Design:

---

## DAX Measures & Metrics
Business-focused KPIs commonly used by marketing teams were created.

### Core Metrics:
- Impressions  
- Clicks  
- Engagements  
- Purchases  

### Performance Metrics:
- CTR (Click-Through Rate)
- Engagement Rate
- Conversion Rate
- CPC (Cost per Click)
- CPA (Cost per Acquisition)

### Advanced Metric:
- **Ad Performance Score**  
  *(Custom metric combining engagement, CTR, and conversions)*

---

## Dashboard Pages

### Page 1 — Executive Summary
High-level snapshot for stakeholders:
- Total impressions, clicks, engagements, purchases
- CTR and conversion rate
- Top platforms, countries, and interests
- Monthly engagement trend

---

### Page 2 — Audience Insights
Understanding **who** engages with ads:
- Age groups
- Gender distribution
- Countries
- User interests

---

### Page 3 — Ad Performance
Identifies top and bottom-performing ads:
- Best and worst ads by CTR
- Ad type comparison
- Facebook vs Instagram performance
- Detailed performance table with custom score

---

### Page 4 — Campaign ROI
Budget and efficiency analysis:
- CPC and CPA by campaign
- Budget vs performance
- Clear recommendations on which campaigns to scale or pause

---

### Page 5 — Time Series Analysis
Time-based behavior and trends:
- Hour × Day heatmap
- Day-part performance
- Weekly trends
- Monthly CTR and conversion trends

---

## Key Takeaways
This project strengthened hands-on skills in:
- Data cleaning and preparation (Python / Pandas)
- Dimensional modeling (Star Schema)
- Writing optimized DAX measures
- Designing multi-page Power BI dashboards
- Translating marketing data into actionable business insights

---

## Why This Project Matters
This is a **real-world BI project**, not a toy dataset.

It demonstrates how data analysts:
- Evaluate advertising performance
- Identify high-value audiences
- Optimize marketing spend
- Support data-driven decision-making

Relevant for roles such as:
- Data Analyst
- Business Intelligence Analyst
- Marketing Analyst
- BI Consultant







