# 📊 Project: Customer Churn – Telecom X

This project was developed as part of a data analysis challenge for **Telecom X**.  
The main objective is to investigate the factors that influence service cancellations (**churn**) by customers, providing a solid, cleaned data foundation and **strategic insights** for the Data Science team.

---

## 📋 Challenge Description

Telecom X faces a high customer churn rate.  
The challenge consists of:

- Collecting historical data  
- Cleaning the data  
- Analyzing the data  

in order to extract **valuable patterns** that help to understand:

- Why customers are leaving  
- How to reduce this loss  

before moving forward to **predictive models**.

---

## 🛠️ Technologies and Tools

The project was developed in **Python v3.13.9**, using:

- **Pandas**  
  - Data manipulation, cleaning, and transformation

- **JSON Normalize**  
  - Handling the nested structure of the original data

- **Microsoft VS Code (kernell engine)**  
  - Development environment used to run the notebook

---

## 🚀 Project Steps

### 1. Data Extraction

- Data extracted from an **API** in **JSON** format  
- Initial structure with nested data about:
  - Customer profile  
  - Phone services  
  - Internet services  
  - Account details

---

### 2. Transformation and Cleaning

The raw data was prepared for analysis through:

- **Normalization**  
  - Expanding JSON fields into a tabular format (DataFrame)

- **Attribute Selection**  
  - Critical variables:
    - Churn  
    - Gender  
    - Contract  
    - Tenure  
    - Dependents  
    - Total charges

- **Feature Engineering**  
  - Creation of the `daily_bill` metric (daily cost)  
  - Goal: understand the impact of price on churn

- **Type Casting**  
  - Converting categorical variables into numeric values  
  - Example:
    - 1 for `"Yes"`  
    - 0 for `"No"`

---

### 3. Exploratory Analysis and Insights

**Main findings:**

- **Short-Term Contracts**  
  - Customers with *Month-to-month* contracts are more likely to churn

- **Payment Methods**  
  - Use of *Electronic Check* is correlated with higher churn rates

- **Tenure**  
  - Customers in their first 6 months are the most likely to leave

- **Age Profile**  
  - Senior customers (*Senior Citizens*) show specific behavior patterns  
  - They deserve special attention in retention campaigns

---

## 🧩 Strategic Recommendations

Based on the analyzed data:

- **Loyalty Incentives**  
  - Create promotions to migrate customers:
    - From monthly plans  
    - To annual or biennial plans

- **Onboarding Focus**  
  - Strengthen *Customer Success* efforts  
  - Especially during the first 6 months

- **Payment Review**  
  - Investigate dissatisfaction with *Electronic Check*  
  - Encourage automatic debit

- **Segmented Packages**  
  - Develop offers tailored to senior customers

---

## 📌 Next Steps

- Build churn prediction models  
- Validate hypotheses with statistical tests  
- Implement retention metrics

---

## 📎 Author

Lucas Aoki  
Project developed for educational and demonstration purposes.
