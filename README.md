\# E-Commerce Sales \& Customer Behaviour Analysis Using Python



\## Project Overview



This project explores historical e-commerce transaction data to analyse sales performance, product revenue, geographical trends, and customer purchasing behaviour.



Using Python, Pandas, NumPy, Matplotlib, and Seaborn, the project transforms raw transaction data into meaningful business insights that can support data-driven decision-making.



\## Business Objectives



\- Analyse overall sales performance and revenue trends.

\- Identify top-performing products based on revenue.

\- Understand geographical sales distribution.

\- Examine customer purchasing patterns and repeat purchases.

\- Generate actionable business recommendations.



\## Tools \& Technologies



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Google Colab

\- Jupyter Notebook



\## Dataset



\*\*Source:\*\* UCI Machine Learning Repository – Online Retail Dataset



\[Download the Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)



The original dataset contains 541,909 transaction records from a UK-based online retailer, covering transactions between December 2010 and December 2011.



The original Excel dataset is not included in this repository. Please download it from the official source and upload it to Google Colab to reproduce the analysis.



\## Data Preparation



The dataset was cleaned and prepared through the following steps:



\- Removed cancelled invoices.

\- Excluded transactions with zero or negative quantities.

\- Excluded transactions with zero or negative unit prices.

\- Removed duplicate records.

\- Handled missing product descriptions.

\- Converted invoice dates into datetime format.

\- Created a revenue column using quantity multiplied by unit price.

\- Extracted month, year, weekday, and hour information for analysis.



\## Key Performance Indicators



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



\## Analysis Performed



1\. Monthly Revenue Analysis

2\. Top 10 Products by Revenue

3\. Country-wise Sales Analysis

4\. Customer Purchase Analysis

5\. Repeat Customer Analysis

6\. Weekday Sales Analysis

7\. Top Customer Analysis



\## Key Business Insights



\- The United Kingdom generated approximately £9 million in revenue, making it the dominant market.

\- November 2011 recorded the highest monthly revenue at approximately £1.50 million.

\- Approximately 65.58% of identified customers made two or more purchases during the observation period.

\- Product-level revenue analysis helps identify products contributing

