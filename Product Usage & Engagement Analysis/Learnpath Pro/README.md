# LearnPath Pro — Product Usage & Engagement Analysis

## Overview

Analyzed user engagement and product usage patterns on LearnPath Pro, an e-learning SaaS platform, across an 18-month period from January 2023 to June 2024.

This project simulates a real-world product analytics scenario where behavioral and subscription data across 2,000 users is transformed into structured insights to support product, growth, and retention decisions.

---

## Key Impact

- Analysed 2,000 users across three subscription tiers (Free, Pro, Enterprise)
- Identified churn drivers: Free tier churn rate of 35% vs. 5% for Enterprise
- Quantified session behavior differences across plan types — Enterprise users average 38 min/session vs. 12 min for Free users
- Revealed a 19.9% course completion rate, identifying a critical engagement gap
- Surfaced geographic concentration: Nigeria, USA, and UK lead user acquisition
- Uncovered Live Sessions as the most underutilised premium feature despite its high potential value

---

## Business Context

LearnPath Pro is a fictional e-learning SaaS platform offering three subscription tiers — Free, Pro, and Enterprise — to learners across multiple regions.

The platform aims to understand:

- How users engage with its core features
- Which subscription tiers drive the most value
- Where users drop off in their learning journey
- How to reduce churn and accelerate Free-to-Paid upgrades

---

## Problem Statement

LearnPath Pro lacks clear visibility into what drives user engagement and what causes churn.

Key questions include:

- Which plan types generate the most sessions and deepest engagement?
- What features are users actually using — and which are being ignored?
- Where are users dropping off before completing courses?
- Which regions and demographics represent the biggest growth opportunities?
- How can the platform convert Free users to paid plans more effectively?

---

## Role

**Product Data Analyst**

- Cleaned and validated user, session, and event-level data
- Defined and calculated engagement KPIs across subscription tiers
- Performed churn, retention, and feature adoption analysis
- Delivered insights and recommendations to inform product and growth strategy

---

## Dataset Overview

| Metric | Value |
| --- | --- |
| Total Users | 2,000 |
| Analysis Period | January 2023 – June 2024 (18 months) |
| Subscription Tiers | Free, Pro, Enterprise |
| Churn Rate | 26.3% |
| Retention Rate | 73.7% |
| Avg. Session Duration | 25.38 minutes |
| Course Completion Rate | 19.9% |
| Free-to-Paid Upgrade Rate | 11.4% |

---

## Data Cleaning & Preparation

To ensure accuracy and analytical reliability:

- Handled missing values (~2–3%) in age_group, gender, duration_min, and plan_at_event fields — treated as nulls and excluded from relevant calculations
- Removed duplicate rows (~1%) identified across the Sessions and Events tables
- Flagged and reviewed 15 session records with invalid duration values (zero, negative, or implausibly high) — retained given negligible volume (15 of 94,000+ records)
- Standardised approximately 20 signup_date records stored in an inconsistent DD/MM/YYYY format, converting them to null during cleaning

---

## Product Analytics Insights

### 1. User Growth & Activity

Monthly Active Users showed consistent growth across the 18-month period, reflecting healthy organic acquisition. Organic Search (30%) and Paid Ads (20%) together account for half of all new signups, indicating that top-of-funnel efforts are working effectively.

> **Note on MAU Methodology:** The current MAU measure reflects cumulative distinct users across the full dataset. For a more precise DAU/MAU ratio analysis, session data should be filtered to individual calendar months in future iterations.

---

### 2. Session Behavior & Engagement

**Pro users drive the highest session volume; Enterprise users engage most deeply.**

| Plan | Total Sessions | Avg. Session Duration |
| --- | --- | --- |
| Pro | ~45,000 | ~28 minutes |
| Free | ~27,000 | ~12 minutes |
| Enterprise | ~21,000 | ~38 minutes |

While Pro users are the most frequent, Enterprise users derive more concentrated value per session — suggesting depth of engagement scales with plan tier.

**Desktop dominates access (50%), followed by mobile (38%) and tablet (12%).** The low tablet share is notable given that tablets are well-suited for consuming video and course content, pointing to a potential gap in the platform's tablet experience.

---

### 3. Feature Adoption

**Video Lessons and Quizzes are the platform's core engagement drivers**, followed by the Progress Tracker. These three features represent the core learning loop of the platform.

**Live Sessions — a premium feature — ranked last in usage** despite being available to Pro and Enterprise users. This underutilisation represents both a concern and a significant upsell opportunity.

Certificate Download and Peer Review also see limited usage. Given that certifications are often a primary motivation for e-learning users, the low download rate likely correlates directly with the 19.9% course completion rate.

---

### 4. Churn & Retention

A clear churn gradient exists across subscription tiers:

| Plan | Churn Rate |
| --- | --- |
| Free | ~35% |
| Pro | ~15% |
| Enterprise | ~5% |

The overall 26.3% churn rate is primarily driven by the Free tier, which represents 60% of the user base. Paid users show significantly stronger retention, consistent with their deeper commitment to the platform.

---

### 5. User Demographics & Geography

