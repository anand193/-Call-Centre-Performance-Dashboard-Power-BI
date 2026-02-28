# 📞 Call Centre Performance Dashboard – Power BI

## 📌 Project Overview
This project analyzes call center performance using an interactive Power BI dashboard.  
It provides operational insights into call volume, response time, SLA compliance, sentiment analysis, channel performance, and state-level distribution.

The dashboard is designed to help management monitor service efficiency, customer satisfaction, and operational performance.

---

## 🎯 Business Objective
The goal of this dashboard is to:

- Monitor total call volume and call duration
- Track SLA compliance and response time %
- Analyze call distribution by state
- Identify major call reasons
- Evaluate channel performance (Call Center, Web, Email, Chatbot)
- Monitor customer sentiment trends
- Analyze performance by call centers

---

## 📊 Key Performance Indicators (KPIs)

- 📞 Total Calls: **32.94K**
- ⏱ Total Call Duration (Hours): **13.74K**
- 🕒 Total Call Duration (Minutes): **824K**
- 📊 Avg Call Duration: **25.02 Minutes**
- 📈 Response Time (SLA %): **75.26%**

---

## 🗂 Dataset Description
The dataset includes:

- Call ID
- Customer Name
- Channel
- State
- City
- Call Reason (Billing, Payments, Service Outage)
- Response Time (Within SLA / Above SLA / Below SLA)
- Call Duration
- Sentiment Category
- Call Center Location
- Call Date

Data cleaning and transformation were performed using **Power Query**, and KPIs were created using **DAX measures**.

---

## 🛠 Tools & Technologies Used

- Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Map Visualization
- Treemap & Donut Charts

---

## 📈 Dashboard Pages

### 🏠 Home Page (Executive View)

Provides high-level insights:

- Total Calls by Day
- Calls by State (Map)
- Calls by Reason (Treemap)
- Calls by Channel (Donut Chart)
- Calls by Sentiment
- Calls by Call Centers
- SLA Performance %

This page is designed for senior management monitoring.

---

### 📊 Grid Page (Detailed View)

Provides:

- Complete call-level transaction table
- Filter panel (Date, Channel, City)
- SLA status visibility
- Customer-level interaction tracking

This page is useful for operational teams.

---

## 🔍 Key Insights

- Majority of calls are related to **Billing Questions**.
- 75% of calls are handled within SLA.
- Certain states generate significantly higher call volume.
- Negative and Neutral sentiments are dominant, indicating improvement opportunity.
- Call Center channel contributes highest interaction share.
- Some call centers outperform others in total volume handled.

---

## 📌 Business Recommendations

- Improve SLA compliance for below-SLA cases.
- Address root causes behind negative sentiment calls.
- Optimize staffing in high-call-volume states.
- Enhance chatbot and digital channels to reduce manual call load.
- Provide training for recurring billing-related issues.

---

## 🧠 Technical Highlights (DAX Concepts Used)

- Total Calls Measure
- Average Call Duration Calculation
- SLA % Calculation
- Sentiment Distribution %
- Dynamic Filtering by Date / Channel / City
- State-wise Aggregation
- Drill-through & Cross-filtering

---

## 📷 Dashboard Preview

### 🏠 Home View
![Call Centre Dashboard - Home](Images/home_dashboard_preview.png)

### 📊 Grid View
![Call Centre Dashboard - Grid](Images/grid_dashboard_preview.png)

---

## 🚀 How to Use

1. Download the `.pbix` file from the repository.
2. Open it in Power BI Desktop.
3. Use filters (Date, Channel, City) to explore call trends.
4. Navigate between Home and Grid pages for summary and detailed analysis.

---

## 👤 Author

Anand Mehto  
Aspiring Data Analyst | SQL | Python | Power BI | Machine Learning  

---

⭐ If you found this project useful, feel free to connect or provide feedback!
