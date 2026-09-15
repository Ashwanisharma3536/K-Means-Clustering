# K-Means-Clustering
"An unsupervised machine learning project using K-Means Clustering to identify distinct customer segments based on annual income and spending scores."
# Customer Segmentation using K-Means Clustering

This repository contains a Data Science project focused on **Customer Segmentation** using the **K-Means Clustering** algorithm. The goal is to analyze mall customer data and group customers into distinct segments based on their shared behaviors (Annual Income and Spending Score) to help the marketing team design targeted business strategies.

## 📊 Dataset Overview
The dataset used is `Mall_Customers.csv`, which contains information about 200 customers. The primary features used for segmentation are:
* **Annual Income (k$)**: Annual income of the customer.
* **Spending Score (1-100)**: A score assigned by the mall based on customer behavior and spending nature.

## 🚀 Key Steps Covered
1. **Data Exploration**: Loading and understanding the distribution of features.
2. **Feature Selection**: Selecting optimal features (Income and Spending Score) for 2D visualization.
3. **The Elbow Method**: Determining the optimal number of clusters ($K$) using Within-Cluster-Sum-of-Squares (WCSS).
4. **Model Training**: Fitting the K-Means algorithm on the dataset with the optimal $K=5$.
5. **Cluster Visualization**: Plotting clusters along with their centroids for deep insights.
6. **Cluster Profiling**: Analyzing each customer segment to understand their financial and spending behavior.

## 📈 Customer Profiles & Business Strategy

Based on the final 5 clusters, the following customer segments were identified:

| Cluster | Segment Name | Income Group | Spending Score | Marketing/Business Strategy |
| :---: | :---: | :---: | :---: | :---: |
| **0** | **Standard** | Medium | Medium | Maintain engagement with regular offers and loyalty points. |
| **1** | **Target / VIP** | High | High | Target with premium brands, VIP club memberships, and exclusive luxury launches. |
| **2** | **Careless** | Low | High | Send alerts for limited-time fast-fashion flash sales and Buy-1-Get-1 offers. |
| **3** | **Sensible** | High | Low | Attract with high-value cashback deals, premium quality positioning, and membership perks. |
| **4** | **Careful** | Low | Low | Provide basic discounts on essential items and target via value-driven marketing. |

## 🛠️ Tech Stack & Libraries
* **Python 3**
* **Pandas**: For data manipulation.
* **NumPy**: For mathematical and array operations.
* **Matplotlib & Seaborn**: For plotting interactive and clean visualizations.
* **Scikit-Learn**: For implementing the K-Means Clustering model.

## ⚙️ How to Run This Project
1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python file to see the results.
