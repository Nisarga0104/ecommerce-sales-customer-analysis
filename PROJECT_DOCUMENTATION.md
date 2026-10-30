\# Project Documentation

\## E-Commerce Sales \& Customer Behaviour Analysis Using Python



\## 1. Project Objective



The objective of this project is to analyse historical e-commerce transaction data to understand sales performance, product contribution, geographical revenue distribution, and customer purchasing behaviour.



The analysis uses Python-based data manipulation and visualisation techniques to convert raw transaction records into meaningful business insights.



\## 2. Dataset Information



\*\*Dataset:\*\* Online Retail Dataset



\*\*Source:\*\* UCI Machine Learning Repository



\*\*Link:\*\* https://archive.ics.uci.edu/dataset/352/online+retail



\*\*Original Records:\*\* 541,909



\*\*Time Period:\*\* December 2010 – December 2011



\### Dataset Columns



| Column | Description |

|---|---|

| InvoiceNo | Unique invoice or transaction number |

| StockCode | Product identifier |

| Description | Product description |

| Quantity | Number of units purchased |

| InvoiceDate | Date and time of transaction |

| UnitPrice | Price per unit |

| CustomerID | Customer identifier |

| Country | Customer's country |



\## 3. Tools and Libraries



\- Python – Core programming language.

\- Pandas – Data cleaning, transformation, and aggregation.

\- NumPy – Numerical operations.

\- Matplotlib – Data visualisation.

\- Seaborn – Statistical visualisation.

\- Google Colab – Development environment.



\## 4. Data Cleaning and Preparation



The following preparation steps were performed:



1\. Created a separate working copy of the original dataset.

2\. Standardised column names.

3\. Converted InvoiceNo into string format.

4\. Converted InvoiceDate into datetime format.

5\. Removed records with missing invoice numbers or invalid dates.

6\. Excluded cancelled invoices identified by invoice numbers beginning with C.

7\. Removed transactions with zero or negative quantities.

8\. Removed transactions with zero or negative unit prices.

9\. Removed duplicate records.

10\. Replaced missing product descriptions with Unknown Product.

11\. Created a Revenue column.



\### Revenue Calculation



Revenue was calculated as:



Revenue = Quantity × UnitPrice



Additional date-based columns were created to support monthly, weekday, and hourly analysis.



\## 5. Key Performance Indicators



The following KPIs were calculated:



| KPI | Calculation |

|---|---|

| Total Revenue | Sum of transaction revenue |

| Units Sold | Sum of purchased quantities |

| Total Orders | Count of distinct invoice numbers |

| Identified Customers | Count of unique CustomerID values |

| Average Order Value | Total Revenue / Total Orders |

| Repeat Purchase Rate | Customers with at least two distinct orders / Identified Customers × 100 |



\### Final KPI Results



| Metric | Result |

|---|---:|

| Original Records | 541,909 |

| Cleaned Records | 524,878 |

| Total Revenue | £10,642,110.80 |

| Units Sold | 5,572,420 |

| Total Orders | 19,960 |

| Identified Customers | 4,338 |

| Average Order Value | £533.17 |

| Repeat Purchase Rate | 65.58% |



\## 6. Exploratory Data Analysis



\### 6.1 Monthly Revenue Analysis



Monthly revenue was aggregated to identify sales trends over time.



\*\*Finding:\*\* November 2011 recorded the highest monthly revenue at approximately £1.50 million.



\*\*Business Application:\*\* Businesses can use monthly trends to plan seasonal campaigns, inventory, and promotional activities.



\### 6.2 Product Performance Analysis



Products were grouped by description and their total revenue was calculated.



Non-product transaction descriptions such as Postage, DOTCOM Postage, and Manual were excluded from the improved top-product analysis.



\*\*Business Application:\*\* Identifying revenue-generating products supports product prioritisation and inventory planning.



\### 6.3 Geographical Sales Analysis



Revenue was grouped by country to understand geographical performance.



\*\*Finding:\*\* The United Kingdom contributed approximately £9 million in revenue.



\*\*Business Application:\*\* Country-level analysis can help identify strong markets and potential expansion opportunities.



\### 6.4 Customer Purchase Analysis



Customer purchase activity was examined using distinct invoice counts.



Customers with two or more distinct orders were classified as repeat customers.



\*\*Finding:\*\* Approximately 65.58% of identified customers made multiple purchases.



\*\*Business Application:\*\* Repeat purchasing behaviour can help businesses evaluate customer retention and loyalty initiatives.



\### 6.5 Weekday Sales Analysis



Revenue was grouped by day of the week to examine differences in purchasing activity across weekdays.



\*\*Business Application:\*\* This analysis can help businesses understand weekly demand patterns and plan marketing activities.



\### 6.6 Top Customer Analysis



Customers were ranked based on their total transaction revenue.



\*\*Business Application:\*\* Identifying high-value customers can support customer segmentation and targeted retention strategies.



\## 7. Business Recommendations



1\. Customer Retention: Develop loyalty programmes and personalised promotions to encourage repeat purchases.

2\. Seasonal Planning: Prepare inventory and marketing campaigns ahead of observed high-revenue periods.

3\. Market Diversification: Explore opportunities to expand beyond the dominant UK market.

4\. Product Strategy: Use product-level revenue analysis to support inventory and promotional decisions.

5\. Customer Segmentation: Identify high-value customers and develop targeted engagement strategies.



\## 8. Data Limitations and Assumptions



\- Cancelled invoices were excluded.

\- Negative-quantity return transactions were excluded.

\- Transactions with zero or negative unit prices were excluded.

\- Customer-level analysis includes only records with an available CustomerID.

\- Revenue is calculated from quantity multiplied by unit price and does not account for shipping, refunds, or other adjustments.

\- December 2011 contains partial-month data, ending on 9 December.

\- The repeat purchase rate measures multiple purchases within the available dataset period, not long-term customer loyalty.



\## 9. Conclusion



This project demonstrates how Python can be applied to real-world transaction data for data cleaning, exploratory data analysis, KPI development, and business insight generation.



The analysis provides a practical example of using data to understand revenue performance, product contribution, geographical trends, and customer purchasing behaviour.



\---



\*\*Project Category:\*\* Exploratory Data Analysis (EDA)



\*\*Domain:\*\* E-Commerce / Retail Analytics



\*\*Technologies:\*\* Python, Pandas, NumPy, Matplotlib, Seaborn

