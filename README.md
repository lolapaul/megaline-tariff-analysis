# 📞 Megaline Tariff Analysis

Revenue and user behavior analysis for two prepaid telecom plans — Surf and Ultimate — offered by Megaline. This project includes data cleaning, exploratory data analysis, and statistical testing to determine which plan generates more average monthly revenue.

---

## 📌 Objective

The commercial department of Megaline wants to evaluate which prepaid plan — Surf or Ultimate — is more profitable. This project analyzes user activity (calls, texts, internet usage) and monthly revenue per user to support business decisions.

---

## 📊 Dataset Description

The dataset includes five tables:

1. **users.csv** – User data: age, city, signup date, and chosen plan  
2. **calls.csv** – Call records per user and date  
3. **messages.csv** – SMS activity per user and date  
4. **internet.csv** – Web sessions per user, with data used in MB  
5. **plans.csv** – Details of each plan's cost and included services

Key characteristics:
- All web data usage is rounded up to the nearest GB monthly.
- All calls are rounded up to the next minute individually.

---

## 🔍 Project Workflow

1. **Data Preparation**
   - Convert types
   - Handle missing values and outliers
   - Aggregate monthly usage and revenue per user

2. **Exploratory Data Analysis**
   - Compare usage patterns (calls, SMS, data)
   - Revenue distributions per plan
   - Summary statistics (mean, variance, std)

3. **Hypothesis Testing**
   - Compare average monthly revenue for Surf vs. Ultimate plans
   - Analyze differences in revenue between NYC/NJ and other regions

---

## 📊 Key Questions Answered

- Which plan has higher average monthly revenue?
- How do user behaviors vary between plans?
- Are users in New York/New Jersey statistically different in terms of revenue?
- How effective are the free allowances in each plan?

---

## 📁 Project Structure

```
megaline-tariff-analysis/
│
├── Proyecto_final_sprint4.ipynb
├── megaline_calls.csv
├── megaline_internet.csv
├── megaline_messages.csv
├── megaline_plans.csv
├── megaline_users.csv
├── requirements.txt
└── README.md

```

---

## 🛠️ Tools & Libraries Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- Jupyter Notebook

---

## ✅ Status

✔️ Project completed as part of the **TripleTen Bootcamp** – Sprint: *Revenue Analysis & Statistical Inference*

---

## 📌 Author

David Villanueva  
[LinkedIn](https://www.linkedin.com/in/david-villanueva-59659727)  
[GitHub](https://github.com/lolapaul)
