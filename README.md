# customer_shopping_behavior_analysis

📌 Overview
An end-to-end data analytics project exploring 3,900 customer purchases to understand spending patterns, product preferences, discount usage, shipping choices, subscriptions, and customer segments. The workflow covers Python, SQL,and Power BI.

📊 Dataset
- Records: 3,900 | Columns: 18
- Missing values: 37 in Review Rating
- Includes customer demographics, purchase details, discounts, ratings, shipping, and subscription status.
  
🛠️ Tools
- Python & Pandas — EDA, data cleaning, and feature engineering
- MySQL Workbench — SQL business analysis
- Power BI — dashboard and visualisations
  
🔄 Workflow
1. Python EDA: Loaded the dataset and reviewed structure, summary statistics, and missing values.
2. Data Cleaning: Imputed missing ratings using category-level medians, standardised column names, created age_group and purchase_frequency_days, and reviewed redundant fields.
3. SQL Analysis: Investigated revenue by gender, discounts, product ratings, shipping, subscriptions, customer segments, repeat buyers, and age groups.
   
📈 Key Findings
- Revenue by gender: Male customers generated 157,890; female customers generated 75,191.
- Average purchase amount: Express shipping was 60.48 versus 58.46 for Standard shipping.
- Customer segments: 3,116 Loyal, 701 Returning, and 83 New customers.
- Top-rated products: Gloves (3.86), Sandals (3.84), Boots (3.82), Hat (3.80), and Skirt (3.79).
- Age groups: Young adults had the highest reported revenue at 62,143.
Figures are taken from the project report. Confirm currency and metric definitions before external use.

💡 Business Recommendations
- Test subscription benefits and loyalty rewards.
- Review discount-heavy products alongside profitability.
- Promote top-rated and best-selling products.
- Tailor campaigns using age-group and shipping insights.
  
▶️ How to Run
1. Open the Python notebook in Jupyter Notebook or VS Code.
2. Install dependencies if needed: pip install pandas numpy matplotlib seaborn jupyter
3. Set the correct dataset path and run the notebook cells.
4. Import the cleaned data into MySQL, then run the SQL queries in MySQL Workbench.
5. Open the .pbix file in Power BI Desktop and update data-source settings if prompted.
   
📁 Repository Contents
- notebooks/ — Python notebook
- sql/ — SQL queries
- powerbi/ — Power BI dashboard

## 📄 License
This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for details.
