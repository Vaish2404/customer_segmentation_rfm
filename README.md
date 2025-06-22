# Customer Segmentation Using RFM and Clustering

This project segments customers using RFM (Recency, Frequency, Monetary) analysis and KMeans clustering, based on the [UCI Online Retail dataset](https://archive.ics.uci.edu/ml/datasets/online+retail). The goal is to identify distinct customer groups and help marketing teams take data-driven decisions.

---

## Dataset
- Source: UCI Online Retail Dataset
- Records: ~540,000
- Features: Invoice details, CustomerID, Purchase amounts, Country

---

## Techniques Used
- RFM Feature Engineering
- KMeans Clustering
- Silhouette Score for optimal `k`
- PCA for Dimensionality Reduction
- Data Preprocessing (null removal, filtering)
- Cluster Interpretation and Labeling

---

## Segment Profiles (k=5)

| Cluster | Description            | Behavior                                      |
|---------|------------------------|-----------------------------------------------|
| 0       | Engaged Regulars       | Recent, decent spend and frequency            |
| 1       | Loyal / VIP Customers  | Very active, frequent, high spenders          |
| 2       | Big Spenders (Rare)    | High spenders but infrequent buyers           |
| 3       | Casual At-risk         | Moderate activity and spend                   |
| 4       | Lost / Dormant         | Not recent, infrequent and low value          |

---

## Visualizations

Emebedded in the python notebook

---

