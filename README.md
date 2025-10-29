# EDA on Retail CRM Data

## Executive Summary
Using Python, SQL, and Power BI, I analyzed customer purchase and demographic data to uncover key patterns in shopping behavior across product categories and subscription types. The analysis revealed that loyal and express-shipping customers contribute the highest revenue share, while discount-driven purchases have an impact on overall margins.  
To boost profitability and retention, I recommend:

- Introducing loyalty and referral programs for repeat buyers  
- Optimizing discount policies for high-performing products  
- Targeted marketing toward top-spending age groups  

---

## Business Problem
The retail business's high volume of transactional data is underutilized, failing to convert repeat, high-value purchasers into loyal, long-term subscribers, thus suppressing Customer Lifetime Value (CLV).  
This strategic gap is driven by two key dilemmas:

- **Discount Dilemma:** Current generic promotions risk eroding profit margins rather than driving genuinely new revenue.  
- **Loyalty Paradox:** Despite purchasing repeat buyers (>5 purchases) are not proportionally converting to subscriptions (2,518 non-subscribers vs. 958 subscribers).

---

## Methodology
**Python (Pandas):** Handled ETL, cleaning, and feature engineering to derive the age_group for segmentation.  
**SQL (PostgreSQL/MySQL):** Executed advanced strategic aggregation to calculate Discount Effectiveness and analyze the Loyalty Paradox.  
**Power BI:** Created the interactive dashboard for stakeholder visualization of key insights like Revenue by Age-Group.

---

## Skills
- **SQL:** CTEs, Joins, CASE, Aggregate Functions, Data Modeling  
- **Python:** ETL, Pandas, Data Cleaning (imputation), Feature Engineering (creating age_group), EDA (df.info(), describe()), Numpy (binning)  
- **Power BI:** Interactive Dashboard Design, Data Visualization, ETL, BI Reporting  
- **General:** Customer Segmentation, Data Storytelling  

---

## Key Behavioral Insights
- **Loyalty Chasm:** A staggering 72.4% of high-volume repeat buyers are not subscribers (2,518 non-subscribers), marking a vast, dormant opportunity for recurring revenue.  
- **Revenue Disparity:** The Male customer segment drives twice the revenue of the Female segment ($157.9K vs. $75.2K), signaling a critical gap in market targeting.  
- **Margin Erosion Risk:** Items like Hats and Sneakers are unnaturally dependent on discounts, prompting an urgent review of their pricing strategy to safeguard profitability.  
- **Highest Yield Segment:** While Young Adults generate the largest revenue chunk ($62.1K), their high discount sensitivity mandates careful promotional planning.

---

## Actionable Business Recommendations
- **Close the Loyalty Gap:** Launch a targeted Customer Loyalty Program focused on exclusive, non-monetary rewards for current repeat buyers, thereby moving them directly into the high-CLV subscriber pool.  
- **Refocus Marketing:** Immediately reallocate ad spend to aggressively engage the top-performing Young Adult and Male demographics with compelling subscription value propositions.  
- **Leverage Behavior:** Prioritize promoting subscription benefits to frequent 'Express Shipping' users, recognizing their demonstrated willingness to pay for premium service.

---

## Next Steps
- Develop Predictive CLV Model (Python)  
- Conduct Micro-Churn Analysis on Non-Subscribers  
- Launch & Monitor A/B Tests for Discount Policy

