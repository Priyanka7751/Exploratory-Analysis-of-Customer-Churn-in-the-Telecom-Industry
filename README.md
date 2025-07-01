# Telecom Customer Churn Analysis 📉

This project focuses on understanding and analyzing customer churn in a telecom Company using real-world data. The goal is to identify key factors that contribute to customer churn and provide actionable insights to reduce churn Rates and improve customer retention.

## 📌 Project Overview

Customer churn is a major problem in the telecom industry. Understanding why customers leave helps businesses take strategic actions to improve customer satisfaction and reduce losses. This project applies data analysis techniques using Python to uncover patterns and trends in customer behavior.

## ❓ Problem Statement

> Identify the main factors leading to customer churn in a telecom company and provide insights that could help the company retain its customers.

---

## 📊 Dataset

- **Total Records**: ~7,000 customer records
- **Features**:
  - Customer demographics (gender, age, etc.)
  - Account information (tenure, contract type, billing)
  - Services used (Internet, Phone, Online Security, etc.)
  - Churn status (Yes/No)

---

## 🛠️ Tools & Technologies Used

- **Languages**: Python
- **Libraries**:
  - `NumPy`, `Pandas` – Data manipulation
  - `Matplotlib`, `Seaborn` – Data visualization
- **IDE**: Jupyter Notebook / VS Code

---

## 📈 Exploratory Data Analysis (EDA)

The following steps were performed:

1. **Data Cleaning**
   - Checked for null values
   - Converted column types
   - Removed duplicates

2. **Data Visualization**
   - Univariate and bivariate analysis
   - Distribution of churn across various features
  
---

## 🔍 Key Insights & Findings

### 📄 Contract Type and Churn
- Customers on **month-to-month contracts** have the highest churn rate at **42%**.
- In contrast, **one-year** and **two-year contracts** show churn rates of **11%** and **3%**, respectively.
- 🔑 **Insight:** Longer contract periods help improve customer retention.

### 💳 Payment Methods and Churn
- Customers using **electronic checks** exhibit the highest churn rate at **45%**.
- Those paying via **credit cards, bank transfers, or mailed checks** have much lower churn rates, averaging around **15–18%**.
- 🔑 **Insight:** Secure and stable payment methods are linked to reduced churn.

### ⏳ Churn by Tenure
- Customers with **less than 1 year** of tenure churn at **50%**.
- Those with **1–3 years** churn at **35%**, and those with **more than 3 years** churn at just **15%**.
- 🔑 **Insight:** Engaging customers early in their journey is crucial for long-term retention.

### 🌐 Churn by Internet Service Type
- **Fiber Optic** users churn at **30%**, whereas **DSL** users churn at **20%**.
- 🔑 **Insight:** Dissatisfaction with fiber optic service speed or reliability may drive higher churn.

### 👴 Senior Citizens and Churn
- **Senior citizens (65+)** have a churn rate of **41%**, compared to **26%** for non-seniors.
- 🔑 **Insight:** Tailored retention programs for senior users may help reduce churn in this demographic.

---

## ✅ Recommendations

- **Promote Long-Term Contracts**  
  Offer incentives for customers to commit to longer contracts to reduce churn.

- **Address Payment Method Concerns**  
  Implement campaigns encouraging customers to switch from electronic checks to more reliable and secure payment methods.

- **Customer Engagement in Early Tenure**  
  Focus on improving the customer experience within the first year, as churn is highest in this period.

- **Special Senior Citizen Retention Programs**  
  Create personalized offers or assistance programs to retain the senior demographic.

