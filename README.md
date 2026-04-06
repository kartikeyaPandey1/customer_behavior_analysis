👨🏻‍💻 Customer Behavior Data Analysis Project

This project demonstrates a complete end-to-end data analytics workflow, replicating real-world data analyst responsibilities—from raw data processing to generating actionable business insights.

The objective is to analyze customer purchasing behavior and uncover patterns that can drive strategic business decisions.

📌 Project Overview

This project focuses on understanding customer behavior using transactional data (3,900 purchases, 18 features).

The analysis answers key business questions such as:

Who are the highest-value customers?
What factors influence spending behavior?
Which products and categories perform best?
How do discounts and subscriptions impact revenue?
⚙️ Tech Stack
Python (Pandas, NumPy, Matplotlib) – Data cleaning & analysis
PostgreSQL – Data storage & querying
Power BI – Interactive dashboard & visualization
🔄 Project Workflow
1️⃣ Data Preparation & EDA (Python)
Loaded and explored dataset
Handled missing values (ratings imputed)
Standardized column names
Created new features:
age_group
purchase_frequency_days
2️⃣ Data Storage & Analysis (SQL)
Stored cleaned data in PostgreSQL
Wrote SQL queries to:
Segment customers
Analyze revenue trends
Evaluate purchase behavior

📁 Queries available in:

sql/queries.sql
3️⃣ Data Visualization (Power BI)
Built an interactive dashboard with filters for:
Gender
Subscription
Product Category
Shipping Type

📁 Dashboard file:

powerbi/dashboard.pbix
4️⃣ Reporting & Presentation
Created a structured report
Designed a presentation summarizing:
Key insights
Business recommendations
📊 Key Insights
💰 Revenue & Spending Behavior
Male customers generate nearly 2× more revenue than female customers
Young Adults are the highest revenue-generating segment
Express shipping users spend more ($60.48 vs. $58.46)
Discount users still show above-average spending, indicating effective promotional impact
👥 Customer Segmentation
79.9% of customers are loyal, showing strong retention
Only 2.13% are new customers, indicating low acquisition
Non-subscribers dominate even among repeat buyers
💳 Subscription Insights
Subscribers have higher average value, but
73% of total revenue comes from non-subscribers
→ Strong opportunity to increase revenue via subscription conversion
🛍️ Product Insights
Top-rated products: Gloves, Sandals, Boots
These products can be leveraged for marketing campaigns
🧾 Discount Behavior
Products like Hats, Sneakers, Coats rely heavily on discounts (~50%)
Indicates dependency on promotions → possible margin risk
📦 Category Performance
Clothing and Accessories drive the highest sales volume
Footwear and outerwear show stable but slightly lower performance
🧠 Business Recommendations
Increase Customer Acquisition
Focus on marketing strategies to grow the small new-customer segment
Boost Subscription Adoption
Convert loyal customers into subscribers for higher lifetime value
Optimize Discount Strategy
Reduce over-reliance on discounts to protect profit margins
Target High-Value Segments
Focus on young adults and express-shipping users
Promote Top Products
Highlight high-rated and best-selling items in campaigns
📸 Dashboard Preview
<img width="1184" height="709" alt="Screenshot 2026-04-06 113235" src="https://github.com/user-attachments/assets/9bfe69a4-6416-48ca-adbc-505cbaba4b1c" />

🛠️ How to Run This Project
git clone https://github.com/your-username/customer-behavior-analysis.git
cd customer-behavior-analysis
Steps:
Open the Jupyter Notebook in notebooks/
Run data cleaning and preprocessing
Load data into PostgreSQL
Execute queries from sql/queries.sql
Open Power BI dashboard
👨‍💻 About Me

Hi, I’m Kartikeya Pandey — a Data Analyst and Developer passionate about transforming data into actionable insights and building impactful solutions.

⭐ Final Note

This project demonstrates an end-to-end analytics pipeline, combining data engineering, analysis, and visualization to solve real-world business problems.
