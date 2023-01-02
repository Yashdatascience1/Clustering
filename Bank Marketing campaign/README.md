## Problem Statement

A bank needs to execute a marketing campaign for sending promotional messages more aligned with their specific characteristics. The objective is to cluster them
in groups such that the customized messaging can be sent to the groups according to their needs

---

## Characeteristics of the data:

1. There are 210 customers and 7 features
2. There are no missing values in any of the columns so we can use the clustering algorithm without any imputations
3. All the data are fairly symmetrical and there is little or no skewness
4. Only two columns have outliers. They are “probability_of_full_payment” and “min_payment_amt”
5. The highest count of maximum amount spent by the customers in single shopping is in the range of 5000 to 5250. This could be used to come up with schemes 
priced in the upper ball park of this range to attract a large chunk of customers that if they spend this much, they will get a reward or something.

---

## Conclusions from the study:

1. 3 clusters are identified from the analysis
2. Cluster #1 – High-end spenders with maximum credit limit and maximum chances of paying back to the bank
3. Cluster #2 - Low-end spenders with minimum credit limit and relatively least chances of paying back to the bank
4. Cluster #3 - Mid-end spenders with mid-range credit limit and mid-range chances of paying back to the bank

## Recommendations

1. For customers in cluster#1, bank should create schemes such as more reward points on spending a certain amount in a month. 
   Also, their credit limit can be increased because their probability of paying back to the bank is highest, so minimum risk. 
   For these customers, bank should promote a scheme of giving reward points on spending Rs. 5000 in a single shopping. 
   This is because, their max_spent_in_single_shopping is highest and they have(at least) that much of credit amount left in their account.

2. For customers in cluster#2, they are spending the least. However, the minimum amount paid by them on a monthly basis is maximum. 
   Therefore, we should promote some instalment-based payment schemes for them provided they spend over a certain amount.

3. For customers in cluster#3, bank can increase their credit card limit. 
   Their spend is decent enough as compared to cluster #1 and #2, their probability is almost similar to cluster #1. 
   So, if their credit card limit is increased with more offers, their tendency to spend more might increase.
