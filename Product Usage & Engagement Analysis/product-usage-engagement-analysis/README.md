# E-Commerce Product Usage & Engagement Analysis

## Overview

Analyzed over 1 million e-commerce transactions to uncover patterns in customer behavior, engagement, and revenue performance.

This project simulates a real-world product analytics scenario, where raw transactional data is transformed into structured insights to support product, marketing, and growth decisions.

---

## Key Impact

- Processed and cleaned 1M+ rows, improving data reliability by removing ~23% invalid records
- Quantified £16.71M in revenue across 44K transactions
- Identified repeat customers (75.63%) as primary engagement drivers
- Discovered behavioral concentration across time (Thursdays, afternoons, Q4 seasonality)
- Revealed 24.37% user drop-off after first purchase
- Highlighted revenue concentration in a single dominant market (UK)

---

## Business Context

This analysis is based on a fictional UK-based e-commerce company, ShopSphere, operating across multiple international markets.

The company aims to understand:

- Customer engagement and retention
- Product usage behavior
- Geographic performance
- Seasonal purchasing patterns

---

## Problem Statement

ShopSphere lacks visibility into how users interact with its platform.

Key questions include:

- What does active usage look like?
- Which users drive engagement and revenue?
- Where do users drop off in their lifecycle?
- How does engagement vary across time and geography?

---

## Role

**External Product Data Analyst**

- Cleaned and validated large-scale transactional data
- Built a scalable data model for analysis
- Defined engagement and behavioral metrics (DAU/MAU proxies)
- Delivered insights to inform product and growth strategy

---

## Dataset Overview

### Raw Data

| Dataset | Rows |
|---|---|
| 2009 - 2010 | 525,462 |
| 2010 - 2011 | 541,011 |
| **Total** | **1,066,473** |

### After Cleaning

| Metric | Value |
|---|---|
| Final dataset | 820,626 rows |
| Rows removed | 245,847 |
| Reduction | ~23.05% |

---

## Data Cleaning & Preparation

To ensure analytical accuracy and behavioral relevance:

- Removed missing Customer IDs (ensuring valid user tracking)
- Excluded cancelled transactions (non-completed interactions)
- Filtered non-product StockCodes (e.g., adjustments, charges, test entries)
- Removed negative/zero quantities (returns or invalid activity)
- Standardized country naming (EIRE consolidated into Ireland)
- Combined both datasets into a unified model

### Critical Data Insight

Over 240,000 rows were removed, revealing that a significant portion of raw data represented non-behavioral or operational noise.

This highlights that raw transactional data can significantly distort product insights if not properly filtered.

---

## Performance & Tooling

Due to dataset size (>1M rows), Excel presented performance limitations during transformation.

**Solution:**

- Transitioned to Power BI for scalable data processing
- Implemented a structured and refreshable data model

---

## Product Analytics Insights

### Active Usage Patterns

User activity is not evenly distributed across time:

- Peak engagement occurs during afternoon hours, followed by mornings
- Thursday is the highest activity day, with consistent weekday dominance
- Minimal activity observed during evenings and weekends

This suggests usage is time-bound and operational, rather than habit-driven.

---

### Engagement & Customer Behavior

- 5,876 unique customers generated 44K transactions
- Average of 7.47 transactions per customer
- Customer 14911 recorded the highest activity (466 transactions)

A relatively small group of users drives a large share of engagement, indicating strong power-user concentration.

---

### Retention & User Drop-Off

- 75.63% repeat customers (~4K users)
- 24.37% one-time buyers (~1K users)

While retention is strong overall, nearly 1 in 4 users churn after their first interaction, indicating friction in early lifecycle engagement.

---

### Customer Segmentation

Customers were segmented by transaction frequency into four behavioral groups:

| Segment | Definition | Characteristic |
|---|---|---|
| Champions | 10+ transactions | High-frequency, high-value users |
| Regulars | 4 - 9 transactions | Core contributors to sustained activity |
| Occasionals | 2 - 3 transactions | Moderate engagement, growth potential |
| One-Time Buyers | 1 transaction | Largest drop-off segment |

Regulars form the largest segment, followed closely by Occasionals and One-Time Buyers. Champions, though the smallest group, represent the highest-value users and anchor revenue performance.

### Top 10 Most Active Customers

| Customer ID | Total Invoices |
|---|---|
| 14911 | 466 |
| 12748 | 343 |
| 17841 | 287 |
| 15311 | 269 |
| 14606 | 250 |
| 13089 | 247 |
| 14156 | 182 |
| 17850 | 159 |
| 13694 | 158 |
| 14646 | 153 |

Customer 14911 leads all users with 466 transactions, nearly 36% more than the second highest customer, indicating extreme power-user concentration at the top.

### Lifecycle Segmentation Story

The segmentation reveals a classic engagement funnel:

