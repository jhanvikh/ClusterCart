# 🛍️ ClusterCart

**ClusterCart** is a customer segmentation-based recommendation engine for e-commerce platforms. It uses clustering algorithms to group customers by demographics and then recommends products based on cluster behavior and collaborative filtering. The goal is to simulate real-world shopping patterns and deliver personalized product suggestions.

---

## 📌 Features

- Customer segmentation using KMeans, DBSCAN, and PCA.
- Hybrid recommendation engine combining cluster-based logic with collaborative filtering.
- Synthetic purchase behavior simulation to mimic real-world interactions.
- Visual analysis of clusters, user personas, and product recommendations.

---

## 🧰 Technologies Used

- **Python**  
- **Google Colab / Jupyter Notebook**  
- **Libraries:**  
  - `pandas`, `numpy` – Data handling  
  - `matplotlib`, `seaborn` – Visualization  
  - `scikit-learn` – KMeans, DBSCAN, PCA  
  - `surprise` – Collaborative filtering (KNNBasic)

---

## 📊 Approach

### 1. Customer Segmentation
- Loaded and preprocessed customer demographic data (Age, Annual Income, Spending Score).
- Applied PCA for dimensionality reduction.
- Used KMeans and DBSCAN to create distinct customer clusters.
- Created persona profiles for each cluster.

### 2. Purchase Behavior Simulation
- Simulated product purchases based on customer cluster preferences.
- Constructed a user-item interaction matrix for recommendation modeling.

### 3. Hybrid Recommendation System
- Applied collaborative filtering using the `Surprise` library (KNNBasic).
- Recommended top-N products by combining filtering results with cluster-based product trends.

### 4. Visualization
- Visualized customer clusters using scatter plots.
- Displayed top products per cluster and demographic trends using Matplotlib.

---

## 📁 Project Structure

