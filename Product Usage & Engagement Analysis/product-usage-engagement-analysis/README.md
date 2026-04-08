# E-Commerce Product Usage & Engagement Analysis

## Overview

Analyzed over 1 million e-commerce transactions to uncover patterns in customer behavior, engagement, and sales performance.

This project simulates a real-world product analytics scenario where raw, unstructured data is transformed into actionable insights to support product, marketing, and growth decisions.

---

## Key Impact

- Processed and cleaned **1M+ rows**, improving data reliability by removing ~23% invalid records  
- Identified **repeat customers (75.6%) as primary revenue drivers**  
- Discovered **peak engagement periods (Thursdays, mornings, Q4 seasonality)**  
- Highlighted **high-value customer segments (Champions & Regulars)**  
- Revealed **user drop-off between first purchase and repeat engagement**  

---

## Business Context

This analysis is based on a fictional UK-based e-commerce company, **ShopSphere**, operating across multiple international markets.

The company aims to understand:

- Customer engagement and retention  
- Product usage behavior  
- Geographic performance  
- Seasonal purchasing trends  

---

## Problem Statement

ShopSphere lacks visibility into how users interact with its platform.

Key questions include:

- What does active usage look like?  
- Which customer segments drive engagement?  
- Where do users drop off in their lifecycle?  
- How does engagement vary across time and geography?  

---

## Role

**External Product Data Analyst**

- Cleaned and validated large-scale transactional data  
- Built a scalable data model for analysis  
- Defined engagement and behavioral metrics  
- Delivered insights to inform product and marketing strategy  

---

## Dataset Overview

### Raw Data

- 2009–2010: 525,462 rows  
- 2010–2011: 541,011 rows  

**Total:** 1,066,473 rows  

---

### After Cleaning

- Final dataset: 820,626 rows  
- Rows removed: 245,847  
- Reduction: ~23.05%  

---

## Data Cleaning & Preparation

To ensure analytical accuracy:

- Removed missing Customer IDs  
- Excluded cancelled transactions  
- Filtered non-product StockCodes (e.g. adjustments, charges)  
- Removed negative/zero quantities  
- Standardized country naming (EIRE → Ireland)  
- Combined both datasets into a unified model  

---

## Critical Data Insight

Over **240,000 rows were removed**, highlighting how raw operational data can distort analysis.

This reinforces that:

- Data cleaning is essential for reliable insights  
- Poor data quality directly impacts business decisions  

---

## Performance & Tooling

Due to dataset size (>1M rows), Excel showed performance limitations.

Solution:
- Transitioned to **Power BI** for scalable transformation and analysis  
- Implemented a more efficient data modeling workflow  

---

## Product Analytics Insights

### Active Usage

Active usage was defined as customers completing at least one valid transaction.

- Strong concentration of activity during **morning and afternoon hours**  
- Peak usage observed on **Thursdays**, indicating pre-weekend purchasing behavior  
- Significant spikes in **Q4 (Oct–Dec)** driven by seasonal demand  

---

### Feature Engagement

Engagement was evaluated through transaction behavior and repeat activity:

- **75.63% repeat customers** indicate strong product-market fit  
- A small group of high-frequency users contributes disproportionately to total activity  
- Customer **12748** recorded the highest engagement (343 transactions)  

This suggests that:
- Repeat interaction is a key driver of business performance  
- High-engagement users represent critical product value  

---

### User Drop-Off

A simplified lifecycle analysis shows:

- High initial customer acquisition  
- Significant drop-off after first purchase (24.37% one-time buyers)  
- Only a subset transitions into repeat or high-value users  

This indicates:
- Friction in post-purchase engagement  
- Opportunity to improve retention strategies  

---

### Customer Segmentation

- **Champions (10+ transactions):** Highest value, lowest volume  
- **Regular Customers:** Core revenue contributors  
- **Occasional Customers:** Growth opportunity  
- **One-Time Buyers:** High drop-off segment  

---

### Time-Based Trends

- Peak day: **Thursday**  
- Peak periods: **Morning & Afternoon**  
- Strong **Q4 seasonality**  
- Post-holiday decline in **January–February**  
- Overall upward trend (2009–2011)  

---

### Geographic Insights

- UK dominates revenue and transaction volume  
- Germany, France, and Ireland show growth potential  

---

### Data Quality Observations

- 2009 data limited to December (not suitable for full-year comparison)  
- Duplicate country naming (EIRE vs Ireland)  
- Invalid timestamps (31/12/1899) indicate parsing issues  

---

## Dashboard 

### Sales & Engagement Overview
![Overview](https://github.com/Jaytee4000/data-analytics-portfolio/blob/e48401abd8012052d8656c93da310908204d46e4/Product%20Usage%20%26%20Engagement%20Analysis/Overview.png)

### Transaction Trends
![Time Analysis](https://github.com/Jaytee4000/data-analytics-portfolio/blob/586eedc587b6f1b0b0b01e19d8f1eca4297035df/Product%20Usage%20%26%20%26%20Engagement%20Analysis/Time%20Analysis.png)

---

## Business Recommendations

- Align promotions with **peak engagement periods (Thursdays, Q4)**  
- Improve **post-purchase engagement** to reduce drop-off  
- Strengthen loyalty programs to grow **Champion customers**  
- Re-engage one-time buyers with targeted campaigns  
- Expand marketing efforts in **Germany, France, and Ireland**  
- Improve data governance to prevent inconsistencies  

---

## Tools & Technologies

- Excel  
- Power Query  
- Power BI  
- Data Modeling Techniques  

---

## Skills Demonstrated

- Large-scale data cleaning (1M+ rows)  
- Product analytics thinking (engagement, retention, lifecycle)  
- Customer segmentation  
- Time-series analysis  
- Performance-aware tool selection  
- Business insight communication  

---

## Why This Project Matters

This project demonstrates the ability to:

- Work with real-world, messy datasets at scale  
- Apply product thinking to user behavior analysis  
- Identify engagement drivers and drop-off points  
- Translate data into actionable business strategy  

---

## Project Walkthrough

[Watch Dashboard Demo](https://youtu.be/sUwxbkWZmfw?si=tCHEo4tr2eJdBxo0)

---

## Contact

- LinkedIn: https://www.linkedin.com/in/tjumukoro95  
- Email: terryjosephumukoro95@gmail.com  