**Nigeria leads user acquisition (~393 users)**, followed by the United States (~315) and the United Kingdom (~267). Kenya, Ghana, and South Africa also feature prominently — reinforcing a strong African market opportunity and alignment with an Africa-focused growth positioning.

**Users aged 25–34 represent the largest cohort (~650 users)**, with 18–24 close behind (~516). Together these groups account for over 58% of the user base, indicating that LearnPath Pro's core audience is young professionals and recent graduates seeking to upskill or advance their careers.

---

## Dashboard

### Overview

<!-- Replace with your screenshot: drag the image into the GitHub file upload -->
![Overview Page](https://github.com/Jaytee4000/data-analytics-portfolio/blob/ed8f8f3d153afee8a3e808967a4cd047c0137aae/Product%20Usage%20%26%20Engagement%20Analysis/Learnpath%20Pro/Images/Overview.png)

**Key Insight:**
Retention is strong among paid users, but the Free tier's 35% churn rate and 19.9% course completion rate signal significant early-lifecycle engagement gaps.

---

### Session & Engagement Analysis

<!-- Replace with your screenshot -->
![Session Analysis](https://github.com/Jaytee4000/data-analytics-portfolio/blob/ed8f8f3d153afee8a3e808967a4cd047c0137aae/Product%20Usage%20%26%20Engagement%20Analysis/Learnpath%20Pro/Images/Engagement_Analysis.png)

**Key Insight:**
Enterprise users engage most deeply per session despite lower total volume. Pro users drive the bulk of platform activity, while Free users show shallow, short-form engagement patterns.

---

### Feature Adoption

<!-- Replace with your screenshot -->
![Feature Adoption](https://github.com/Jaytee4000/data-analytics-portfolio/blob/ed8f8f3d153afee8a3e808967a4cd047c0137aae/Product%20Usage%20%26%20Engagement%20Analysis/Learnpath%20Pro/Images/Feature_Analysis.png)

**Key Insight:**
The core learning loop (Video Lessons, Quizzes, Progress Tracker) carries engagement, while premium features like Live Sessions remain significantly underused — representing the clearest upsell opportunity on the platform.

---

### Geographic & Demographic Breakdown

<!-- Replace with your screenshot -->
![Geographic Analysis](https://github.com/Jaytee4000/data-analytics-portfolio/blob/ed8f8f3d153afee8a3e808967a4cd047c0137aae/Product%20Usage%20%26%20Engagement%20Analysis/Learnpath%20Pro/Images/User%20Segments.png)

**Key Insight:**
Nigeria, the USA, and the UK lead acquisition. The concentration of users in African markets and the 25–34 age group presents a clear strategic opportunity for localised content and career-focused course offerings.

---

## Project Walkthrough

<!-- Replace with your screen recorded video link once uploaded -->
[▶ Watch Dashboard Walkthrough](https://youtu.be/your-video-link-here)

---

## Business Recommendations

**1. Address the Course Completion Gap**
Only 1 in 5 users who start a course complete it. Introduce progress nudges, milestone notifications, and completion streaks to sustain learner momentum. Consider breaking longer courses into shorter modules to reduce abandonment.

**2. Revive Live Sessions Adoption**
Bundle Live Session access into Pro plan onboarding to create an early usage habit. Promote scheduled sessions via in-app and email campaigns, highlighting expert instructors and networking opportunities.

**3. Reduce Free Tier Churn**
Focus on a guided onboarding experience that leads new users to a Video Lesson and Quiz within the first session. Introduce a 7-day free trial of Pro features to demonstrate the depth of the paid experience and accelerate upgrade decisions.

**4. Improve the Tablet Experience**
Conduct UX testing specifically on tablet to identify friction points. Consider targeted marketing toward tablet users highlighting the visual richness of video lessons on larger screens.

**5. Leverage the African Market Advantage**
Localised content, local currency pricing, and partnerships with African institutions could deepen penetration in Nigeria, Kenya, Ghana, and South Africa — markets that already show strong organic reach.

**6. Accelerate Enterprise Upsell**
Enterprise users show the highest session depth and lowest churn. Develop a clear Pro-to-Enterprise upgrade pathway and introduce a dedicated Customer Success touchpoint to maximise retention and expand seat count within organisations.

---

## Tools & Technologies

- Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling

---

## Skills Demonstrated

- SaaS product analytics (engagement, retention, churn)
- KPI definition and calculation across subscription tiers
- Feature adoption and behavioral analysis
- Cohort and lifecycle analysis
- Geographic and demographic segmentation
- Business insight communication and stakeholder reporting

---

## Why This Project Matters

This project demonstrates the ability to:

- Apply product thinking to SaaS user behavior data
- Identify where a platform loses users and why
- Connect behavioral patterns to business outcomes (churn, revenue, growth)
- Translate data insights into clear, prioritised recommendations for product and growth teams

---

## Contact

- LinkedIn: [linkedin.com/in/tjumukoro95](https://www.linkedin.com/in/tjumukoro95)
- Email: [terryjosephumukoro95@gmail.com](mailto:terryjosephumukoro95@gmail.com)
