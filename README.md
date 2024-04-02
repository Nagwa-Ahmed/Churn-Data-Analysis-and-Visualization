# Churn Data Analysis and Visualization

This repository contains a data analysis project focusing on understanding churn behavior and identifying key characteristics of churners using the Telco Customer Churn dataset available on Kaggle ([Dataset Link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)). The analysis is conducted using Python, utilizing popular libraries such as pandas, numpy, matplotlib, and seaborn.

## Project Overview

### Data Preprocessing
- Removed duplicates, checked for missing values, and assessed data types.
- Conducted descriptive statistics to gain insights into the dataset.

### Main Analysis
- Visualized data to identify trends and patterns.
- Conducted statistical tests (e.g., t-test, z-test, chi-square test) to validate insights derived from visualizations.

## Key Insights

- **Gender and Phone Service:** Found no significant impact on churn status.
- **Feature Utilization:** Churners tend to avoid utilizing specific features like online security, backup, and tech support.
- **Impact of Relationships:** Customers with partners and dependents are less likely to churn.
- **Monthly Charges:** Churners typically have higher monthly charges compared to non-churners.

## Conclusions

1. **Marketing Campaign:** Recommended launching a campaign to increase awareness of underutilized services such as online security.
2. **Customer Loyalty:** Suggested focusing on retaining long-term customers through tailored services.
3. **Targeting Older Population:** Noted that most churners are senior citizens, suggesting further investigation into their specific concerns.

## Actionable Suggestions

- Implement targeted marketing strategies to promote underutilized services.
- Develop loyalty programs or incentives for long-term customers.
- Investigate and address specific concerns of older customers to improve retention and satisfaction.

## Note
The analysis was conducted twice, once with imputation of "not applicable" values and once by deleting them. Both approaches yielded similar results, ensuring the robustness of the findings.


