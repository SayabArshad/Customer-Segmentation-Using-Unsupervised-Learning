# Task-2-Customer-Segmentation-Using-Unsupervised-Learning


## ✅ Task Objective
To segment customers into meaningful groups based on their spending and product preferences using unsupervised machine learning.

## 🔍 Our Approach
- The dataset was explored and cleaned by selecting relevant numerical features such as Annual Income, Spending Score, and Age.
- Features were scaled using `StandardScaler` to normalize the data.
- The Elbow Method and Silhouette Score were used to determine the optimal number of clusters, with K=4 showing the best balance of compactness and separation.
- K-Means clustering was applied, and cluster assignments were added to the dataset.
- The clusters were visualized in 2D using PCA (Principal Component Analysis).
- Cluster profiles were interpreted to describe each segment’s behavior.

## 📊 Results and Findings
- Four distinct customer groups were identified:
  - Budget-conscious buyers
  - Mid-level loyal customers
  - High-income occasional spenders
  - Premium frequent buyers
- Business can now target these segments with customized marketing strategies, loyalty programs, and personalized offerings.
- This segmentation can enhance customer satisfaction and maximize revenue.
