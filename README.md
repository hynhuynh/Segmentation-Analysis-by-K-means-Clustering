# Segmentation Analysis by K-means Clustering
## 1. Goal:
The primary objective of this project is to conduct a comprehensive Customer Segmentation Analysis for Amazon's retail sector based on the shopping behavior of customers. This segmentation is crucial for identifying specific customer groups to tailor suitable solutions for enhancing sales revenue and customer retention rate.

## 2. Method:
- Apply the RFM (Recency, Frequency, Monetary) model to evaluate each customer's transaction history.
- Utilize K-means clustering to categorize customers into distinct segments.
- Segment customers into 4 main categories and further divide them into 7 sub-segments.
 - To define 7 sub-segments, assign rankings ranging from 1 to 4 to each R F M Clusters, where a lower Recency value is considered better, and higher values for Frequency and Monetary are preferred. It means we assign higher R-scores to clusters with smaller mean Recency values, and lower F-scores and M-scores to clusters with smaller mean values.
   
![image](https://github.com/hynhuynh/Segmentation-Analysis-by-K-means-Clustering/assets/74954965/5ed90893-bb0c-4169-9d99-a1ffa324e98e)
![image](https://github.com/hynhuynh/Segmentation-Analysis-by-K-means-Clustering/assets/74954965/30ae04b3-9ae4-4cb7-a016-3d222ae55e8d)
![image](https://github.com/hynhuynh/Segmentation-Analysis-by-K-means-Clustering/assets/74954965/505205c7-4738-479c-832d-2a79ba64a1b9)

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
   
There is a significant portion of customers (37%) who are at risk and about to churn. On the positive side, 32% of our customer base falls into the categories of champions and potential loyalists.

Focus on retaining the "At Risk" customers while leveraging the loyalty and high-value potential of the "Champions" and "Potential Loyalists" to drive sales and growth.

Create a seamless onboarding process and offer new customer discounts to make their initial experience memorable and keep them coming back.

![image](https://github.com/hynhuynh/Segmentation-Analysis-by-K-means-Clustering/assets/74954965/49f07206-8836-4fa5-b82a-4e789ffcf60e)

![image](https://github.com/hynhuynh/Segmentation-Analysis-by-K-means-Clustering/assets/74954965/90710c53-7d6f-4cff-9b6e-71f6292cd52d)

Combine all segments together:

![image](https://github.com/hynhuynh/Segmentation-Analysis-by-K-means-Clustering/assets/74954965/9980f303-efe5-401f-b29c-a766dc1f35f1)
