# Telco Customer Churn Data Analytics & Machine Learning Project

## Overview
This project showcases my **data analytics and machine learning skills** using the Telco Customer Churn dataset. The goal is to analyze customer behavior, identify drivers of churn, and build predictive models to forecast at-risk customers. The project demonstrates practical data analysis, visualization, and predictive modeling skills, providing actionable insights for retention strategies.

---

## Skills Demonstrated
Across this project, I demonstrate proficiency in:

- Data wrangling and cleaning with **pandas**
- Exploratory Data Analysis (EDA) using **matplotlib** and **seaborn**
- Handling missing values, mismatched data types, and duplicates
- Numerical and categorical data visualization (histograms, box plots, bar charts, heatmaps)
- Correlation analysis and understanding feature relationships
- Customer churn analysis by behavioral and demographic factors
- Building and evaluating **machine learning models** (Logistic Regression, Random Forest)
- Handling class imbalance with class weighting
- Evaluating model performance using **precision, recall, F1-score, and ROC-AUC**
- Translating analytics into **business insights and actionable recommendations**

---

## Dataset
The project uses the **Telco Customer Churn dataset**, which contains customer-level information for a telecommunications company. Key features include:

- **Customer demographics:** gender, age, partner/dependent status, senior citizen  
- **Account information:** tenure, contract type, payment method  
- **Service subscriptions:** internet service type, add-ons, monthly and total charges  
- **Target variable:** churn (Yes/No)

This dataset is widely used for customer analytics and churn prediction exercises.

---

## Project Structure
- `telco_customer_churn.csv` – Raw dataset
- `telco_churn_analysis.ipynb` – Full analysis and modeling workflow with clear sections and comments  
- `README.md` – Explains the project, dataset, insights, and recommendations  

---

## Business Questions & Insights

1. **What are the general patterns in customer tenure, monthly, and total charges?**  
   *Insight:* Many customers are early in their tenure, with revenue concentrated across multiple pricing tiers, highlighting potential segmentation opportunities.

2. **How do contract type, payment method, and internet service vary among customers?**  
   *Insight:* Most customers are on month-to-month contracts with fiber optic service, suggesting retention is a key risk for high-value customers.

3. **How do demographic factors like gender, partner status, and dependents relate to churn?**  
   *Insight:* Customers with partners or dependents are generally more loyal, indicating household stability contributes to retention.

4. **Which factors are associated with higher churn risk?**  
   *Insight:* Short-term contracts, early tenure, and fiber optic service correlate with higher churn, while household factors support loyalty.

5. **Can we predict at-risk customers using machine learning?**  
   *Insight:* Logistic Regression achieves **ROC-AUC = 0.86** and **recall for churn = 0.83**, effectively identifying customers likely to leave, allowing targeted retention campaigns.

---

## Why This Project Matters
This project demonstrates not only technical data analytics and machine learning skills, but also:

- The ability to ask and answer meaningful business questions  
- Translating raw data into actionable insights for retention strategy  
- Structuring clean, readable, and professional Python code  
- Applying predictive modeling to real-world business problems  
- Analytical thinking aligned with practical data analyst responsibilities
