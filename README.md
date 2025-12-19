# Brownwall Sales Data Analysis

## Overview
This project focuses on cleaning, analyzing, and visualizing sales inquiry data for Brownwall to generate meaningful business insights. Python was used for data cleaning and preprocessing, and an interactive dashboard was built using Google Looker Studio to support data-driven decision-making.

---

## Tools Used
- Python (Pandas) for data cleaning and analysis  
- Google Colab for notebook execution  
- Google Looker Studio for dashboard creation  

---

## Data Cleaning
The raw dataset was cleaned using Python to ensure accuracy and consistency. This included handling missing values, standardizing column names and formats, converting revenue fields to numeric values, and creating calculated fields required for analysis. The cleaned dataset was then used as the data source for the dashboard.

---

## Key Performance Indicators (KPIs)

**Estimated Business Generated from Sun Pharma**  
This KPI shows the total expected revenue generated from Sun Pharma, helping assess the contribution of a key client to overall business.

**Most Potential Client by Expected Revenue**  
Identifies the client with the highest expected revenue, allowing management to focus on high-value accounts and prioritize relationship management.

**Best Salesperson**  
This KPI evaluates salesperson performance using two perspectives:
- Number of clients handled  
- Total expected revenue generated  
It helps compare workload distribution and revenue efficiency across the sales team.

**Salesperson Handling the Biggest Client**  
Displays which salesperson manages the highest-value client, supporting key account ownership analysis and risk assessment.

**Average Deal Size**  
Calculated as total expected revenue divided by the number of unique clients, this KPI measures deal quality and helps evaluate whether revenue growth should focus on larger deals or higher deal volume.

---

## Dashboard
An interactive Google Looker Studio dashboard was created to visualize all KPIs using scorecards, bar charts, and tables. The dashboard allows users to quickly identify top clients, high-performing salespeople, and overall revenue trends.

Dashboard Link:  
https://lookerstudio.google.com/reporting/851328de-78cf-4bc9-aca4-5c02532bf1ef

---

## Assumptions
- Expected revenue represents potential business, not confirmed sales  
- All revenue values are assumed to be in INR (₹)  
- Missing revenue values were treated as zero during data cleaning  
- Client names were standardized to avoid duplication  
---
## Conclusion
This project demonstrates an end-to-end data analytics workflow, from raw data cleaning to actionable business insights. The dashboard provides a clear view of revenue potential, client importance, and salesperson performance, enabling management to make informed strategic decisions.