- Champions and Regulars anchor revenue and repeat activity despite being a small base
- Occasionals represent the highest growth opportunity, one nudge away from becoming Regulars
- One-Time Buyers signal early lifecycle friction that needs to be addressed through onboarding or re-engagement campaigns

This pattern confirms the business is sustained by a loyal core while a significant portion of acquired users remain under-engaged.

---

### Time-Based Trends

- Peak day: Thursday
- Peak session: Afternoon
- Strong Q4 seasonality (October to December spikes)
- Noticeable decline in January and February
- Overall upward trend from 2010 to 2011

The business exhibits seasonal and event-driven behavior, rather than stable year-round engagement.

---

### Geographic Insights

- United Kingdom dominates both revenue and transaction volume with over £7M in revenue contribution
- Germany, France, and Ireland contribute smaller but consistent volumes

The business is heavily UK-dependent, with international markets representing clear expansion opportunities.

---

## Data Quality Observations

- 2009 data is limited to December only (partial-year bias) and is excluded from year-on-year comparisons
- Duplicate country naming (EIRE vs Ireland) was identified and standardized
- Invalid timestamps (31/12/1899) indicate parsing inconsistencies in the raw data

---

## Dashboard

### Sales & Engagement Overview

![Overview](https://github.com/Jaytee4000/data-analytics-portfolio/blob/e48401abd8012052d8656c93da310908204d46e4/Product%20Usage%20%26%20Engagement%20Analysis/Overview.png)

**Key Insight:**
A relatively small customer base generates high transaction frequency and revenue, with strong repeat engagement but noticeable first-time user drop-off.

---

### Transaction Trends

![Time Analysis](https://github.com/Jaytee4000/data-analytics-portfolio/blob/58fa5548b1f1846a9170dc70689ae15b04a945b3/Product%20Usage%20%26)

**Key Insight:**
User activity is concentrated during weekdays and afternoons, with strong Q4 spikes, indicating time-bound and seasonal engagement patterns.

---

### Sales & Revenue by Geography

![Georgraphic Analysis](https://github.com/Jaytee4000/data-analytics-portfolio/blob/8d43a2bb785a7c3b8fe9eae869cc032712c17361/Product%20Usage%20%26%20Engagement%20Analysis/product-usage-engagement-analysis/Geographic%20Analysis.png)

**Key Insight:**
Revenue is heavily concentrated in the UK, highlighting both market dominance and geographic risk exposure.

---

### Customer Segmentation Analysis

![Customer Segmentation](https://github.com/Jaytee4000/data-analytics-portfolio/blob/8d43a2bb785a7c3b8fe9eae869cc032712c17361/Product%20Usage%20%26%20Engagement%20Analysis/product-usage-engagement-analysis/Customer%20Segmentation.png)

**Key Insight:**
Engagement and revenue are driven by a small but loyal customer base. Regulars and Champions sustain the business while Occasionals and One-Time Buyers represent the largest opportunity for lifecycle progression and re-engagement.

---

## Cross-Dashboard Insight

Across all analyses, three key patterns emerge:

- **Time Concentration** — Activity peaks on Thursdays and afternoons
- **Customer Concentration** — A small group drives most engagement and revenue
- **Seasonal Concentration** — Heavy reliance on Q4 performance

This indicates the product is event-driven, not habit-driven, and highly dependent on both seasonality and a core group of loyal users.

---

## Business Recommendations

- Improve post-purchase engagement to reduce first-time user drop-off
- Align marketing campaigns with peak periods (Thursdays, afternoons, Q4)
- Develop strategies to reduce seasonality dependency and drive year-round activity
- Expand into underperforming international markets to reduce UK revenue concentration
- Strengthen loyalty programs for Champions and Regulars to retain high-value users
- Re-engage One-Time Buyers through targeted follow-up campaigns and personalized product recommendations
- Move Occasionals up the engagement ladder with incentives and frequency-based rewards

---

## Tools & Technologies

- Excel
- Power Query
- Power BI
- DAX (Data Analysis Expressions)
- Data Modeling

---

## Skills Demonstrated

- Large-scale data cleaning (1M+ rows)
- Product analytics thinking (engagement, retention, lifecycle)
- Customer segmentation and behavioral analysis
- Time-series and trend analysis
- Performance-aware tool selection
- Business insight communication

---

## Why This Project Matters

This project demonstrates the ability to:

- Work with real-world, messy datasets at scale
- Apply product thinking to transactional data
- Identify behavioral patterns and engagement drivers
- Translate data insights into actionable business strategies

---

## Project Walkthrough

[Watch Dashboard Demo](https://youtu.be/sUwxbkWZmfw?si=tCHEo4tr2eJdBxo0)

---

## Contact

- LinkedIn: [linkedin.com/in/tjumukoro95](https://www.linkedin.com/in/tjumukoro95)
- Email: terryjosephumukoro95@gmail.com
