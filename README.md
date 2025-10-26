## Communicating Analysis Results

### Project Overview

This Tableau dashboard was created and presented during the study period at Turing College. The project focused on analyzing company performance over a three-year period using data from the fictitious company *AdventureWorks*. The goal was to evaluate historical sales data, understand business performance trends, and provide insights for executive and sales management decision-making.

**Tools Used:**

* SQL (BigQuery) for data extraction, cleaning, and aggregation
* Excel for initial data review and exploration
* Tableau for visualization and dashboard development

**Link to Dashboard:**
[View Public Tableau Dashboard](https://public.tableau.com/views/AdventureWorks_SalesDashboard/HomeDashboard?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link)

##

### Part of ASK

**Chosen Topic:** Company Sales Performance

**Business Problem:**
The company seeks an overview of sales and performance to identify revenue trends, evaluate product profitability, and understand how performance varies across regions, time periods, and sales channels.

**Key Questions:**

* What were the company’s total revenue and profit over the given period?
* How were sales and orders distributed across quarters and years?
* How did sales vary across countries, product categories, and subcategories?
* How did reseller and online channels compare in terms of performance?
* Which years were most and least successful for the company?
* Which territories and resellers generated the highest profit?
* Which product categories were the most profitable?

##

### Part of PREPARE

**Data Collection and Preparation:**
Relevant data was extracted from the *AdventureWorks* database. Four core modules were used:

* Sales
* HR (Employees)
* Persons (Customers and Resellers)
* Products

Data cleaning, transformation, and aggregation were completed using **Google BigQuery**. The cleaned datasets were then exported in **CSV** format and connected to **Tableau** for dashboard creation.

##

### Part of SHARE

**Summary of Findings:**

* The company generated approximately **$141M** in revenue and **$40M** in profit over a three-year period.
* The most profitable period was **2003 Q3 – 2004 Q2**, with **$78M** in sales, accounting for 55% of total revenue.
* The least successful period was **2001 Q3 – 2002 Q2**, when revenue reached only **$30M** (21% of total).
* The **United States** was the most profitable market, while **Germany** performed the weakest.
* The **Bikes** category was the top-performing segment, generating **86% of total revenue ($95M)**.
* Within Bikes, **Mountain Bikes** and **Road Bikes** were leading subcategories.
* **Accessories** had the highest number of orders and strong profit margins, indicating high demand and efficiency.
* **Reseller sales** generated strong revenue and profit, while **online sales** excelled in order volume.
* The best-performing salesperson was **Linda C. Mitchell**, and the lowest-performing was **Syed E. Abbas**.
* The top-selling individual product was **Mountain-200 Black (size 38)**.

##

### Dashboard Previews

#### Home View

Overview of company performance, revenue, profit, and category breakdown.
![Home View](https://github.com/JonasLauri/AdventuresWork_Sales_Dashboard/assets/31222361/393cca5c-22b5-4000-bfa1-86758a2f7894)

#### Performance View

Detailed performance by year, territory, and sales representative.
![Performance View](https://github.com/JonasLauri/AdventuresWork_Sales_Dashboard/assets/31222361/e8dae4f6-7e63-4ea1-a93f-f62c7226e26c)

#### Production View

Breakdown by product category, subcategory, and profitability distribution.
![Production View](https://github.com/JonasLauri/AdventuresWork_Sales_Dashboard/assets/31222361/8928c678-901b-4340-a038-b395567a15b8)

##

### Key Takeaways

This analysis provided a clear understanding of sales performance, key revenue drivers, and areas of improvement. The insights helped highlight top-performing regions, products, and time periods, supporting data-driven decision-making for future strategy planning.


