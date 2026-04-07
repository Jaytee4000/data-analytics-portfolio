# E-Commerce Product Usage & Engagement Analysis

## Project Overview
This project analyses large-scale e-commerce transactional data to uncover patterns in customer behavior, sales performance, and engagement trends.

The analysis simulates a real-world scenario where raw, unstructured data must be cleaned, transformed, and modeled before meaningful insights can be derived.

---

## Company Context (Fictitious)
This analysis is based on a fictional UK-based e-commerce company, ShopSphere, which sells a wide range of consumer goods across multiple countries.

The company aims to better understand:
- Customer engagement and retention  
- Sales trends over time  
- Geographic performance  
- Seasonal and behavioral purchasing patterns  

---

## Role: External Product Data Analyst
In this project, I assumed the role of an External Product Data Analyst engaged to:

- Audit and clean raw transactional data  
- Build a scalable data model for analysis  
- Identify key drivers of customer engagement  
- Deliver insights to support product, marketing, and operations teams  

---

## Dataset Overview

### Raw Dataset
Two datasets were provided:

- **2009–2010**
  - Rows: 525,462  
  - Columns: 8  

- **2010–2011**
  - Rows: 541,011  
  - Columns: 8  

**Total Raw Rows:** 1,066,473  

---

### After Cleaning & Transformation

- **Final Rows:** 820,626  
- **Rows Removed:** 245,847  
- **Data Reduction:** ~23.05%  

---

## Data Cleaning Summary

To ensure analytical accuracy, the dataset was rigorously cleaned:

- Removed rows with missing Customer IDs  
- Excluded cancelled transactions  
- Removed non-product StockCodes (e.g. adjustments, test entries, bank charges)  
- Eliminated negative or zero quantities  
- Standardized country naming (EIRE → Ireland)  
- Appended both datasets into a unified structure  

---

## Critical Data Insight

The removal of over 240,000 rows highlights how operational and system-generated data can significantly distort product analytics if not properly cleaned.

This demonstrates that:
- Raw data is not inherently reliable  
- Data cleaning is essential, not optional  
- Poor data quality can lead to misleading business decisions  

---

## Performance & Tooling Consideration

Due to the size of the dataset (over 1 million rows), Excel presented performance limitations during transformation, particularly with iterative filtering in Power Query.

To address this:
- The workflow was transitioned to Power BI for improved performance  
- A more scalable and structured data transformation approach was implemented  

This reflects real-world analytical practice where tool selection must align with data scale and complexity.

---

## Dashboard Preview

### Sales & Engagement Overview
![Overview](https://github.com/Jaytee4000/data-analytics-portfolio/blob/e48401abd8012052d8656c93da310908204d46e4/Product%20Usage%20%26%20Engagement%20Analysis/Overview.png)

### Transaction Trends
![Time Analysis](https://github.com/Jaytee4000/data-analytics-portfolio/blob/586eedc587b6f1b0b0b01e19d8f1eca4297035df/Product%20Usage%20%26%20Engagement%20Analysis/Time%20Analysis.png)

---

## Key Insights

### Time-Based Insights
- Thursday is the peak transaction day, indicating pre-weekend purchasing behavior  
- Morning and afternoon periods drive the highest activity  
- Strong seasonal spikes occur in Q4 (October–December)  
- Post-holiday decline observed in January and February  
- Overall upward trend from 2009 to 2011 indicates business growth  

---

### Customer Engagement Insights
- 75.63% of customers are repeat buyers  
- 24.37% are one-time buyers  
- Customer 12748 recorded the highest activity with 343 transactions  
- A small group of high-frequency users drives a large share of transactions  

---

### Customer Segmentation Insights
- Regular customers form the largest segment  
- Occasional customers represent strong growth potential  
- Champions (10+ transactions) are the most valuable but smallest group  
- One-time buyers present re-engagement opportunities  

---

### Geographic Insights
- The United Kingdom dominates both revenue and transaction volume  
- Germany, France, and Ireland follow but at significantly lower levels  

---

### Data Quality Observations
- 2009 data is limited to December and should not be used for full-year comparison  
- EIRE and Ireland appear as separate entries and require consolidation  
- Some timestamps default to 31/12/1899, indicating parsing issues  

---

## Business Recommendations

- Align promotions with peak activity periods (Thursday and weekends)  
- Launch mid-week marketing campaigns to drive conversions  
- Strengthen loyalty programs to move customers into higher-value segments  
- Retain high-value customers (Champions) with exclusive incentives  
- Re-engage one-time buyers using personalized marketing  
- Improve data governance to prevent inconsistencies in future datasets  

---

## Tools and Technologies
- Microsoft Excel  
- Power Query  
- Power BI  
- Data Modeling and Transformation Techniques  

---

## Skills Demonstrated
- Large-scale data cleaning and validation  
- Data modeling and transformation  
- Performance-aware tool selection  
- Customer segmentation and behavioral analysis  
- Time-series analysis  
- Business insight generation and storytelling  

---

## Project Value
This project demonstrates the ability to:
- Handle large, messy datasets in a realistic environment  
- Identify and correct data quality issues  
- Translate data into actionable business insights  
- Think beyond analysis into product and business strategy  

---

## Project Walkthrough (Video)
[Watch Dashboard Demo](https://youtu.be/sUwxbkWZmfw?si=tCHEo4tr2eJdBxo0)

---

## Connect With Me
- LinkedIn: https://www.linkedin.com/in/your-link  
- Email: your-email@example.com
