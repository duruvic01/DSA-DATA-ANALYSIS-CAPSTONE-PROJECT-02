# DSA-DATA-ANALYSIS-CAPSTONE-PROJECT-02
## PROJECT TOPIC: Kultra Mega Stores Inventory
## Project Overview: 
Kultra Mega Stores (KMS), headquartered in Lagos, specializes in office supplies and furniture. This project analyzes sales and operational data from 2009 to 2012, focusing on identifying trends, patterns and accessing the alignment between order priority and shipping costs.
### Data Source: 
The dataset used, titled  *KMS Sql Case Study.csv* and *Order_Status.csv* was provided by DSA & the Incubator Hub as part of the requirements in fulfillment and completion of my course Data Analysis with them. 

### Tools & Features: 
#### Tools: 
-	Microsoft Excel  [Download Here](https://www.microsoft.com/en-us/microsoft-365/excel?ocid=ORSEARCH_Bing&msockid=1d9ec785832e634d3841d23c828262a5)
-	Microsoft SQL Server Management Studio 20 
#### Features used :
-	Microsoft Excel: Used for CSV data handling
-	Microsoft SQL Server Management Studio 20:
  1. Create database
  2. Select statement
  3. Where clause
  4. Group by clause
  5. Order by clause
  6. Having clause
  7. Aliasing 
  8. Joins
  9.	Subqueries 
### Exploratory Data Analysis(EDA)
EDA involved the exploring of the Data to answer some questions about the Data such as:
#### Case Scenario I
1. Which product category had the highest sales?
2. What are the Top 3 and Bottom 3 regions in terms of sales? 
3. What were the total sales of appliances in Ontario? 
4. Advise the management of KMS on what to do to increase the revenue from the bottom 10 customers 
5. KMS incurred the most shipping cost using which shipping method
#### Case Scenario II
6. Who are the most valuable customers, and what products or services do they typically purchase? 
7. Which small business customer had the highest sales? 
8. Which Corporate Customer placed the most number of orders in 2009 – 2012? 
9. Which consumer customer was the most profitable one? 
10. Which customer returned items, and what segment do they belong to? 
11. If the delivery truck is the most economical but the slowest shipping method and Express Air is the fastest but the most expensive one, do you think the company appropriately spent shipping costs based on the Order Priority? Explain your answer

### Data Analysis(EDA):
The line of queries used during the analysis are seen in the attached *KMS.sql* file.
### Key Insights and Findings:
-	**Technology** was the top-performing product category in terms of sales.
-	The **West, Ontario and Prarie** ranked top 3 in sales, while **Nunavut, Northwest and Yukon** were the lowest.
-	**Adam Hart**, a Corporate Customer placed the most number of orders from 2009 -2012.
-	**Emily Phan**, a Consumer customer was the most profitable customer
-	**Returns** was seen in all segments, however **Consumer customers** showed the highest number.
-	KMS incurred the most shipping cost via **Delivery truck**.
-	If the delivery truck is the most economical but the slowest shipping method and Express Air is the fastest but the most expensive one, do you think the company appropriately spent shipping costs based on the Order Priority? Explain your answer
- No the company did not appropriately spend shipping costs based on Order Priority.
- This is because the delivery truck despite being the slowest & most economical was used for some orders with a Critical Order Priority, which contradicts the implied urgency by that priority level.
- Also the Express Air being the fastest & most expensive was also used for some orders with a Low Order Priority, which is evidently not cost-effective.
- All this suggests that shipping methods were assigned not on Order Priority, but was selected **based on the customer’s preference at the point of purchase**.
### Recommendations 
-	Stricter business rules for shipping modes should be established based on Order Priority
-	Consider the following recommendations to increase the revenue from the bottom 10 customers; 
1. Loyalty offers
2. Running personalized discounts
3. Offering referral incentives 
4. Upsell frequently purchased items
5. Promotion of bundle offers
6. Reach the out for feedback survey
### Appendix 
-	Here is the [.sql file](https://github.com/duruvic01/DSA-DATA-ANALYSIS-CAPSTONE-PROJECT-02/blob/main/KMS.ssmssln) and the [pdf](https://github.com/duruvic01/DSA-DATA-ANALYSIS-CAPSTONE-PROJECT-02/blob/main/KMS_SQL_DSA.pdf) containing all the queries used in this analysis
