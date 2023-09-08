# Customer Segmentation for Credit Card Users

## Objective
The objective of this project is to perform customer segmentation for credit card users. By clustering customers based on their credit card usage patterns, we can gain insights into different customer segments and tailor marketing strategies accordingly.

## Dataset
The dataset used for this project is sourced from Kaggle: [Credit Card Customer Segmentation Dataset](https://www.kaggle.com/datasets/thedevastator/predicting-credit-card-customer-attrition-with-m). 

### Data Preprocessing and Exploration
1. Checking for null values.
2. Filling numerical null values with mean.
3. Heatmap analysis.
4. Statistical summary.
5. Feature scaling.
6. Dropping insignificant columns.

## Methodology
### K-Means Clustering (Elbow Method)
To perform customer segmentation, the K-Means clustering algorithm was employed. The Elbow Method was utilized to determine the optimal number of clusters.

## Results
**The optimal number of clusters is found to be 3.**

### Final Dataset
Below is a sample of the final dataset with customers categorized into clusters. Each customer's transaction data has been categorized into one of the three clusters, allowing for distinct customer segmentation based on their credit card usage patterns.

| BALANCE   | BALANCE_FREQUENCY | PURCHASES | ONEOFF_PURCHASES | INSTALLMENTS_PURCHASES | CASH_ADVANCE | PURCHASES_FREQUENCY | ONEOFF_PURCHASES_FREQUENCY | PURCHASES_INSTALLMENTS_FREQUENCY | CASH_ADVANCE_FREQUENCY | CASH_ADVANCE_TRX | PURCHASES_TRX | CREDIT_LIMIT | PAYMENTS | MINIMUM_PAYMENTS | PRC_FULL_PAYMENT | TENURE | Cluster_Number |
|-----------|--------------------|-----------|-------------------|-------------------------|--------------|---------------------|-----------------------------|---------------------------------|-----------------------|-------------------|----------------|--------------|----------|-----------------|------------------|--------|----------------|
| 40.90075  | 0.818182           | 95.4      | 0                 | 95.4                    | 0            | 0.166667            | 0                           | 0.083333                       | 0                     | 0                 | 2              | 1000         | 201.8021 | 139.5098        | 0                | 12     | 1              |
| 3202.467  | 0.909091           | 0         | 0                 | 0                       | 6442.945     | -5.55E-17           | 0                           | 0                               | 0.25                  | 4                 | 0              | 7000         | 4103.033 | 1072.34         | 0.222222         | 12     | 2              |
| 2495.149  | 1                  | 773.17    | 773.17            | 0                       | 0            | 1                   | 1                           | 0                               | 0                     | 0                 | 12             | 7500         | 622.0667 | 627.2848        | 0                | 12     | 1              |
| 1666.671  | 0.636364           | 1499      | 1499              | 0                       | 205.788      | 0.083333            | 0.083333                  | 0                               | 0.083333              | 1                 | 1              | 7500         | 0        | 864.2065        | 0                | 12     | 1              |
| 817.7143  | 1                  | 16        | 16                | 0                       | 0            | 0.083333            | 0.083333                  | 0                               | 0                     | 0                 | 1              | 1200         | 678.3348 | 244.7912        | 0                | 12     | 1              |
| 1809.829  | 1                  | 1333.28   | 0                 | 1333.28                 | 0            | 0.666667            | 0                           | 0.583333                       | 0                     | 0                 | 8              | 1800         | 1400.058 | 2407.246        | 0                | 12     | 1              |

## Conclusion

In this project, we successfully segmented credit card users into three distinct clusters using K-Means clustering and the Elbow Method. This segmentation allows for targeted marketing strategies and a deeper understanding of customer behavior.

Thank you for exploring this analysis!

