# Product Analytics: Feature Adoption & KPI Dashboard

## Overview
This project analyzes product feature adoption, customer behavior, and revenue patterns to support data-driven Go-to-Market (GTM) decisions.

The goal is to identify:
- Which features drive engagement
- How adoption varies across regions
- Which customer segments generate the most value

---

## Business Problem
A SaaS company offers multiple product features but lacks visibility into:

- Feature-level performance
- Regional differences in usage
- High-value customer segments

Without this insight, sales and product teams cannot effectively prioritize growth efforts.

---

## Data
The dataset includes:

- **customers**: region, company size, industry  
- **features**: product feature definitions  
- **usage_events**: feature usage behavior  
- **revenue**: revenue generated per customer  

---

## KPI Framework

- **Feature Adoption Rate**  
  Percentage of customers using a feature  

- **Usage Intensity**  
  Total usage per customer  

- **Revenue per Customer**  
  Total revenue contribution  

- **Segment Performance**  
  Combined view of usage and revenue  

---

## Analysis

### 1. Feature Adoption
- All features show high adoption (~85%+)
- Indicates strong baseline engagement

### 2. Regional Differences
- Adoption varies by region
- Suggests region-specific user behavior patterns

### 3. Segment Performance
- High-value segments identified by high usage + revenue
- Some segments show high usage but lower monetization

---

## Key Insights

- Adoption alone is not sufficient to evaluate product performance  
- Regional differences highlight opportunities for localized GTM strategies  
- Customer segmentation enables targeted sales prioritization  

---

## Business Recommendations

- Focus sales efforts on high-value segments  
- Improve monetization strategies for high-usage, low-revenue segments  
- Tailor GTM strategy based on regional usage patterns  

---

## Tools
- Python (pandas)
- SQL (analysis logic)
- Power BI / Tableau (dashboard)

---

## Project Structure
