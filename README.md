# Freddie Mac Capstone Project: Mortgage Delinquency Modeling for Florida

## Project Overview

This capstone project focuses on analyzing Freddie Mac's mortgage data to develop predictive models for mortgage delinquency in Florida. Florida's unique housing challenges, including a historically volatile market and seasonal population shifts, provide a critical backdrop for this analysis.

### Objectives:
1. Predict delinquency rates for home loans in Florida and identify key contributing factors.
2. Model the transition probabilities for delinquent loans to different payment statuses over a one-year period.
3. Provide actionable insights for Freddie Mac to enhance decision-making and minimize delinquency risks.

---

## Business Problem

Florida's housing market faces distinct challenges, such as natural disaster risks and demographic volatility. The project aims to create robust predictive models that:
- Identify key variables influencing delinquency.
- Provide data-driven insights to support Freddie Mac's mission of housing stability and affordability.

---

## Data Sources

- **Historical Loan Dataset (2000-2018):** Includes borrower and loan characteristics.
- **Performance Dataset (2000-2018):** Tracks monthly loan performance over time.
- **Cleaned Dataset:** A processed version optimized for model training and validation.

### Key Features:
- **32 Variables:** Includes Credit Score, Loan-to-Value Ratio, and Debt-to-Income Ratio.
- **Data Points:** Over 54,000 loans and 950,000 monthly payment records.

---

## Methodology

### Data Cleaning & Transformation:
1. **Standardization:** Ensured consistent formats and handled missing data.
2. **Unpivoting:** Transformed reporting periods into analyzable time series columns.
3. **Feature Engineering:** Addressed multicollinearity and removed outliers.

### Model Development:
- **Model Selection:** Chose Random Forest for its balance between accuracy and interpretability.
- **Validation:** Employed 5-fold cross-validation to minimize bias and ensure reliability.
- **Evaluation Metrics:** Focused on accuracy, recall, and feature importance.

---

## Findings & Insights

### Key Predictive Variables:
- Recent payment history is the most critical determinant of delinquency.
- Borrower credit score and original loan amount significantly influence delinquency risks.

### Notable Trends:
- **High-Risk Borrowers:** Loans with higher unpaid balances (UPB) are more likely to become delinquent.
- **Seasonality:** Delinquency risks vary by reporting period, influenced by economic and environmental factors.

---

## Recommendations

1. **Early Intervention Programs:** Offer financial counseling and repayment plans to borrowers in early stages of delinquency.
2. **Focus on Recent Payment Trends:** Utilize recent payment data for targeted decision-making.
3. **Enhance Data Integration:** Leverage additional datasets for improved predictive accuracy.
4. **Resource Allocation:** Prioritize high-risk segments for delinquency prevention and recovery efforts.

---

## Challenges & Workarounds

### Challenges:
- **Class Imbalance:** Managed unequal distributions across payment classes.
- **Data Volume:** Large datasets required optimization for processing.

### Workarounds:
- Replaced missing values using statistical imputation.
- Simplified features to maintain model stability without overfitting.

---

## Future Opportunities

- Expand predictive modeling to other states or loan products.
- Incorporate real-time analytics for dynamic delinquency management.
- Leverage insights for adjacent business areas, such as credit card or auto loans.






