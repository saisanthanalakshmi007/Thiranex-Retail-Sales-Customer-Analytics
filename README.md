# Retail Sales and Customer Analytics

## Thiranex Data Science Internship – Task 4

**Author:** Sai Santhana Lakshmi S

---

## Project Overview

This project performs an end-to-end analysis of a retail transaction dataset to understand sales performance, product performance, customer purchasing behavior, and category-level revenue.

The project follows a practical retail analytics workflow inspired by the concepts demonstrated in the provided task tutorial.

The analysis includes sales calculations, customer analysis, product analysis, category analysis, market-basket style product pair analysis, customer segmentation, visualizations, and business recommendations.

---

## Domain

**Retail Analytics**

---

## Dataset

The dataset contains **200 retail transactions** generated for this project.

The dataset contains the following features:

- Order ID
- Order Date
- Customer ID
- Product
- Category
- Quantity
- Unit Price
- Revenue

### Revenue Calculation

Revenue was calculated using:

`Revenue = Quantity × Unit Price`

---

## Products

The dataset contains products from different retail categories, including:

- Laptop
- Headphones
- Smartphone
- T-Shirt
- Jeans
- Sneakers
- Backpack
- Watch
- Coffee Maker
- Blender

---

## Product Categories

The products are grouped into the following categories:

- Electronics
- Clothing
- Footwear
- Accessories
- Home Appliances

---

## Project Workflow

### 1. Data Generation

An original retail transaction dataset was created using Python, NumPy, and Pandas.

The dataset contains 200 transactions and includes customer, product, category, quantity, price, date, and revenue information.

### 2. Data Understanding

The dataset was examined using:

- Dataset information
- Statistical summary
- Missing value checking
- Duplicate checking
- Data type inspection

### 3. Basic Retail Analytics

The following business metrics were calculated:

- Total revenue
- Total quantity sold
- Total orders
- Unique customers
- Unique products
- Unique categories
- Average order value

### 4. Product Analysis

Product-level analysis was performed to identify:

- Total quantity sold by product
- Total revenue by product
- Top-selling products

### 5. Sales Trend Analysis

Sales were analyzed at different time levels:

- Daily sales
- Monthly sales
- 7-day moving average

These analyses help understand sales patterns and changes over time.

### 6. Category Analysis

Category-level analysis was performed to determine:

- Total quantity sold by category
- Total revenue by category
- Category revenue share
- Highest revenue-generating category

### 7. Customer Analysis

Customer purchasing behavior was analyzed using:

- Total customer spending
- Top-spending customers
- Number of orders
- Total quantity purchased
- Customer spending segments

Customers were grouped into:

- Low Value
- Medium Value
- High Value

### 8. Product Pair Analysis

A market-basket style analysis was performed to identify products that were frequently purchased by the same customers.

This can provide useful information for:

- Product bundling
- Cross-selling
- Promotional offers

---

## Visualizations

The following visualizations were created:

1. Daily Sales Trend
2. Monthly Sales Trend
3. Top 5 Products by Revenue
4. Revenue by Product Category
5. Top 10 Customers by Spending
6. Revenue Share by Product Category
7. Daily Revenue and 7-Day Moving Average
8. Customer Distribution by Spending Segment

All visualization files are stored in the `visualizations` folder.

---

## Business Insights

The analysis helps identify:

- Products generating high revenue
- Categories contributing significantly to revenue
- High-spending customers
- Customer spending segments
- Changes in daily and monthly sales
- Frequently associated product purchases
- Overall retail sales performance

---

## Business Recommendations

Based on the analysis, businesses can:

- Maintain sufficient inventory for high-performing products.
- Focus marketing efforts on strong revenue-generating categories.
- Develop loyalty strategies for high-value customers.
- Use customer segmentation for targeted marketing.
- Monitor sales trends for better inventory planning.
- Use frequently associated products for bundle offers and cross-selling opportunities.

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

Thiranex_Task4_Retail_Analytics/

├── Retail_Sales_Analytics.ipynb  
├── retail_transactions.csv  
├── README.md  
│  
└── visualizations/  
&nbsp;&nbsp;&nbsp;&nbsp;├── daily_sales.png  
&nbsp;&nbsp;&nbsp;&nbsp;├── monthly_sales.png  
&nbsp;&nbsp;&nbsp;&nbsp;├── top_products.png  
&nbsp;&nbsp;&nbsp;&nbsp;├── category_revenue.png  
&nbsp;&nbsp;&nbsp;&nbsp;├── customer_spending.png  
&nbsp;&nbsp;&nbsp;&nbsp;├── category_revenue_share.png  
&nbsp;&nbsp;&nbsp;&nbsp;├── moving_average_sales.png  
&nbsp;&nbsp;&nbsp;&nbsp;└── customer_segments.png  

---

## Conclusion

This project demonstrates an end-to-end real-world retail analytics workflow using Python.

The analysis combines data generation, data understanding, sales analysis, product analysis, category analysis, customer analysis, customer segmentation, product pair analysis, visualization, and business recommendations.

The project demonstrates how retail transaction data can be analyzed to understand sales performance and customer behavior and support data-driven business decisions.

---

## Author

**Sai Santhana Lakshmi S**

**Thiranex Data Science Internship – Task 4**