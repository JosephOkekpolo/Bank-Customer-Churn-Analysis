# Bank Customer Churn Analysis

### Project Objective 
---
This report provides a detailed analysis of customer churn patterns using internal bank data. 
The aim is to identify churn drivers across multiple customer segments - including product usage, age, gender, geography, and account balance - and to develop actionable strategies to improve customer retention.

### Dataset Overview and Preparation
---
As part of the data preparation process, duplicates were removed using Power Query to maintain the integrity of the analysis.
Blank values were treated, corrected spelling errors and data types errors, A new column was added the breakdown customers ages into age brackets to identify trends across life stages.
All these where done also with Power Query and Excel(Pivot table and Data Visualization).

The dataset consists of 10,000 customer records with the following key attributes:
- Exited (1 = churned, 0 = stayed)
- NumOfProducts (1-4)
- Gender (Male/Female)
- Age (18-92)
- Geography (France, Germany, Spain)
- Balance, Tenure, and other relevant financial metrics

![Annotation 2025-06-26 070653](https://github.com/user-attachments/assets/c9affc8d-7c54-426b-b25b-dcaa8ef37aec)



### Exploratory Data Analysis
---
EDA involves exploring the bank customer churn data to answer key questions, such as:

-	What insights can you uncover from the data?
-	How do churn trends vary by geography, age group, gender, account balance, or product usage?
-	Are there patterns that might predict which customers are most likely to churn?

### Key Insights/Findings
---
1. Churn customers by Age Group
- Customers aged 45-54 (48.1%) and 55-64 (49.8%) show the highest churn rates.
- These age brackets represent a high-risk segment, possibly due to:
- Retirement transitions
- Lower digital adoption
- Feeling underserved by modern banking
2. Churn customers by Gender
- 25.1% of female customers churned vs. 16.5% of males — a 9% gap.
- Possible reasons:
- Limited personalization in financial advice or support
- Products not tailored to women's financial goals
- Greater sensitivity to service quality or life-stage transitions (e.g., maternity)
3. Churn customers by Account Balance
- Churned customers tend to have lower balances.
- Indicates lower engagement, possibly feeling undervalued or ignored
- Customers with higher balances are more likely to stay, suggesting value perception plays a key role
4. Churn customers by Product Usage
- Customers with 2 products have the lowest churn (7.6%) — a likely engagement sweet spot
- Those with 3 or 4 products exhibit extremely high churn (82.7% and 100%)


![new](https://github.com/user-attachments/assets/a79c8323-b39d-4c2b-929c-d17ffb2f3730)


### Recommendations
---
1. For High-Risk Age Groups (45-64)
- Targeted Retention Campaigns
- Personalized check-ins, loyalty programs, and birthday perks
- Dedicated relationship managers
- Retirement-Focused Products
- Pension savings plans, simplified investment options, estate planning etc.

2. For Gender
-Sensitive Engagement
- Personalized Advisory Services
- Improve Customer Experience
- Segmented Marketing
3. Based on Account Balance
- Engagement Incentives
- Proactive Communication
 
4. Based on Product Usage
- Investigate High Product Holders (3-4)
- Protect 2-Product Customers
- Engage 1-Product Customers
- Rethink Cross-Selling Strategy

### Conclusions
---
This analysis reveals that customer churn is influenced by a combination of demographic, behavioral, and financial factors.
Age, gender, product load, and balance levels are all significant indicators of churn risk. To reduce churn and improve retention, the bank must:
- Deliver personalized services across all customer types
- Address churn among older and female customers
- Promote relevant and balanced product bundling
- Support low-balance and disengaged customers with targeted communication
By acting on these insights, the bank can improve customer loyalty, reduce attrition, and enhance overall customer lifetime value.
