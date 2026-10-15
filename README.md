# Customer Shopping Behavior Analysis

## Project Overview
This data analytics project explores customer shopping behavior across **3,900 purchase records** and **18 columns**. It combines Python-based data cleaning and feature engineering, SQL queries for business questions, and a Power BI dashboard to help identify customer, product, and purchasing trends.

## Business Objectives
- Compare purchase revenue across customer groups.
- Identify customers who use discounts but still make above-average purchases.
- Find highly rated products and compare shipping preferences.
- Understand how subscription status relates to spending and revenue.
- Segment customers based on previous purchases.
- Explore purchasing patterns by age group and product category.

## Tools & Technologies
- **Google Colab:** Cloud-based environment used to run the Python notebook
- **Python (pandas):** Data cleaning, exploration, and feature engineering
- **MySQL:** SQL queries for business analysis
- **Power BI:** Dashboard development and visualization
- **Dataset:** customer shopping behavior CSV

## Project Files
| File | Description |
|---|---|
| `customer_shopping_behavior.csv` | Source dataset containing 3,900 records and 18 columns |
| `customer_shopping_behavior_analysis.ipynb` | Data exploration, cleaning, and feature engineering in Python |
| `customer_behavior_sql_queries.sql` | SQL queries addressing business questions |
| `customer_behavior_dashboard.pbix` | Power BI dashboard file |
| `Customer Shopping Behavior Analysis Document.pdf` | Supporting project document |

## Workflow
1. **Load and explore the data** using pandas.
2. **Check data quality**, including missing values and summary statistics.
3. **Handle missing review ratings** by filling them with the median rating within each product category.
4. **Standardize column names** and rename the purchase amount field for easier analysis.
5. **Create additional features**, including age groups and purchase-frequency intervals in days.
6. **Prepare the data for SQL analysis** and answer business questions with queries.
7. **Build a Power BI dashboard** and summarize the insights in the presentation.

## Questions Explored
The SQL script includes analyses of:
1. Revenue by gender.
2. Discount users whose purchase amount is at or above the overall average.
3. Top products by average review rating.
4. Average purchase amount by shipping type.
5. Customer count, average spend, and revenue by subscription status.
6. Products with the highest discount rate.
7. New, returning, and loyal customer segments based on previous purchases.
8. Top purchased products within each category.
9. Subscription status among repeat buyers.
10. Revenue contribution by age group.

## Selected Insights
The project presentation highlights the following findings:
- Female customers generated slightly higher total revenue than male customers.
- Customers using express shipping had a higher average purchase amount than customers using standard shipping (approximately **$65 vs. $58** in the presentation).
- The analysis identifies highly rated products and customers who combine discount use with above-average spending.
- The presentation recommends subscription promotion, loyalty programs, targeted marketing, and promotion of highly rated products.

## How to Run
### Python notebook (Google Colab)
1. Download or clone this repository, or upload the notebook and CSV to your Google Drive.
2. Open `customer_shopping_behavior_analysis.ipynb` in Google Colab.
3. Upload `customer_shopping_behavior.csv` to the Colab session, or mount Google Drive and update the file path in the notebook.
4. Run the cells in order. The notebook uses pandas for data exploration, cleaning, and feature engineering.

### MySQL
1. Import the prepared dataset into your MySQL database and create/select a table named `customers`.
2. Open `customer_behavior_sql_queries.sql` in MySQL Workbench or your preferred MySQL client.
3. Check that the table columns match the names used in the queries (for example, `purchase_amount`, `review_rating`, and `age_group`). Some fields may be created during Python data preparation.
4. Run the queries individually and review the results.

### Power BI
Open `customer_behavior_dashboard.pbix` using Power BI Desktop. If prompted, update the data source to your CSV file or MySQL connection, then refresh the report.

## Author
**Sai Teja Reddy**  
Aspiring Data Analyst
