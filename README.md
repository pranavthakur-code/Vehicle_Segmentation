# 🚗 Vehicle Segmentation using K-Means Clustering

## 📌 Project Overview

This project focuses on grouping vehicles into meaningful clusters using **unsupervised learning (K-Means Clustering)**.
The goal is to identify patterns such as fuel-efficient and high-performance vehicles without using labeled data.

---

## 📊 Dataset

* Source: The dataset is taken from an open-source repository:

🔗 [View Dataset](https://raw.githubusercontent.com/mwaskom/seaborn-data/master/mpg.csv)

The dataset is loaded directly using a URL for better reproducibility.

* Features include:

  * MPG (fuel efficiency)
  * Cylinders
  * Horsepower
  * Weight
  * Acceleration
  * Origin

---

## 🛠️ Steps Performed

### 1. Data Cleaning

* Handled missing values in horsepower using **median**
* Checked for duplicates

### 2. Exploratory Data Analysis (EDA)

* Distribution of MPG
* Cylinders vs MPG
* Origin vs MPG
* Observed trends and outliers

### 3. Feature Scaling

* Used **StandardScaler** to normalize data

### 4. Model Building

* Applied **K-Means Clustering**
* Used:

  * Elbow Method
  * Silhouette Score

### 5. Model Tuning

* Tested multiple values of K
* Selected optimal K based on silhouette score

### 6. Visualization

* Used **PCA** to reduce dimensions and visualize clusters

---

## 📈 Results

* Optimal number of clusters: **2**
* Silhouette Score: ~0.48
* Clusters identified:

  * **Cluster 0**: Fuel-efficient vehicles
  * **Cluster 1**: High-performance vehicles

---

## 📌 Conclusion

The model successfully grouped vehicles into meaningful categories.
This can be useful for:

* Market segmentation
* Product analysis
* Customer targeting

---

## 🚀 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn

---

## 👤 Author

Pranav Thakur
