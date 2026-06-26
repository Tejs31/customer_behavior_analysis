# Customer_behavior_analysis
data analytics project showcasing customer behavior analysis using python, sql and power Bi

---

# 📌 Overview

This project analyzes customer shopping behavior using **Python, SQL, and Power BI** to uncover customer purchasing patterns, shopping trends, and valuable business insights.

The project follows the complete Data Analytics lifecycle, including data cleaning, exploratory data analysis (EDA), SQL-based business analysis, interactive Power BI dashboards, business reporting, and presentation preparation.

The goal is to transform raw customer shopping data into meaningful insights that help businesses improve sales, customer satisfaction, and decision-making.

---

# 🎯 Business Problem

Retail businesses collect a large amount of customer shopping data every day. However, without proper analysis, it becomes difficult to answer important business questions such as:

- Which product categories generate the highest revenue?
- Which products are purchased the most?
- How do customer demographics influence buying behavior?
- Does subscription status impact customer spending?
- Which payment and shipping methods are preferred?
- What shopping trends can help improve sales?

This project provides data-driven insights to help businesses make informed decisions.

---

# 📂 Dataset

**Dataset Name:** Customer Shopping Behavior Dataset

The dataset contains approximately **3,900 customer records** with information such as:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Season
- Payment Method
- Shipping Type
- Subscription Status
- Promo Code Used
- Previous Purchases
- Review Rating
- Purchase Frequency

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|-------|----------|
| 🐍 Python | Data Cleaning & EDA |
| 🐼 Pandas | Data Manipulation |
| 📈 NumPy | Numerical Operations |
| 📊 Matplotlib | Data Visualization |
| 🎨 Seaborn | Statistical Visualization |
| 🗄️ SQL (PostgreSQL/MySQL/SQL Server) | Business Analysis |
| 📉 Power BI | Interactive Dashboard |
| 📑 Gamma | Business Presentation |
| 📝 Microsoft Word | Business Report |
| 🐙 Git & GitHub | Version Control |

---

# 🔄 Project Workflow

```
Dataset
   │
   ▼
Data Cleaning (Python)
   │
   ▼
Exploratory Data Analysis
   │
   ▼
SQL Business Analysis
   │
   ▼
Power BI Dashboard
   │
   ▼
Business Report
   │
   ▼
Business Presentation
```

---

# 🗃️ Key SQL Analysis

Business questions answered using SQL include:

- Total number of customers
- Average purchase amount
- Average review rating
- Revenue by category
- Sales by category
- Customer distribution by subscription status
- Revenue by age group
- Sales by age group
- Most preferred payment methods
- Shipping type analysis
- Highest-rated product categories
- Seasonal purchasing trends

Example SQL Query

```sql
SELECT category,
AVG(purchase_amount) AS average_purchase
FROM customer
GROUP BY category
ORDER BY average_purchase DESC;
```

---

# 🐍 Python EDA & Data Cleaning

### Data Cleaning

✔ Removed duplicate records

✔ Checked for missing values

✔ Corrected data types

✔ Renamed columns

✔ Verified data consistency

### Exploratory Data Analysis

Performed analysis on:

- Customer demographics
- Gender distribution
- Purchase amount distribution
- Revenue by category
- Product popularity
- Review ratings
- Subscription analysis
- Purchase frequency
- Seasonal shopping trends
- Payment methods
- Shipping preferences
- Correlation analysis

**Libraries Used**

- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 📊 Power BI Dashboard

The dashboard provides an interactive overview of customer shopping behavior.

### Dashboard Features

- KPI Cards
  - Number of Customers
  - Average Purchase Amount
  - Average Review Rating

- Revenue by Category

- Sales by Category

- Revenue by Age Group

- Sales by Age Group

- Subscription Status Analysis

- Interactive Filters

  - Gender
  - Category
  - Shipping Type

- Dynamic Slicers

- Interactive Visualizations

---

# 💡 Key Insights

From the analysis:

- Clothing generated the highest sales among all categories.
- Accessories ranked second in revenue generation.
- Around **73%** of customers were non-subscribers.
- Young Adult customers contributed the highest revenue.
- The average customer spent **$59.76** per purchase.
- The average customer review rating was **3.75/5**.
- Subscription customers represented only **27%** of the customer base.
- Clothing and Accessories are the strongest-performing product categories.

---

# 📈 Business Recommendations

Based on the findings:

- Increase marketing efforts for Clothing and Accessories.
- Encourage subscriptions through loyalty rewards.
- Offer personalized promotions to frequent customers.
- Improve customer retention with targeted campaigns.
- Optimize inventory based on customer demand.
- Promote popular payment and shipping options.
- Focus seasonal promotions on high-performing product categories.

---

# 📁 Project Folder Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── SQL/
│   └── customer_behavior_sql_queries.sql
│
├── Power BI/
│   └── customer_behavior_dashboard.pbix
│
├── Dashboard Screenshots/
│   └── dashboard.png
│
├── Business Report/
│   └── Customer_Shopping_Behavior_Report.pdf
│
├── Presentation/
│   └── Gamma_Presentation.pdf
│
└── README.md
```

---

# 🖼️ Dashboard Screenshot

## Customer Behavior Dashboard

<p align="center">
<img width="511" height="285" alt="Screenshot 2026-06-25 192646" src="https://github.com/user-attachments/assets/ac51bf7e-1456-4ee0-a88f-755c3a7300ac" />
</p>

---

# 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git
```

### 2️⃣ Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 3️⃣ Run the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Customer_Shopping_Behavior_Analysis.ipynb
```

### 4️⃣ Execute SQL Queries

Import the dataset into:

- PostgreSQL
- MySQL
- SQL Server

Run the SQL script located in the **SQL** folder.

### 5️⃣ Open the Power BI Dashboard

Open:

```
customer_behavior_dashboard.pbix
```

using **Microsoft Power BI Desktop**.

---

# 🔮 Future Improvements

- Build a customer segmentation model using Machine Learning.
- Perform RFM (Recency, Frequency, Monetary) Analysis.
- Predict future customer purchases.
- Create a real-time dashboard connected to SQL.
- Publish the dashboard using Power BI Service.
- Automate dashboard refresh.

---

# 👨‍💻 Author

## Tejas Vish

**Aspiring Data Analyst**

### Skills

- Python
- SQL
- Power BI
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Data Cleaning
- Exploratory Data Analysis
- Business Analytics

📧 Email: tjsvish777@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/tejas-vishwakarma-912680419/

🐙 GitHub: https://github.com/Tejs31

---

## ⭐ If you found this project helpful, don't forget to Star this repository!
