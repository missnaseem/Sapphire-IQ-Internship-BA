# Amazon India Sales Dashboard
**Student:** SABOORA NASEEM | **Tool used:** Excel


# 1. Project overview
Amazon India generates large volumes of sales transactions across multiple product categories, payment methods and fulfillment channels. Analysing these transactions individually makes it difficult to identify sales trends, profitability, patterns and operational issues.

This dashboard is designed in a simple and easy-to-understand management dashboard for Manoj to submit to his manager, Ravi, who comes from a non-technical background. The dashboard will help Ravi monitor sales trends, profit performance, product and order performance, customer order status, payment methods, fulfillment status and geographic performance supporting better business understanding and decision-making. 

## 2. Dataset
- Number of rows - 10,000; 
- Number of columns - 13; 
- Date range -  1/1/2024 - 30/8/2026; 
-- Briefs asked in each section:
- section 1 - Overall sales and profit performance;
- section 2 - Category and product performance;
- section 3 - Order status and revenue loss;
- section 4 - Payment, fulfillment and geographic performance
  

## 3. Data preparation
- Checks done: neither duplicate values nor missing values found in the dataset
- Fields I created: created order_month column to analyze changing sales and profit trends over the months and years.  
- How I treated cancelled and returned orders: Kept all the cancelled and returned records as provided in the dataset.Analyzed orders separately using order_status.Compared order counts and sales values to understand cancellations and returns.Did not treat cancelled or returns sales as actual financial loss statements for business because this approach provides  a more accurate picture of business performance whole helping identify potential issues in order fulfillment  , customer satisfaction and returns.
  

## 4. KPI definitions
- Total Sales = =SUM('Amazon sales raw data'!H2:H10001) ; sum of all the sales
- Profit Margin % = =SUM('Amazon sales raw data'!I2:I10001)/SUM('Amazon sales raw data'!H2:H10001) ; profits/sales
- Total orders =COUNTA of all order_ids
- Return Rate % = total orders returned / total orders
- Cancellation rate % = total orders cancelled / total orders
- [NOTE - FORMULAS ARE USED IN WORKSHEETS AT REQUIRED PLACES ACCORDING TO THE CELL REFERENCES]

  
## 5. Dashboard preview
- RAW DATA - [Amazon Sales Data India.xlsx](https://github.com/user-attachments/files/35541806/Amazon.Sales.Data.India.xlsx)
- DASHBOARD PDF - [Amazon Sales Data India (1).pdf](https://github.com/user-attachments/files/35541982/Amazon.Sales.Data.India.1.pdf)
- DASHBOARD - <img width="1282" height="762" alt="image" src="https://github.com/user-attachments/assets/43ff9909-8d10-4b84-86e9-d1fb78fc8153" />
- OBJECTIVES -<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3d1750ac-f2ce-405f-bf65-5248fb10317a" />
<img width="1740" height="862" alt="image" src="https://github.com/user-attachments/assets/5cff02d4-55d3-485e-b9db-d6bdc0cc52ba" />
<img width="1458" height="848" alt="image" src="https://github.com/user-attachments/assets/616d1745-3f87-47e2-88b4-388d41e93475" />
<img width="1310" height="866" alt="image" src="https://github.com/user-attachments/assets/a10d97a7-e1cf-464a-8d25-0e79e1d912e4" />


## 6. Key findings
1. PROFIT MARGIN TREND : The profit margin was around 21% in 2024. It dropped to 14% in first half of 2025 and increased to 22% by the second half of 2025.
2. CATEGORY PERFORMANCE : Electronics and mobiles is the largest category in terms of sales and profit, with approximately 12.36 CR recorded sales. Pantry and groceries has the lowest sales.
3. ORDER STATUS : 81.47% of orders were delivered , while total 9.85% were returned[4.85%] and cancelled[5%]. The value of returned and cancelled orders is approximately 1.56 CR , which represents 10.04% of total sales.
4. PAYMENT AND GEOGRAPHIC PERFORMANCE : UPI is the largest payment method by sales contributing approximately 7.8 CR . Amazon FBA leads in fulfillment sales, contributing approximately 10.7 CR. Maharashtra is the leading state in sales and profit , with approximately 2.9 CR in sales and kerala is the lowest performing state in sales and profits.

   
## 7. Recommendations
1. IMPROVE PROFIT MARGIN - Focus on controlling costs and maintaining the profit margin , especially during months when it decreases.
2. IMPROVE LOW-SELLING CATEGORIES - The business should check its demand , product range and pricing. Increase promotions and customer reviews of product for better product performance.
3. MANAGE AND REDUCE RETURNS AND CANCELLETAIONS - Identify the reasons behind returns and cancellations and take necessary steps to reduce them.
4. IMPROVE DELIVERY PERFORMANCE - Focus on better order handling and deliveries to increase successful deliveries and reduce returns and customer complaints.
5. FOCUS ON HIGH SELLING STATES - Maintain sales and good performance in Maharashtra and explore opportunities to increase sales in other states by exploring market , understanding competitor strategy and increasing manpower which will help business to improve its turnover and market capital.  

   
## 8. How to use the dashboard
- The dashboard can be used to understand key performance indicators including , sales, profits, orders, profit margin, return rate and cancellation rate.
- Use the charts to compare monthly sales, profit and category performance.
- TOP 10 filters are applied on category wise performance charts and state wise performing charts that helps to identify high performing parts of business.
- Slicers are present in objective sheets which have detailed analysis of business that helps to filter the data according to the requirements.
- clear the filters to return to the full chart views.
  

## 9. Limitations
- The dashboard is based on the available dataset.
- It does not explain the exact reasons behind returned and cancelled orders.
- It does not predict future sales and profits.
- It does not compare AMAZON'S performance with other companies.
- The value of returned and cancelled orders is not confirmed as actual financial loss.
  

