# Customer Churn Analysis Dashboard

## 📊 Project Overview

This project is a **Customer Churn Analysis Dashboard** designed to visualize and analyze the key factors contributing to customer attrition.

The primary goal is to provide a clear, data-driven understanding of our customer base and identify high-risk segments to inform targeted retention strategies.

### Key Metrics

* [cite_start]**Total Customers:** 7,043 [cite: 1, 2]
* [cite_start]**Distinct Customers:** 7,043 [cite: 4, 5]
* [cite_start]**Churned Customers:** 1,869 [cite: 6]
* [cite_start]**Overall Churn Rate:** 26.54% [cite: 7]

## 🔎 Analysis Highlights

The dashboard explores customer churn across various demographic, relationship, tenure, and service usage dimensions.

### 1. Demographic & Relationship Analysis

We analyzed the count of churn by gender and partner status.

* [cite_start]**Gender:** Churn is relatively evenly distributed between Male and Female customers[cite: 8].
* **Partner Status Impact (Sum of Churn Flag):**
    * [cite_start]**Female without Partner (Female-0):** Accounts for 33.17% (620) of all churned customers[cite: 22, 23, 24].
    * [cite_start]**Male without Partner (Male-0):** Accounts for 31.03% (580) of all churned customers[cite: 29].
    * [cite_start]**Male with Partner (Male-1):** Accounts for 18% (350) of all churned customers[cite: 28].
    * [cite_start]**Female with Partner (Female-1):** Accounts for 17.07% (319) of all churned customers[cite: 21].

### 2. Tenure Analysis

The **Count of Churn by tenure** visualization identifies the time frame during which customers are most likely to leave:
* Churn is notably high for customers in their very **first month** of service (low tenure).
* A second spike in churn occurs for customers with **high tenure** (around 70 units of time).

### 3. Contract & Payment Analysis

This section identifies which contract and payment method combinations pose the highest risk of churn:
* [cite_start]The dashboard includes a detailed breakdown of churn by **Payment Method** (e.g., Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)) and **Contract Type** (Month-to-month, One year, Two year)[cite: 31, 32, 33, 34, 35, 36, 38, 39, 44].
* **Month-to-month contracts** are generally associated with higher churn risk across most payment types.

### 4. Service and Financial Impact

* [cite_start]**Sum of Total Charges:** The total charges from customers who have **not churned (No)** is significantly higher (13.19M - 82.17%) than those who **have churned (Yes)** (2.86M - 17.83%)[cite: 60, 61, 62].
* [cite_start]The analysis also compares the **Sum of Total Services** between churned and non-churned customers[cite: 52, 53].

## 🛠️ Technologies Used

*(Note: Fill this section in with the actual tools you used, such as Python, R, Tableau, Power BI, SQL, etc.)*

* **Data Analysis:** [e.g., Python (Pandas, NumPy)]
* **Visualization/Dashboarding:** [e.g., Tableau / Power BI]
* **Data Source:** [e.g., CSV file / SQL Database]
* **Programming Language:** [e.g., Python / R]

## ✨ Key Takeaways & Recommendations

* **Focus on Early-Stage Retention:** High churn in the first month requires immediate attention to onboarding and initial customer experience.
* **Target Month-to-Month Contracts:** Customers on shorter contracts represent the highest flight risk and should be the focus of promotional offers or incentives to upgrade to longer-term commitments.
* **Investigate Payment Methods:** Certain payment methods (like Electronic Check) combined with high-risk contracts should be investigated further for potential friction points.

---
