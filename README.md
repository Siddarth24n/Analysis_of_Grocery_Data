
# 🛒 Blinkit-Style Grocery Data Analysis with Python & Power BI

This project analyzes grocery data to uncover insights into sales trends, customer behavior, product performance, and market dynamics. 


## Introduction
In the age of rapid grocery deliveries, businesses like Blinkit operate in a hyper-competitive, high-volume environment where data-driven decision-making is essential. This project simulates a real-world use case where grocery data is analyzed to extract actionable insights into sales performance, customer behavior, pricing strategies, and delivery efficiency.

The complete solution was built using:

Python for data analysis and visualization

📊 Power BI for business-facing interactive dashboards

Synthetic dataset simulating 7,000+ product records across multiple categories


## Project Structure
Blinkit_Grocery_Data_Analysis_Project
├── data/                   ← Synthetic grocery dataset (CSV)
├── notebooks/              ← Jupyter notebook for EDA
├── images/                 ← Saved plots from analysis
├── powerbi_dashboard/      ← Placeholder for Power BI (.pbix) file
├── requirements.txt        ← Python dependencies
└── README.md               ← Project overview


## The Dataset
A synthetic grocery dataset was generated containing over 7,000 records, mimicking Blinkit’s product catalog. It includes:

product_name and product_category

price, discount_level, and stock_quantity

delivery_time (in minutes)

shelf_life_days

customer_rating

This structure supports multi-faceted analysis across product metrics, logistics, and customer engagement.


## Key Features
- Exploratory Data Analysis (EDA)
- Pricing and Discount Impact
- Customer Buying Patterns
- Interactive Dashboards


## 🧪 Exploratory Data Analysis (EDA)
Using pandas, matplotlib, and seaborn, we explored:

1️⃣ Product Distribution
How inventory is spread across categories such as Fruits, Dairy, Snacks, etc.

📈 Chart: Product Category Distribution

2️⃣ Pricing Trends
Analyzing average prices and the impact of discount levels.

📈 Chart: Average Price by Category

3️⃣ Delivery Timeliness
Visualized delivery time distribution to identify potential bottlenecks.

📈 Chart: Delivery Time Distribution


## 📈 Power BI Dashboard
The Power BI dashboard (not included in this version) offers a business-facing interface to explore:

🔹 Sales by Category and Time

🔹 Top-Selling vs Underperforming Products

🔹 Pricing and Discount Effectiveness

🔹 Delivery Time Trends and Market Demand Shifts


## Key Insights
Discounts significantly influence conversion rates.

Certain categories (like Snacks and Beverages) showed shorter shelf lives and higher turnover.

Delivery times for products like Fruits and Dairy were more optimized, hinting at freshness-focused logistics.


## Tech Stack
| Tool                                   | Purpose                                  |
| -------------------------------------- | ---------------------------------------- |
| `Python (pandas, seaborn, matplotlib)` | Data cleaning and visual analysis        |
| `Jupyter Notebooks`                    | Interactive EDA                          |
| `Power BI`                             | Business intelligence dashboards         |
| `GitHub`                               | Version control and portfolio publishing |


## How to Use This Project
Clone the repository or download the ZIP folder.

Set up your environment:
pip install -r requirements.txt

Open the notebook in /notebooks/eda_grocery_data.ipynb.

Run the code to generate insights.

Open the Power BI dashboard and connect it to the dataset.


## Conclusion
This project showcases how grocery delivery businesses can leverage data to optimize operations, understand customer preferences, and make smarter pricing decisions. Whether you're a data enthusiast or an aspiring data analyst, this end-to-end project gives you a practical, portfolio-ready analysis workflow.


## Author
Siddarth N