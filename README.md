# Segmentation Analysis by K-means Clustering
## 1. Goal:
The primary objective of this project is to conduct a comprehensive Customer Segmentation Analysis for Amazon's retail sector based on the shopping behavior of customers. This segmentation is crucial for identifying specific customer groups to tailor suitable solutions for enhancing sales revenue and customer retention rate.

## 2. Method:
Apply the RFM (Recency, Frequency, Monetary) model to evaluate each customer's transaction history.
Utilize K-means clustering to categorize customers into distinct segments.
Segment customers into 4 main categories and further divide them into 7 sub-segments.

## 3. Result:
4 main customer segments with distinct purchasing behaviors:
 - Cluster 0: Named "Need Attention": who purchased often and spent big amounts, but haven't purchased recently and are about to lose.
 - Cluster 1: Named "Lost Customer": customers who haven't visited the shop for a long time and don't spend much money in this shop.
 - Cluster 2: Named "Best Customer": who bought most recently, most often, and are heavy spenders.
 - Cluster 3: Named "New Customer": who bought more recently, but not often and haven't spent much.

![image](https://github.com/hynhuynh/Segmentation-Analysis-by-K-means-Clustering/assets/74954965/cef9dbae-2007-45b6-bfb8-5dd745c124ba)

Besides this, we can identify fine-grained segments:
 - Champions: Bought recently, buy often, and spend the most.
 - Potential Loyalists: Spend good money. Above average recency, and frequency. Core customers.
 - Big Spender: Spend the most.
 - New Customers: Bought more recently, but not often, and haven’t spent much.
 - At Risk: Spent above average monetary values, purchased often but a long time ago.
 - Lost: Lowest recency, frequency, and monetary values.

![image](https://github.com/hynhuynh/Segmentation-Analysis-by-K-means-Clustering/assets/74954965/ac6bf455-4a98-4d8e-8a69-af3289d0638c)
![image](https://github.com/hynhuynh/Segmentation-Analysis-by-K-means-Clustering/assets/74954965/d418db2d-ac37-4160-8265-c04e9d68f93e)

![image](https://github.com/hynhuynh/Segmentation-Analysis-by-K-means-Clustering/assets/74954965/9980f303-efe5-401f-b29c-a766dc1f35f1)
