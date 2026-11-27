# Amazon India Sales Dashboard
**Student:** SABOORA NASEEM | **Tool used:** Excel


# 1. Project overview
Amazon India generates large volumes of sales transactions across multiple product categories, payment methods and fulfillment channels. Analysing these transactions individually makes it difficult to identify sales trends, profitability, patterns and operational issues.

This dashboard is designed in a simple and easy-to-understand management dashboard for Manoj to submit to his manager, Ravi, who comes from a non-technical background. The dashboard will help Ravi monitor sales trends, profit performance, product and order performance, customer order status, payment methods, fulfillment status and geographic performance supporting better business understanding and decision-making. 

## 2. Dataset
Number of rows - 10,000
Number of columns - 13
Date range -  1/1/2024 - 30/8/2026
Briefs asked in each section:
section 1 - Overall sales and profit performance
section 2 - Category and product performance
section 3 - Order status and revenue loss
section 4 - Payment, fulfillment and geographic performance

## 3. Data preparation
- Checks done: neither duplicate values nor missing values found in the dataset
- Fields I created: created order_month column to analyze changing sales and profit trends over the months and years.  
- How I treated cancelled and returned orders: Kept all the cancelled and returned records as provided in the dataset.Analyzed orders separately using order_status.Compared order counts and sales values to understand cancellations and returns.Did not treat cancelled or returns sales as actual financial loss statements for business because this approach provides  a more accurate picture of business performance whole helping identify potential issues in order fulfillment  , customer satisfaction and returns. 

## 4. KPI definitions
- Total Sales = =SUM('Amazon sales raw data'!H2:H10001) ; sum of all the sales
- Profit Margin % = =SUM('Amazon sales raw data'!I2:I10001)/SUM('Amazon sales raw data'!H2:H10001) ; profits/sales
- Return Rate % = total orders returned / total orders

  
## 5. Dashboard preview
DASHBOARD - <img width="1282" height="762" alt="image" src="https://github.com/user-attachments/assets/43ff9909-8d10-4b84-86e9-d1fb78fc8153" />
OBJECTIVES -<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3d1750ac-f2ce-405f-bf65-5248fb10317a" />
<img width="1740" height="862" alt="image" src="https://github.com/user-attachments/assets/5cff02d4-55d3-485e-b9db-d6bdc0cc52ba" />
<img width="1458" height="848" alt="image" src="https://github.com/user-attachments/assets/616d1745-3f87-47e2-88b4-388d41e93475" />
<img width="1310" height="866" alt="image" src="https://github.com/user-attachments/assets/a10d97a7-e1cf-464a-8d25-0e79e1d912e4" />







## 6. Key findings
1. [A finding with a number, for example: Category X gives Y% of total sales]
2. [Finding 2]
3. [Finding 3]

   
## 7. Recommendations
1. [An action the business can take, and the finding that supports it]
2. [Recommendation 2]

   
## 8. How to use the dashboard
[Which slicers and filters exist and what they do]


## 9. Limitations
[What the dashboard does not cover]


