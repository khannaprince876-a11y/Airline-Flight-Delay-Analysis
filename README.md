# ✈️ Airline Flight Delay Analysis 

## 📌 Project Overview

This project is an end-to-end Data Analytics and Business Intelligence solution developed using Excel, SQL, Python, and Power BI to analyze airline performance, flight delay patterns, route efficiency, and cancellation trends using real-world U.S. domestic flight data.

The objective of this project is to identify operational inefficiencies, uncover delay patterns, evaluate airline performance, and provide actionable insights that can help airlines improve customer satisfaction and optimize flight operations.

By combining data cleaning, SQL analysis, exploratory data analysis (EDA), and interactive dashboarding, this project transforms raw flight records into meaningful business intelligence for data-driven decision-making.

---

## 🎯 Business Problem

Flight delays and cancellations significantly impact customer experience, operational efficiency, and airline profitability. Understanding the factors contributing to delays is essential for improving scheduling, resource allocation, and overall performance.

Key business questions addressed in this project include:

- Which airlines experience the highest delays?
- What are the most delayed routes?
- How do delays vary across months and days of the week?
- What are the primary causes of flight cancellations?
- Which airports contribute most to delay occurrences?
- What operational improvements can reduce delays?

---

## 📊 Dataset Information

The dataset contains over 600,000 domestic flight records covering one year of airline operations across the United States.

### Dataset Features

- Flight Date
- Airline Carrier
- Origin Airport
- Destination Airport
- Departure Delay
- Arrival Delay
- Cancellation Status
- Cancellation Reason
- Flight Distance
- Flight Time

### Dataset Source

Dataset Link:

https://www.kaggle.com/datasets/usdot/flight-delays

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|--------|---------|
| Excel | Data Cleaning & Preparation |
| SQL | Data Transformation & Analysis |
| Python | Exploratory Data Analysis |
| Power BI | Dashboard Development |
| GitHub | Documentation & Version Control |

---

## 📋 Project Workflow

### 1. Data Collection & Understanding

- Imported and explored flight records.
- Reviewed data structure and quality.
- Identified relevant variables for analysis.

### 2. Data Cleaning

- Handled missing values.
- Standardized date and time formats.
- Removed duplicate records.
- Corrected inconsistent airport and airline codes.

### 3. SQL Analysis

- Performed aggregations and filtering.
- Created analytical queries using joins and CTEs.
- Calculated airline performance metrics.
- Identified delay and cancellation patterns.

### 4. Exploratory Data Analysis (EDA)

- Delay trend analysis.
- Airline performance comparison.
- Route analysis.
- Cancellation analysis.
- Seasonal trend analysis.

### 5. Dashboard Development

Developed an interactive Power BI dashboard allowing stakeholders to:

- Monitor flight delays.
- Analyze airline performance.
- Evaluate route efficiency.
- Track cancellation trends.
- Identify operational bottlenecks.

---

## 📈 Key Performance Indicators (KPIs)

- Total Flights
- Average Departure Delay
- Average Arrival Delay
- Total Delayed Flights
- Total Cancelled Flights
- On-Time Performance Rate
- Most Delayed Airline
- Most Delayed Route

---

## ❓ Business Questions Answered

### Airline Performance

- Which airline has the highest average delay?
- Which airline demonstrates the best on-time performance?

### Route Analysis

- What are the top 5 most delayed routes?
- Which routes consistently experience operational issues?

### Time-Based Analysis

- How do delays vary by month?
- Which days of the week experience the highest delays?

### Cancellation Analysis

- What are the most common cancellation reasons?
- Which airlines have the highest cancellation rates?

---

## 📊 Dashboard Features

### Executive Summary

High-level overview of airline performance metrics.

### Delay Analysis

- Departure Delay Trends
- Arrival Delay Trends
- Monthly Delay Analysis

### Airline Performance

- Airline Ranking
- On-Time Performance Comparison

### Route Analysis

- Most Delayed Routes
- Airport Performance Analysis

### Cancellation Analysis

- Cancellation Reasons
- Airline Cancellation Rates

### Interactive Filters

- Airline
- Month
- Airport
- Route

---

## 🔍 Key Insights

### Route Performance

- Identified the top 5 routes with the highest average delays.
- Certain airport pairs consistently experience operational disruptions.

### Airline Performance

- Significant performance differences exist across airlines.
- Some carriers maintain substantially higher on-time rates.

### Seasonal Trends

- Delays increase during peak travel periods.
- Weather-related disruptions contribute to seasonal fluctuations.

### Cancellation Analysis

- Weather conditions represent the leading cause of cancellations.
- Operational issues account for a significant portion of flight disruptions.

### Airport Operations

- Major hub airports experience higher delay frequencies due to traffic volume.

---

## 💡 Business Recommendations

### Operational Planning

Optimize scheduling during peak travel periods to reduce congestion-related delays.

### Resource Allocation

Increase staffing and operational support at high-delay airports.

### Route Optimization

Review underperforming routes and implement schedule adjustments.

### Customer Experience

Provide proactive communication and compensation strategies during disruptions.

### Predictive Analytics

Develop machine learning models to forecast delays and improve operational planning.

---

## 🚀 Skills Demonstrated

- Data Cleaning & Wrangling
- SQL Joins
- Common Table Expressions (CTEs)
- Aggregations & Window Functions
- Exploratory Data Analysis (EDA)
- Python (Pandas, NumPy, Matplotlib)
- Business Intelligence
- Power BI Dashboard Development
- KPI Design
- Data Visualization
- Data Storytelling

---

## 📁 Repository Structure

```text
Airline-Flight-Delay-Analysis/
│
├── README.md
│
├── dataset/
│   └── flight_data.csv
│
├── sql/
│   └── flight_analysis_queries.sql
│
├── notebooks/
│   └── Airline_Delay_Analysis.ipynb
│
├── dashboard/
│   └── Airline_Flight_Delay_Dashboard.pbix
│
├── images/
│   └── Dashboard.png
│
└── presentation/
    └── Airline_Flight_Delay_Analysis.pptx
```

---

## 📌 Conclusion

This project demonstrates how data analytics and business intelligence can be applied to airline operations to identify delay patterns, improve operational efficiency, and enhance customer experience. The insights generated provide valuable guidance for optimizing airline performance and supporting strategic decision-making.
