# 🎯 Customer Segmentation using K-Means Clustering

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Scikit--Learn-1.4.2-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Project-Type-ML%20Project-ff69b4?style=flat-square" />
  <img src="https://img.shields.io/badge/Clustering-KMeans-yellowgreen?style=flat-square" />
</p>

---

## 🧠 Project Overview

Customer segmentation is the process of dividing customers into groups based on common characteristics so companies can market to each group effectively and appropriately. In this project, I used **K-Means Clustering** to segment customers based on their **Annual Income** and **Spending Score** using the [Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial).

---

## 📌 Key Features

- 🎯 Identified customer clusters using **unsupervised learning (K-Means)**
- 📊 Visualized clusters in 2D using **scatter plots**
- 📈 Used **Elbow Method** to determine optimal number of clusters
- 🛒 Useful insights for targeted marketing strategies

---

## 📂 Folder Structure


---

## 📉 Data Used

- **Dataset Name**: Mall Customers Dataset
- **Attributes**:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

---

## 🛠 Tech Stack

| Tool          | Usage                          |
|---------------|--------------------------------|
| `Python`      | Programming language           |
| `Pandas`      | Data manipulation              |
| `Matplotlib`  | Data visualization             |
| `Seaborn`     | Enhanced visualization         |
| `Scikit-Learn`| KMeans clustering & modeling   |

---

## 📊 Visualizations

<p align="center">
  <img src="notebook/kmeans-cluster-output.png" alt="KMeans Cluster" width="600">
</p>

---

## 📌 Insights from Clustering

- Cluster 1: High income, low spenders → potential premium customers
- Cluster 2: Low income, high spenders → impulsive buyers
- Cluster 3: Balanced income & spend → average customers
- Cluster 4: High income, high spend → target for loyalty programs
- Cluster 5: Low income, low spend → low priority

---

## ▶️ How to Run the Project

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation.git
   cd customer-segmentation
