# Churn-Analysis-EDA

![image](https://github.com/SurekhaBerlin/Churn-Analysis-EDA/assets/35975433/00d4dbbc-552f-4412-8d77-6e402466a3a7)


1. BUSINESS UNDERSTANDING & OVERVIEW
   
	Telecom Industry is a highly competitive industry. So, customer retention is very important. In the telecom industry, customers can easily choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences a significant annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition. So, the main aim of this industry is to prevent the customer from churning. Various analysis can be conducted for predicting which customers are at high risk of churn.
Customer Churn means whether the customer has stopped using the product and switched to a competitor product. To prevent customers from churning, we can use data analysis to identify potential features and design strategies to prevent customers from leaving. It is also noted that an already loyal customer is less likely to churn and easier to retain than try gaining a new customer.
In this project I am analyzing the customer level data of a leading telecom industry to come up with  insights into the main indicators of the churn and conclusion.
The dataset I am using is for a project purpose. The name of the dataset is (Customer-Churn.csv). Each row represents a customer; each column contains the customer’s attributes, customer ID, gender, Senior Citizen, Partner, Dependents, tenure, Phone Service, Multiple Lines, Internet Service, Online Security, Online Backup, Device Protection, Tech Support, Streaming TV,  Streaming Movies, Contract, Paperless Billing, Payment Method, Monthly Charges, Total Charges, Churn.
***************
2. OBJECTIVES
•	The objective is to obtain a data-driven solution that will allow us to reduce churn rates and, therefore, to increase customer satisfaction and corporation revenue.
•	To predict how likely a customer will churn by analyzing its characteristics: 
1.	Demographic information
2.	Account informations
3.	Services informations
•	To Compare the demographic makeup of churned and non-churned consumers. Visualizations, such as stacked bar charts, are used to display the findings.
•	To prevent customers from churning, we can use data analysis to identify potential features and design strategies to prevent customers from leaving.
•	Recommend product strategies to business team based on  analysis of product offerings that will help in retaining the customer based on available data.

***************
3. UNDERSTANDING THE DATA

![image](https://github.com/SurekhaBerlin/Churn-Analysis-EDA/assets/35975433/99370490-f921-4799-be4e-3b41d0801e24)



***************
4.	DATA DESCRIPTION
•	Data consists of 7043 fictional customers who belong to various demographics (single; with dependents; senior citizen) and subscribe to different products offerings (internet service; phone line; streaming TV; streaming movies; online security) from a telecom company.
•	Independent variables: 17 Categorical and 3 Continuous
•	Dependent Target variable: “Churn”
•	Churn Rate (Baseline) is 26.5%
*************
 4.1 TARGET VARIABLE
•	Dependent Target variable: “Churn”
•	The Churn Rate is 26.58 % 
•	The dataset is highly imbalanced i.e., there are a lot of loyal customers who are not leaving (the ‘No’ category customers) the telecom service provider to switch to the competitor product. So, we analyze the data with other features while taking the target values separately to get some insights.
![image](https://github.com/SurekhaBerlin/Churn-Analysis-EDA/assets/35975433/ee59bc59-e916-446a-b9e2-f522c687b484)



***************
5. STEPS INVOLVED IN THE PROCESS
•	Initial setup
•	Data Inspection
•	Data Cleaning
•	Data preparation
•	EDA (Exploratory Data Analysis)
•	Models & Algorithms
•	Data Product
•	Data Visualization
•	Make Decisions
•	Inference and Conclusions
******************
![image](https://github.com/SurekhaBerlin/Churn-Analysis-EDA/assets/35975433/ba1d9917-4545-4b48-a394-01fbc67d127d)
******************
EDA Exploratory Data Analysis
*****
***
Categorical Analysis
*****
Numerical Analysis
*******
Correlation plot

![image](https://github.com/SurekhaBerlin/Churn-Analysis-EDA/assets/35975433/ff1e452d-99aa-4108-b400-7cb85bb053c3)

Initial inference from the correlation plot

1.High Churn is seen in the case of Senior Citizens, Customers without partners, Month-to-month contracts, No online security, No Tech support, First year of subscription, and Fibre Optics Internet
*
2.Low Churn is seen in the case of long-term contracts, Subscriptions without internet service, and the customers engaged for more years
*
3.Factors like Gender, Availability of PhoneService, and number of multiple lines have almost no  impact on Churn


***************************
![image](https://github.com/SurekhaBerlin/Churn-Analysis-EDA/assets/35975433/1efb63f2-b896-44af-9125-e981622ca6ae)


FINAL THOUGHTS 
1.	The churn rate of female and male customers is almost the same. So, from this analysis no insights can be concluded. The churn rate of Female is 26.95% and Male is 26.20%
2.	The churn rate of senior citizens is almost double that of young citizens. The churn rate of seniors is almost double that of young customers. The rates for Young Citizens are 23.65% and for Senior Citizen is 41.68% 
3.	Customers with a partner churn less than customers with no partner. Customers without partners are churning more in comparison to customers with partners. The churn rate of customers with Partner is 19.7% and without Partner is 32.97%
4.	Dependent customers are less churners when compared to the non-dependents. The churn rates for Non-Dependent customers are 31.28% and the churn rate of Dependent is 15.53%
5.	The customers with Fiber optic internet service are having a high churning rate. The churn rate for customers with DSL internet service is 18.99% and the churn rate for customers with Fiber optics internet service is 41.89%
6.	The churn rate for customers without online security is very high. The churn rate of customers without Online Security is 41.79%
7.	The churn rate for customers without Online Backup is high. The churn rate of customers without Online Backup is 39.94%
8.	The churn rate for customers Without Device Protection is high compared with customers with Device protection. The churn rate of customers without Device Protection is 39.94%
9.	Customers with no tech support are churning more. The churn rate for customers without Tech Support is 41.65%
10.	Customers with month-to-month contracts have higher churn rates compared to clients with yearly contracts. The churn rate for customers with Month - Month contracts is 42.71%.
11.	Customers opted for paperless billing churn more than the counterpart. The churn rate for customers opted for Paperless Billing is 33.59 %
12.	Customers who opted for an electronic check as a payment method are more likely to churn. The churn rate for customers with Electronic Check is 45.29%
13.	The least churners are there in the tenure group of 61 – 72 Months and the top churners are there in the tenure group of 1 - 12 Months. The churn rate of the tenure group of 1 - 12 is 47.68% and the churn rate of the tenure group 61 – 72 is 6.60% .
14.	New customers (low tenure) are more likely to churn.
15.	The churn rate tends to be larger when monthly charges are high.
16.	Customers with high total charges are less likely to leave the company.
17.	The churn ratio for female customers with fiber optic internet service is high compared to the male customers.
18.	Customers with Partners and Dependents have lower churn rate as compared to those who don’t have partners & Dependents.
19.	Customers with no internet service have a lower churn rate.
20.	Churn rate is much higher in the case of Fiber Optic InternetServices. Customers who do not have services like OnlineSecurity, OnlineBackup, and TechSupport have left the platform in the past month.
21.	Contract duration (strong): Month-to-month contracts churn significantly more than one- or two-year contracts.
22.	Internet services (moderate): Internet Fiber or DSL services churned at a higher pace than other services.]
23.	Dependents (Moderate): Customers who support dependents churned less.
24.	(Low) Paperless billing: Customers who opted for paperless billing had a higher attrition rate.
25.	(Low) Streams: Indicates whether the consumer is utilizing the Internet service to stream TV or movies.
26.	(Low) Automatic payment: Customers who had automatic payments set up were less likely to churn.
27.	(Low) Partner: Customers who were married had a lower churn rate.
28.	High Churn is seen in the case of Senior Citizens, Customers without partners, Month-to-month contracts, No online security, No Tech support, First year of subscription, and Fibre Optics Internet
29.	Low Churn is seen in the case of long-term contracts, Subscriptions without internet service, and the customers engaged for more years
30.	Factors like Gender, Availability of PhoneService, and number of multiple lines have almost no  impact on Churn if considered alone
31.	Female with partners are non-churners. The retain rate for customers with partner and no partner is almost the same. But if we look, the churn rate has increased in females with no partners when compared to females with partners.

