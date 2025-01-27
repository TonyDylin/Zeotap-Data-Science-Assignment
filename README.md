# Zeotap-Data-Science-Assignment

## Task 1 - Business Insights

1. **Regional Contribution to Sales:**

North America is the top-performing region, contributing about 50% of the total sales. This indicates that the region is a significant driver of revenue. However, regions like
Africa contribute only 5%, suggesting potential growth opportunities in underperforming areas if marketing and inventory strategies are tailored to their needs.

<img width="463" alt="Screenshot 2025-01-27 at 12 43 38 PM" src="https://github.com/user-attachments/assets/e1d7fcd0-837b-4fb7-b072-57566348c3b0" />

2. **Category Performance:**

The Electronics category is the best-selling, generating nearly 40% of the total revenue. However, the Home Appliances category stands out with the highest average price per
product. This highlights a potential opportunity to market premium products to target high-value customers.

<img width="463" alt="Screenshot 2025-01-27 at 12 43 57 PM" src="https://github.com/user-attachments/assets/bc926d69-2c45-49a1-8e4b-94a03502767e" />


3. **Customer Spending Patterns:**

The top 10 customers account for around 25% of the total revenue. This suggests a high dependency on a small group of loyal customers, making it crucial to implement
retention strategies, such as loyalty programs or exclusive offers, to maintain and grow this segment.

4. **Seasonality in Sales:**

Sales volumes peak during the months of November and December, which aligns with holiday shopping trends. To capitalize on this, businesses can plan targeted campaigns
and offer discounts during this period to further boost sales.

<img width="463" alt="Screenshot 2025-01-27 at 12 44 57 PM" src="https://github.com/user-attachments/assets/288e9817-a33f-4759-b291-2b313ac61700" />
<img width="463" alt="Screenshot 2025-01-27 at 12 46 26 PM" src="https://github.com/user-attachments/assets/1240d94e-5aca-48bf-a7e7-df7933ff924b" />


5. **Product Preferences by Region:**

Regional preferences vary significantly. For example, customers in Europe have a strong preference for Fashion products, whereas North American customers favor Electronics. Adjusting product availability and marketing strategies based on these preferences could improve sales performance in specific regions.

<img width="463" alt="Screenshot 2025-01-27 at 12 47 03 PM" src="https://github.com/user-attachments/assets/e8f22f53-3d5d-4b44-82f6-d118f47f89a3" />

## Task 3: Customer Segmentation / Clustering

1. **Number of Clusters Formed:**

After analyzing the data using the Elbow Method, we decided to form 4 clusters. This number made sense because it provided clear distinctions between customer groups
while avoiding unnecessary complexity.

2. **Davies-Bouldin Index (DB Index):**

The DB Index for the clustering was calculated to be 0.67. This value shows that the clusters are well-defined, with a good balance between being
compact (similar within clusters) and well-separated (different from other clusters).

3. **Cluster Characteristics**
   
Here’s a summary of the key features for each cluster:

| Cluster | Average Spending ($) | Average Quantity Purchased | Average Transactions | Main Region     |
|---------|----------------------|----------------------------|----------------------|-----------------|
| 0       | 5636.61              | 20.56                      | 7.56                 | South America   |
| 1       | 2410.63              | 8.84                       | 3.68                 | South America   |
| 2       | 2784.74              | 10.87                      | 4.59                 | North America   |
| 3       | 3018.00              | 10.78                      | 4.35                 | Europe          |


**Key Takeaways**

* Cluster 0 represents high-value customers who spend the most, purchase in large quantities, and make frequent transactions. These customers are primarily
from South America.
* Cluster 1 contains low-value customers who have low spending, purchase less, and shop infrequently. These customers are also from South America.
* Cluster 2 mainly includes North American customers with moderate spending and consistent purchasing patterns.
* Cluster 3 consists of European customers with steady spending and transaction behavior.

4. **Visualization**

We used a PCA-based scatter plot to visualize the clusters in two dimensions. Each cluster appeared distinct and well-separated, which indicates that the clustering method
worked effectively.

<img width="808" alt="Screenshot 2025-01-27 at 12 52 06 PM" src="https://github.com/user-attachments/assets/d82436cf-0564-42e3-96c6-707cf03cc110" />

5. **Recommendations**

**1. High-Value Customers (Cluster 0):**
* Focus on retaining these customers by offering loyalty programs or exclusive deals. Since they contribute significantly to revenue, ensuring
their satisfaction should be a priority.

**2. Low-Value Customers (Cluster 1):**
* Engage this group with targeted campaigns, such as discounts, seasonal sales, or bundled offers, to encourage higher spending and transactions.

**3. Regional Strategies:**
* Tailor marketing and inventory for North America (Cluster 2) and Europe (Cluster 3) based on their preferences and behaviors. For instance, introduce region-specific promotions or product lines.

