# Marketing-Campaign-Performance
This repo contains the marketing campaign data of 2,240 customers of a marketing team. 

![](https://github.com/adulojumiriam-hub/Marketing-Campaign-Performance/blob/main/Marketing%20Campaigns.webp)
P.C: Marketing Trends for 2022. From INCAE by Marie Fernanda Marin, 2022.

## Introduction

Marketing campaign data of 2,240 customers of Maven Marketing, including customer profiles, product
preferences, campaign successes/failures, and channel performance.

The primary objective here is to analyze and draw meaningful insights from the Marketing Campaign Results dataset which would aid the management in making informed decisions.

## Research Questions

The analysis was guided by the following questions:

1. Are there any null values or outliers? How will you handle them?

2. What factors are significantly related to the number of web purchases?

3. Which marketing campaign was the most successful?

4. What does the average customer look like?

5. Which products are performing best?
  
6. Which channels are underperforming?

## Tools and Skills Used

- Power BI
- Power Query
- Data Cleaning and Preparation
- Data Modelling
- Dashboard Development
  
 ## Data Analysis
 
### Question 1: Are there any null values or outliers? How will you handle them?

The original [dataset](https://github.com/adulojumiriam-hub/Marketing-Campaign-Performance/blob/main/marketing_data_insight.csv), consisting of 2,240 customers was examined for missing values and outliers using Power Query filtering, sorting and column profiling. A total of 24 null values (approximately 1% of the dataset) were identified in the income column and removed due to their minimal impact.
Unrealistic values such as extreme birth years (e.g 1893) were also removed as they fall outside a valid human age range, a threshold was applied to exclude customers above a reasonable age range and records with birth years earlier than 1925 were removed to ensure data validity. This brought the total removed rows to 27 and total remaining to 2,213. High income values were retained, although significantly higher than the average, they may represent the presence of valid high-value customers. No negative values were found in spending or purchase-related columns.

### Data Visualization

![](https://github.com/adulojumiriam-hub/Marketing-Campaign-Performance/blob/main/Miriam%20Aduloju%20Marketing%20Insight%20Dashboard.png)


### Qusetion 2: What factors are significantly related to the number of web purchases?

Web purchases are primarily influenced by customer behavior and engagement, rather than demographic factors. 
Recency shows a strong negative relationship, with recently active customers making significantly more web purchases.
Website visits display a non-linear relationship, where moderate engagement leads to higher purchases, but excessive visits do not always convert.
Customers who responded to the final campaign recorded higher average web purchases (5.07) compared to non-responders (3.91), making it a key driver of online behavior.
Household composition plays an important role:
Customers with no young children make significantly more web purchases
Customers with teenagers show increased web purchasing activity, with purchases rising as the number of teenagers increases
Education level is also influential: customers with higher education (especially Graduation and PhD levels) demonstrate higher web purchasing behavior compared to lower education levels

### QUESTION 3: Which marketing campaign was the most successful?

The final campaign was the most successful, recording the highest number of customer responses. Earlier campaigns had significantly lower acceptance rates, indicating that the final campaign was more effective in engaging customers.

### Question 4:  What does the average customer look like?

The average customer is a moderately engaged, recently active, multi-channel shopper.

- Makes approximately 4.09 web purchases on average
- Is recently active, as lower recency is associated with higher purchasing behavior
- Engages across multiple channels (web, store, and catalog), rather than relying on a single channel
- Is more likely to respond to marketing campaigns, particularly the most recent one
- Typically belongs to the Graduation education level, which is the most common group, followed by PhD holders
- Is most likely Married, representing the dominant marital status segment
- Is more likely to have no young children, as customers without children show higher web purchasing activity. However, may live in a household with teenagers, as the presence of teenagers is associated with increased web purchases

### QUESTION 5: Which products are performing best?

Wines are the best-performing product category, generating the highest total revenue by a significant margin, followed by meat products. Other product categories such as fruits, fish, sweets, and gold products contribute considerably less to overall sales.

### QUESTION 6: Which channels are underperforming?

The catalog channel is the most underperforming, with the lowest average number of purchases per customer. Web purchases show moderate performance, while store purchases are the strongest, especially among high-frequency buyers.

## FURTHER INSIGHTS AND SUGGESTIONS 

- The catalog channel underperforms compared to web and store channels, indicating low customer engagement. Store purchases lead overall, while web serves as a strong secondary channel, suggesting an opportunity to improve catalog effectiveness or integrate it better with digital channels.

- Customers with higher education levels, particularly those with PhDs and undergraduate degrees, exhibit higher web purchasing behavior, suggesting that education may influence digital engagement. Simplifying the system could lead to the optimization of web purchasing.

- Customers without children demonstrate significantly higher web purchasing activity, suggesting that household responsibilities may limit online shopping behavior. On the other hand, customers with teenagers in the household exhibit higher web purchasing behavior, with web purchases increasing as the number of teenagers rises. This indicates that Teenagers influence online shopping (clothes, gadgets, etc.). Knowledge of the target audience would assist in future campaigns.
