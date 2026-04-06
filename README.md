# 👨🏻‍💻 Customer Behavior Data Analysis Project

This project demonstrates a complete end-to-end data analytics workflow, replicating real-world data analyst responsibilities—from raw data processing to generating actionable business insights.

The objective is to analyze customer purchasing behavior and uncover patterns that can drive strategic business decisions.

---

## 📌 Project Overview

This project focuses on understanding customer behavior using transactional data (3,900 purchases, 18 features).

The analysis answers key business questions such as:

- Who are the highest-value customers?  
- What factors influence spending behavior?  
- Which products and categories perform best?  
- How do discounts and subscriptions impact revenue?  

---

## ⚙️ Tech Stack

- Python (Pandas, NumPy, Matplotlib)  
- PostgreSQL  
- Power BI  

---

## 🔄 Project Workflow

### 1️⃣ Data Preparation & EDA (Python)
- Loaded and explored dataset  
- Handled missing values (ratings imputed)  
- Standardized column names  
- Created new features:
  - age_group  
  - purchase_frequency_days  

---

### 2️⃣ Data Storage & Analysis (SQL)
- Stored cleaned data in PostgreSQL  
- Wrote SQL queries to:
  - Segment customers  
  - Analyze revenue trends  
  - Evaluate purchase behavior  

📁 Queries available in:  
`queries/queries.sql`

---

### 3️⃣ Data Visualization (Power BI)
- Built an interactive dashboard with filters for:
  - Gender  
  - Subscription  
  - Product Category  
  - Shipping Type  

📁 Dashboard file:  
`powerbi/dashboard.pbix`

---

### 4️⃣ Reporting & Presentation
- Created a structured report  
- Designed a presentation with insights and recommendations  

---

## 📊 Key Insights

### 💰 Revenue & Spending Behavior
- Male customers generate nearly 2× more revenue  
- Young Adults are the highest revenue-generating group  
- Express shipping users spend more ($60.48 vs. $58.46)  
- Discount users still show above-average spending  

---

## 📸 Dashboard Preview

<img width="1184" height="709" alt="Screenshot 2026-04-06 113235" src="https://github.com/user-attachments/assets/9b827d62-e30d-4937-8a51-c948c27d01d6" />

---


## 🛠️ How to Run

```bash
git clone https://github.com/your-username/customer-behavior-analysis.git
cd customer-behavior-analysis

##👨‍💻 About Me

Hi, I’m Kartikeya Pandey — a Data Analyst and Developer passionate about transforming data into actionable insights.

