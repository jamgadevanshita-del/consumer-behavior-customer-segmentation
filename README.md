# Consumer Behavior Segmentation & Customer Loyalty Analysis Using K-Means

## Project Overview

This project analyzes customer behavior and segments customers into meaningful groups using K-Means clustering.

The analysis focuses on customer demographics, average spending, income level, loyalty membership, and satisfaction score to identify different customer segments and derive business insights.

## Dataset

The dataset contains 10,000 customer records with information such as:

- Age
- Gender
- Income Level
- Region
- Purchase Category
- Average Spend
- Payment Mode
- Loyalty Membership
- Satisfaction Score

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology

1. Loaded and explored the dataset
2. Checked missing values and duplicate records
3. Selected relevant features for clustering
4. Encoded categorical variables
5. Standardized the features
6. Evaluated different cluster sizes using the Elbow Method
7. Evaluated clustering quality using Silhouette Score
8. Applied K-Means clustering
9. Created five customer segments
10. Analyzed the characteristics of each segment
11. Derived business insights from the clusters

## Customer Segments

| Cluster | Segment |
|---|---|
| 0 | Loyal but Dissatisfied Customers |
| 1 | Satisfied Non-Loyal Customers |
| 2 | Budget-Conscious Loyal Customers |
| 3 | At-Risk Customers |
| 4 | High-Value Loyal Customers |

## Key Insights

- Customer segments were primarily differentiated by income level, loyalty membership, and satisfaction.
- Some higher-income customers showed low satisfaction despite being loyalty members.
- Highly satisfied non-loyal customers represent a potential opportunity for loyalty conversion.
- Lower-income customers can still demonstrate strong loyalty.
- Non-loyal customers with low satisfaction formed an at-risk segment.
- Average spending was relatively similar across the five clusters.

## Conclusion

K-Means clustering helped identify distinct customer behavior patterns within the dataset. These segments can help businesses understand different customer groups and develop more targeted strategies for customer satisfaction, loyalty, and retention.

## Project Files

- `Ecommerce_Customer_Segmentation.ipynb` — Complete analysis and clustering workflow.
