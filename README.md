 Day 3: Customer Segmentation using KMeans Clustering


##  Project Objective

The goal of this project is to segment customers based on their behavior using **KMeans Clustering**. This enables businesses to create tailored marketing strategies for each group to increase sales and engagement.


##  Dataset

- **Dataset Name:** Mall_Customers.csv  
- **Source:** Provided by Main Flow Services for Internship Task-3  
- **Columns Used:**  
  - `Age`  
  - `Annual Income (k$)`  
  - `Spending Score (1-100)`


##  Tools and Libraries Used

- Python  
- Pandas, NumPy – Data handling  
- Matplotlib, Seaborn – Visualization  
- Scikit-learn – Scaling, Clustering, PCA  
- Jupyter Notebook – Development environment


## Key Steps Performed

###  Data Preprocessing
- Checked for nulls and duplicates
- Scaled features using `StandardScaler`

###  Clustering with KMeans
- Used **Elbow Method** to find optimal clusters (k = 5)
- Performed **KMeans Clustering**
- Assigned each customer to a cluster

### Dimensionality Reduction
- Applied **PCA** for 2D visualization

###  Visualizations
- Elbow Plot to choose optimal `k`
- 2D Scatter plot with PCA
- Cluster plot with centroids
- Spending Score vs Annual Income colored by cluster


## Cluster Insights

- **Cluster 0:** Low income, low spending — target with discounts  
- **Cluster 1:** Older with moderate spending — build loyalty  
- **Cluster 2:** High income & high spending — upsell premium products  
- **Cluster 3:** High income but low spending — re-engage via offers  
- **Cluster 4:** Average income, high spending — ideal for cross-selling


##  Outcome

This project demonstrates how customer segmentation can help businesses:
- Understand different customer behaviors
- Strategize marketing campaigns more effectively
- Increase profitability through targeted engagement


##  Internship Context

This project was completed as part of **Task 3** in my internship with  
**Main Flow Services and Technologies Pvt. Ltd., Sector 63, Noida**.

## Contact

If you’d like to know more or collaborate, feel free to reach out!

