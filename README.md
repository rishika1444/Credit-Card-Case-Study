This Case Study has been done on the top of python 3.7 by using pandas, numpy, matplotlib and seaborn packages and code has been written on Jupyter Notebook "Case Study 2-Credit Card Case Study" and data is also attached in CSV as per the problem.

The problem of this case study is given below:

ANALYTICS IN CREDIT CARD INDUSTRY:

Analytics has penetrated every industry owing to the various technology platforms that collect information and thus, the service providers know what exactly customers want. The Credit Card industry is no exception. Within credit card payment processing, there is a significant amount of data available that can be beneficial in countless ways.

Understanding the customer behaviour 
The data available from a credit card processor identifies the types of consumer and their business spending behaviors. Hence, developing the marketing campaigns to directly address their behaviors indeed grows the revenue and these considerations will result in greater sales.

Personalize offering based on data results 
Data also reveals specific interests and needs in individual customers that a company can leverage, this addressing their needs more efficiently. Specific promotions can be sent out related to where these customers are located and this builds sales more quickly.

Use trends and patterns to get new customers 
The transactions and activities of the existing customers that they do in terms of purchase behavior tends to reflect larger trends that are coming. This information provides a strategy to go after possible customers in the target audience.

Uncover suspicious activity 
The data from credit card processing is becoming increasingly important as a tool to fight fraud. When combined with artificial intelligence, this data is being analyzed quickly to uncover areas of purchase activity.

Reduce chargebacks 
The ability to detect suspicious activity and patterns in data can also assess whether or not a transaction might result in a chargeback. Using analytics to track each transaction reveals anomalies. This information can help you reject that transaction and save your business from chargebacks.


BUSINESS PROBLEM: 
In order to effectively produce quality decisions in the modern credit card industry, knowledge must be gained through effective data analysis and modeling. Through the use of dynamic datadriven decision-making tools and procedures, information can be gathered to successfully evaluate all aspects of credit card operations. PSPD Bank has banking operations in more than 50 countries across the globe. Mr. Jim Watson, CEO, wants to evaluate areas of bankruptcy, fraud, and collections, respond to customer requests for help with proactive offers and service.
DATA AVAILABLE 
This book has the following sheets: Customer Acquisition: At the time of card issuing, company maintains the details of customers. 
Spend (Transaction data): Credit card spend for each customer Repayment: Credit card Payment done by customer

Following are some of Mr. Watson’s questions to a Consultant (like you) to understand the customers spend & repayment behavior. 
1. In the above dataset, 
a. In case age is less than 18, replace it with mean of age values.
b. In case spend amount is more than the limit, replace it with 50% of that customer’s limit. (customer’s limit provided in acquisition table is the per transaction limit on his card) 
c. Incase the repayment amount is more than the limit, replace the repayment with the limit. 
2. From the above dataset create the following summaries:  
a. How many distinct customers exist?  
b. How many distinct categories exist?  
c. What is the average monthly spend by customers?  
d. What is the average monthly repayment by customers? 
e. If the monthly rate of interest is 2.9%, what is the profit for the bank for each month? (Profit is defined as interest earned on Monthly Profit. Monthly Profit = Monthly repayment – Monthly spend. Interest is earned only on positive profits and not on negative amounts)
f. What are the top 5 product types?  
g. Which city is having maximum spend?  
h. Which age group is spending more money? 
i. Who are the top 10 customers in terms of repayment?
3. Calculate the city wise spend on each product on yearly basis. Also include a graphical representation for the same.
4. Create graphs for  
a. Monthly comparison of total spends, city wise  
b. Comparison of yearly spend on air tickets  
c. Comparison of monthly spend for each product (look for any seasonality that exists in terms of spend)
5. Write user defined PYTHON function to perform the following analysis: You need to find top 10 customers for each city in terms of their repayment amount by different products and by different time periods i.e. year or month. The user should be able to specify the product (Gold/Silver/Platinum) and time period (yearly or monthly) and the function should automatically take these inputs while identifying the top 10 customers.

