# 📊 Insurance Customer Risk Profiling

## 📌 Project Overview
This project focuses on **Customer Risk Profiling** using a large **Insurance dataset**.  
The objective is to identify which customer characteristics significantly impact insurance claim risk and which factors have minimal influence.

This analysis supports **risk-based pricing, underwriting decisions, and discount strategies** for insurance companies.

---

## 🎯 Objectives
- Identify key customer factors (age, income, health, credit score) affecting claim risk
- Analyze variables that do **not** strongly impact claim risk
- Support data-driven **pricing and premium decisions**
- Improve customer segmentation for better business outcomes

---

## 📂 Dataset Information
- **Dataset Name:** Insurance Customer Data  
- **Source:** Kaggle  
- **Rows:** 800,000  
- **Columns:** 21  

The dataset includes:
- Customer demographics
- Financial indicators
- Health scores
- Vehicle information
- Claim history
- Customer tenure

---

## 🧹 Data Processing & Segmentation

### Data Cleaning
- Handled missing values (credit score, occupation)
- Identified and treated outliers (previous claims)
- Standardized formats for income, health score, and dates

### Customer Segmentation
Customers were grouped into:
- **Age Groups:** Young Adult, Early Career, Mid-Career, Senior
- **Income Levels:** Low, Lower-Middle, Middle, High
- **Credit Scores:** Poor, Fair, Good, Excellent
- **Health Scores:** Poor, Average, Good
- **Other Segments:** Smoking status, Occupation, Vehicle age, Customer tenure

---

## 📊 Exploratory Data Analysis & Insights

### Age-Based Risk
- **Mid-Career (36–50)**  
  - Largest group (264k customers)  
  - Claim risk: **44.3%** (highest volume impact)

- **Young Adults**  
  - Similar risk (44.1%) with lower volume  

**Insight:** Mid-career customers should be a primary focus for pricing strategies.

---

### Occupation
- **Unknown occupation** is the largest segment (239k) with **44.2% risk**
- Top occupations show very similar risk levels

**Insight:** Occupation is not a strong risk driver; data quality improvement is needed.

---

### Vehicle Age
- **New vehicles (0–5 years)**  
  - Largest group (237k)  
  - Claim risk: **44.4%**

- Risk variation across vehicle age groups is **less than 0.6%**

**Insight:** Vehicle age is not a meaningful pricing factor.

---

### Income Levels
- **Lower-Middle Income (15k–40k)**  
  - Largest group (302k)  
  - Lowest risk (**41.8%**)

- **High Income (80k+)**  
  - Smaller group (79k)  
  - Highest risk (**48.0%**)

**Insight:** Lower-middle income customers are ideal for retention discounts, while high-income customers may require premium loading.

---

### Credit Score
- **Poor Credit (300–550)**  
  - Largest group (285k)  
  - Risk: **42.9%**

- **Excellent Credit** customers still show **45.3% risk**

**Insight:** Credit score alone should not be relied upon for underwriting decisions.

---

### Health Score
- **Average Health (16–30)**  
  - Largest group (363k)  
  - Lowest risk (**43.9%**)

- **Good Health** shows slightly higher risk

**Insight:** Counter-intuitive behavior that requires further investigation.

---

## 🤖 Model Building & Interpretation

A classification model was developed to predict customer claim risk.

### Model Performance
- **Safe customers correctly identified:**  
  76,794 (86% accuracy)

- **High-risk customer recall:**  
  Only 22% of risky customers detected

- **False safe predictions:**  
  55,015 high-risk customers labeled as safe

**Business Risk:** Misclassification of risky customers can result in significant claim losses.

---

## ✅ Conclusion & Recommendations
- Closely monitor **Mid-Career customers**
- Avoid using **smoking status** in pricing
- Offer discounts to **Lower-Middle income** customers
- Avoid loyalty-based discounts
- Apply premium loading for **High-Income customers**
- Do not rely solely on **credit score** for risk assessment

---

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Data Visualization Libraries
- Jupyter Notebook
- Exploratory Data Analysis (EDA)
- Classification Modeling

---

## 📌 Business Impact
This project demonstrates how data-driven customer risk profiling can:
- Reduce claim losses
- Improve pricing strategies
- Enhance underwriting accuracy
- Support strategic insurance decisions

---

## 📬 Contact
For collaboration, freelance work, or data analytics projects, feel free to connect.

