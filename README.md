## 1. Data Description

This is a simulated dataset created to demonstrate skills in Excel Dashboards. The dataset was intentionally designed with imperfections such as: incorrect data formats, duplicated entries, inconsistent text casing (uppercase/lowercase), extra spaces, missing spacing, and spelling errors.

It contains **14 columns** and **733 rows** (including headers), with the following fields:

- **Date**: Transaction date (from 01/01/2023 to 31/12/2024)  
- **Invoice ID**: Unique transaction ID  
- **Customer Type**: Member or Normal  
- **Gender**: Male or Female  
- **Payment Method**: Cash, Credit Card, or E-wallet  
- **City**: Hanoi, Ho Chi Minh City, Da Nang  
- **Product Line & Product Name**: Includes product categories (Electronic accessories, Fashion accessories, Health and beauty, Home and lifestyle, Sports and travel, Food and beverages) and the corresponding product names  
- **% Discount**: Discount rate applied  
- **Unit Cost**: Cost per unit  
- **Quantity**: Number of units sold  
- **Unit Price**: Selling price per unit  
- **COGS**: Cost of Goods Sold per transaction  
- **Sales**: Total sales per transaction  
- **Profit**: Total profit per transaction  

## 2. Analysis Objectives

- Track revenue, profit, and profit margin over time  
- Identify high-performing and underperforming product lines to suggest ways to optimize revenue and profitability  

## 3. Skills and Tools Applied

### • Data Cleaning
- Removed duplicates  
- Standardized text format using functions such as `PROPER`, `TRIM`, and `REPLACE`  
- Split complex fields using **Text to Columns** (for the “Product Line & Product Name” column)  
- Change Type  

### • Data Analysis & Visualization
- Used **Pivot Tables** for key metric aggregation  
- Built an **interactive Dashboard** using Slicers and dynamic charts  

## 4. Key Findings

- Revenue and profit showed stable growth in 2024, particularly in **Hanoi** and **Da Nang**. However, **Ho Chi Minh City** showed a decline.  
- Profit margins increased in **Hanoi** and **HCMC** but declined in **Da Nang**, suggesting differences in cost control or pricing strategy.  
- The **Electronic Accessories** and **Sports and Travel** categories generated the highest revenue, while **Food and Beverages** contributed the least.  
- **E-wallet** was the most popular and revenue-generating payment method.  
- **Normal customers** contributed more revenue than **Members**, indicating possible underperformance in the membership program.  

## 5. Insights & Strategic Recommendations

- **Ho Chi Minh City shows the worst business performance.**  
  **Suggestion:** Strengthen marketing campaigns to increase awareness, promote promotional programs to stimulate demand but at a reasonable level (e.g., buy combo or total bill > X VND to receive gifts, etc.) to ensure revenue still increases without affecting profit margins much.

- **Profit margins have decreased in Da Nang**, possibly due to the abuse of discount programs or cost control issues.  
  **Suggestion:** Review discount activities and control costs more closely; focus on selective promotional campaigns.

- **Electronic accessories & Sports and travel** are the top-performing product lines, while **Food and beverages** underperform.  
  **Suggestion:** Focus on high-value electronic products with promotional campaigns (e.g., birthday discounts, loyalty gifts, etc.); consider partnerships with well-known F&B brands.

- **E-wallet is the most used payment method**, proving customers prefer convenience and speed.  
  **Suggestion:** Collaborate with e-wallet platforms (Momo, Zalo Pay, Shopee Pay, VN Pay, etc.) for promotions such as cashback, point accumulation, or X% discounts.

- **Membership program underperforms**, possibly due to lack of attractiveness or complicated process.  
  **Suggestion:** Simplify registration (at counter, online, by phone/email); improve benefits and personalization (e.g., priority checkout lanes, exclusive deals).
