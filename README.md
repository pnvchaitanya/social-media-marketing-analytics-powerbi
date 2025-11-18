# **Social Media Ad Performance Dashboard (Power BI + Python)**



##### This project is an end-to-end analysis of a Social Media Advertisement dataset.

##### I cleaned the data using Python, modeled it into a star schema, and built a 5-page interactive Power BI dashboard to understand:

##### 

##### Who engages with ads

##### 

##### Which ads perform best

##### 

##### Which campaigns give the best ROI

##### 

##### How performance changes over time

##### 

##### It shows a complete journey from raw CSVs → data cleaning → modeling → visualization.



#### What this project includes

#### **1. Raw Data (from Kaggle)**



##### The dataset contains:

##### 

##### Ads

##### 

##### Campaigns

##### 

##### Users

##### 

##### Ad events (impressions, clicks, likes, comments, shares, purchases)



#### **2. Data Cleaning (Python)**



##### I cleaned the data using Pandas:

##### 

##### Removed duplicates

##### 

##### Fixed inconsistent user entries

##### 

##### Split data into dim\_ad, dim\_campaign, dim\_user, and fact\_ad\_events

##### 

##### Exported cleaned tables for Power BI



#### **3. Data Model (Power BI)**



##### I built a star schema:

##### 

##### DimCampaign → DimAd → FactAdEvents ← DimUser

##### 

##### 

##### This helps create clear, fast, easy-to-understand visuals.



#### **4. DAX Measures**



##### Created key metrics such as:

##### 

##### Impressions

##### 

##### Clicks

##### 

##### CTR (Click-Through Rate)

##### 

##### Engagement Rate

##### 

##### Conversion Rate

##### 

##### CPC (Cost per Click)

##### 

##### CPA (Cost per Acquisition)

##### 

##### Ad Performance Score (custom metric)



### Dashboard Pages (5 Pages)

### **Page 1 — Executive Summary**



##### High-level performance:

##### 

##### Impressions, clicks, engagements, purchases

##### 

##### Click-through rate, conversion rate

##### 

##### Top platforms, countries, interests

##### 

##### Monthly engagement trend



### **Page 2 — Audience Insights**



##### Breakdown by:

##### 

##### Age group

##### 

##### Gender

##### 

##### Country

##### 

##### Interests

##### Helps understand who is engaging with ads.



### **Page 3 — Ad Performance**



##### Shows which ads perform best:

##### 

##### Top \& bottom CTR ads

##### 

##### Ad type comparison

##### 

##### Facebook vs Instagram

##### 

##### Detailed table with performance score



### **Page 4 — Campaign ROI**



##### Budget-focused analysis:

##### 

##### CPC and CPA

##### 

##### Budget vs performance

##### 

##### Which campaigns should be scaled or paused



### **Page 5 — Time Series Analysis**



##### Time-based patterns:

##### 

##### Heatmap (hour × day)

##### 

##### Day-part performance

##### 

##### Weekly trends

##### 

##### Monthly CTR \& conversion trends



### **Key Takeaways**



##### From this project, I practiced:

##### 

##### Data cleaning and prep (Python)

##### 

##### Building a proper star schema

##### 

##### Writing DAX measures

##### 

##### Designing a multi-page Power BI dashboard

##### 

##### Extracting useful business insights from marketing data

##### 

##### This is a real-world style BI project showing how ads perform, which audiences to target, and where budgets should go.

