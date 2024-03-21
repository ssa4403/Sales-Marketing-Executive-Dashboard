# Sales and Marketing Analysis Dashboard

This project showcases an executive dashboard for "AdventureWorks," offering insights into key business metrics. I've facilitated an intuitive grasp of key performance indicators (KPIs) - revenue, profit, order volume, and customer engagement metrics. The multifaceted layers of the dashboard reveal trends, such as the surge in sales of specific products and the pivotal contributions of top customers.

# Tools Used:

**Microsoft Power BI -** for dashboard creation and reporting

**Power Query -** for data extraction, wrangling, and cleaning

**DAX -** for custom expressions and calculations

**M-code -** for advanced data transformations

**Key Features:**

1. Financial KPIs - Revenue, Profit, Orders

2. Product-level performance tracking

3. Customer segmentation and behavior analysis

4. Revenue and sales trends over time

5. Interactive visual elements for user exploration

# Process

**Step 1: Data Extraction**

The extraction process involves sourcing raw data from multiple systems within AdventureWorks. This could include sales
figures, customer data, and product information. The extraction is set to gather historical and current data to provide a 
comprehensive view.

**Step 2: Data Wrangling and Cleaning with Microsoft #powerquery**

With #powerquery, the raw data undergoes rigorous cleaning and transformation. This step ensures that the data quality is high with consistent formatting, which is essential for accurate analysis. Processes such as removing duplicates, handling missing values, and normalizing text are applied.

**Step 3: Data Modeling**

The cleansed data is then structured into a cohesive model. Relationships are built, and data is normalized into fact and dimension tables with defined primary and foreign keys, setting the stage for efficient and scalable analysis.

**Step 4: DAX & M-code**

Utilizing DAX (Data Analysis Expressions) & M-code, calculated columns, measures, and custom functions are created to enrich the data model. This enables advanced analytics and the generation of actionable insights directly within the dashboard.

**Step 5: Dashboard Creation**

Finally, the polished data model is visualized through the executive dashboard. This includes interactive elements, trend analysis, and KPI tracking, all designed with the end-user in mind. The dashboard allows for quick assessments and data-driven decision-making.

# Detailed Dashboard Features

**Executive Dashboard:**

The executive dashboard provides a high-level overview of "AdventureWorks" company metrics. Key performance indicators like total revenue, profit, order count, and return rate are displayed prominently. This summary view is perfect for executives who need to quickly grasp the company's financial health.

**Drill-Down Capabilities:**  

Users can view performance over time and across product categories. This interactivity offers a dynamic user experience:

   1. Revenue Trending:
      Track sales performance over time, identify patterns, and analyze seasonal trends.
   
   2. Orders by Category:
      Break down the order volume by product category, such as accessories, bikes, and clothing, to identify which sections are performing above or below expectations.

   3. Product-Level Analysis:
     Users can click on any category to drill down further into the top-selling products within that category.


**Product Detail Analysis:**
   
When a user selects a product category from the executive dashboard, they're taken to the product detail page:

   1. Product Selection:
      Choose a specific product to analyze, such as the 30 oz. Water Bottle, and immediately see the total orders, adjusted profit, and other relevant metrics.

   2. Sales and Profit Targets:
      Assess how each product performs against monthly sales and profit targets, providing clear indicators of over- or under-performing products.

   3. Time Series Analysis:
      Visualize sales trends for each product over time to understand customer demand and to adjust stock levels accordingly.


**Customer Insights:**
   
The customer detail page provides in-depth analytics about the customer base:

   1. Total Customers & Revenue Per Customer: 
      Understand the size of your customer base and track average revenue per customer to gauge customer value.
   
   2. Demographic Segmentation: 
      View orders by income level and occupation, helping tailor marketing strategies to specific customer segments.
   
   3. Top Customers: 
      Identify and analyze top customers by orders and revenue, which is crucial for developing targeted sales strategies and personalized engagement.

The dashboard is designed to be fully responsive, adapting to various screen sizes and devices, ensuring that data is always accessible and readable.
