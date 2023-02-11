# Car Insurance Highvalue Customers Retention 
## Winner of 2022 Travelers Business Insights & Analytics LDP Case Competition


![image](https://user-images.githubusercontent.com/82319213/218237882-f60482e8-062c-4783-b010-26aa1f3d74a0.png)


## Problem Statement
We are a group of Data Analysts working for Blue Buffalo Insurance, a property casualty insurance company based in downtown Hartford, Connecticut. Our business partner wants us to conduct a thorough analysis using historical policy and claim data. As the insurance market changes, the business partner is concerned about the company's retention rates. Customers are more willing to change the status quo than ever before. With current inflation and a volatile market, everyone is looking for ways to save a few dollars. Our team is in charge of analyzing and exploring historical data to determine which customers are "high value" to the company and how the company might be able to offer additional savings or incentives to keep these customers from switching insurance companies. For this analysis, we must incorporate the customers' driving telematics, which tracks the customers' driving habits. The goal here is to identify a subset of 'high value' customers and recommend retention strategies to Blue Buffalo Insurance executives.

## Approach
* In this case competition, we intend to analyze the dynamics that differentiate high-value customers. These dynamics will be of interest for the blue buffalo insurance company as they contribute to 80% of revenue.
* In the dataset, we have 22 attributes which include personal information of record (like gender, age) and also the payment information of the customers (like premium, claims, fraud claims, etc.)
* Coming to pre-processing, the dataset is merged into a single file. Next, we proceeded with basic preprocessing procedures like checking for null values or outliers. 
*  In our next step, we came up with our (“Time Travelers”) definition of a HIGH-VALUE customer. Further, new variables are created by feature engineering methods to reduce the complexity of the dataset, for example making effective use of acceleration values. We also discarded some values that retain redundant information.
* Finally, we found traits that can be attributed to high-value customers. Through this analysis, we found customers who could be classified as “high value customers”. Based on the findings we came up with some recommendations for the buffalo insurance company.

## High Value customer definition
We have defined ‘High Value Customers’ as customers who contribute to 80 percent of the company’s positive net revenue.2 Net revenue is defined as the difference between the total premium paid by the customer over the lifetime of the policy and the claim amount.
To calculate the total positive net revenue, we have considered the subset of customers with positive net revenue.

### Assumptions
The annual premium provided in the dataset is the cumulative annual premium of the current year.
* Assumption 1 : Hence, we have assumed that the annual premium paid by a customer increases every year @ 5% P.A. over the lifetime of the policy1. This has been taken into consideration for calculating the total premium paid by the customer over the lifetime of the policy.
* Assumption 2 : We have assumed that the annual_premium paid by the customer is not affected by whether or not a customer has made a claim or not.

Change factor has been calculated by dividing the total premium paid by the customer without considering 5% annual increase to the total premium paid by the customer with 5 % annual increase in premium.

Change_Factor = Total Premium (without 5% annual increase ) ÷
Total Premium (with 5% increase P.A.)


## Recommendations
### Customer Retention Strategies
* Since more than 50% of the high_value customers fall between the ages of 29 & 43 and most people start owning houses at this age , additional home insurance could be offered in combination with the car insurance at attractive prices / premiums . This could be a huge incentive to the ‘high_value’ customers and can encourage them to stay with Blue Buffalo Insurance
* Since ‘high_value’ customers have made no claims during the lifetime of their policy , they should be offered a no-claim bonus. This bonus could be offered at the time of every renewal. The bonus amount could be calculated based on the number of years the customer has been associated with Blue Buffalo Insurance.
* Direct maximum resources towards the high valued customers by providing regular check-ins and personalized support to ensure customer satisfaction
### Customer Acquisition Strategies
* Michigan, Wyoming, Alabama, and Minnesota account to a mere 9% of the entire customer base but consist of a huge percentage of the high valued customers. Targeted marketing should be done to acquire more customers from these states.
* Utilize the list of high-valued customers in order to get referrals of other customers which leads to – low acquisition rate and potentially an increase in the number of high valued customers.
