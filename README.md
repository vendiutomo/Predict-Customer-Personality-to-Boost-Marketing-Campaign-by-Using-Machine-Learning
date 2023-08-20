# Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning
#3 Mini Project at Rakamin Academy

A company can develop rapidly when it knows its customer personality behavior, so it can provide better services and benefits to customers who have the potential to become loyal customers.

By processing historical marketing campaign data to improve performance and target the right customers so they can transact on the company's platform, from this data insight our focus is to create a cluster prediction model to make it easier for companies to make decisions.

## Conversion Rate Analysis Based on Income, Spending, and Age
### Age Group
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/46985ab7-eaaa-497d-b5fb-49ba3246027f)

### Spending
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/6176c7c5-8a57-4ccf-9373-9e2322fb987b)

### Web Visit
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/f1cfca6e-c8be-4dea-9651-e69501a833f5)

### Transaction
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/47893d5d-19aa-4f81-b9ad-2ee795dc2a05)

### Campaign
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/43636665-de8a-4439-9f43-73fb6644b59e)

### Income
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/b85e4f3c-7f07-49d3-9fd3-1a76a2207ed8)

## Data Cleaning & Preprocessing
- Handling Missing Value.
- Handling Duplicated Data.
- Feature Selection.
- Feature Encoding.
- Feature Transformation.

## Data Modeling
- Elbow Method K- Mean Clustering
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/790c17b1-3222-4edd-bbdd-5d3159e8833f)

> From clusters 1 to 4 the distance between clusters is quite far apart, but from clusters 4 to 5 onwards the distance is quite close and getting closer. It can be said that cluster 4 is an optimal cluster.

- Silhouette Score Evaluation

|Number of Clusters|Silhouette Score|
|----------------|-------------------------------|
|2|0.270107|
|3|0.188347|
|4|0.183801|
|5|0.105559|
|6|0.093623|
|7|0.093414|
|8|0.095792|
|9|0.094958|

> The silhouette score in cluster 5 is quite low compared to the previous cluster, so using 4 clusters is sufficient.

* Modeling with 4 Clusters
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/359c160a-443e-465c-a01d-ca264e0ae8ab)


## Customer Personality Analysis for Marketing Retargeting

### Interpretation
* **Cluster 0**;
**Age**: 27 - 83 (mean : 52) (median : 50);
**Income**: 1.730.000 - 162.397.000 (mean : 35.256.810) (median : 34.587.000);
**Spending** : 5.000	- 442.000 (mean : 93.553) (median : 63.000);
**Conversion Rate**: 0 - 0,25 (mean : 0,01) (median : 0).

The highest level of education in this cluster is S1. Most are married. Most ages are between 40-59 (middle adulthood). Dominated by those who already have children, the most are those who have 1 child.

* **Cluster 1**;
**Age**: 28 - 82 (mean : 56) (median : 55);
**Income**: 2.447.000 - 666.666.000 (mean : 73.947.680) (median : 72.504.000);
**Spending** : 62.000	- 2.525.000 (mean : 1.247.473) (median : 1.193.000);
**Conversion Rate** : 0 - 0,33 (mean : 0,02) (median : 0).

Dominated by people who have at least S1 education. the majority of this group are married or engaged. Most ages are in the middle age and old age group. Most are married but not yet parents.

* **Cluster 2**;
**Age**: 31 - 80 (mean : 58) (median : 58);
**Income**: 4.428.000 - 94.871.000 (mean : 55.867.771) (median : 56.559.000);
**Spending** : 199.000	- 1.829.000 (mean : 688.941) (median : 606.000);
**Conversion Rate** : 0 - 0,25 (mean : 0,02) (median : 0).

Most of them have studied S1. the majority of this group are also married or engaged. Most ages are in the middle age and old age group. Very dominated by those who are already parents who already have at least 1 child.

* **Cluster 3**;
**Age**: 28 - 80 (mean : 52) (median : 58);
**Income**: 48.192.000 - 105.471.000 (mean : 81.795.368) (median : 82.365.500);
**Spending** : 523.000 -	2.525.000 (mean : 1.651.451) (median : 1.682.500);
**Conversion Rate** : 0 - 1 (mean : 0,46) (median : 0.33).

Most have an undergraduate degree, but not a few have masters and doctoral degrees. Dominated by single and married people. The number of each age group is not much different. the majority are those who are not married and do not have children.

### Analysis
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/d1dd4691-2789-4811-bc8c-7cf9b7765f14)
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/6e3cc104-5f93-4a5b-b20d-c9e30167e776)
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/cdf64392-1174-4b4d-8d2f-8c769e9f4b4e)
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/fbc089d6-14c4-431e-a32e-26906e4144af)
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/2bb437d5-34db-4faa-9b5a-d9d70e5b1fd7)
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/97e5ddfb-d9a5-4d09-811a-7775175c8f2f)
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/1f56a53d-85fb-41fc-a343-23f9c638b3c1)
![image](https://github.com/vendiutomo/Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning/assets/128874036/c49bd48a-3b04-4f08-bf6b-736812fb6e08)

1. **Cluster 0 (Risk of Churn)**

> The largest number of customers compared to other clusters. The amount of income and spending is the smallest among the existing clusters. However, this group visits the website the most, although they rarely make transactions. The response to the campaign is also low, which means they make transactions organically.

> For this group it is necessary to look again at the behavior towards the product. Is the product not suitable or there may be price sensitivity. It is hoped that this group can conduct transactions more frequently.

2. **Cluster 1 (Mid Spenders)**

> Has the second largest total income and spending. This group rarely visits the platform but quite often responds to the campaigns that are being carried out. Actually this group should have a high conversion rate, but with a smaller amount of spending. They have a fairly large average use of promos compared to 'High Spenders'.

> Must focus on finding purchasing interests from groups so that it is optimized to make transactions without using coupons to be able to increase revenue. Can perform further analysis in order to make more frequent transactions, perhaps by providing more personalized recommendations. Analysis can also make promotions that may be of interest to this group.

3. **Cluster 2 (Low Spenders)**

> Has a smaller spending compared to 'Mid Spender' and High Spender'. This group tends to visit the web/platform quite often and look for promos, even though the number of promos used is not as much as 'Mid Spender'.

> Can make product recommendations that are more personal with appropriate promos in order to increase transactions for this customer group.

4. **Cluster 3 (High Spenders)**

> Has the largest total income and total spending among other clusters, even though it is included in the cluster with the smallest number of customers. The conversion rate for this group is also the largest, which means that customers in this cluster rarely visit the website but once visited they can make a large number of transactions.

> It is necessary to retarget this group so that they retain and continue to transact. Can also monitor transactions and retention. Also focus on improving services and services so that customer groups do not churn.





# Presentation is [Here](https://docs.google.com/presentation/d/1VpW3D1DfnT159jXK-ocnMrCaoI8zxvIi/edit?usp=sharing&ouid=105243878469528725537&rtpof=true&sd=true)!
