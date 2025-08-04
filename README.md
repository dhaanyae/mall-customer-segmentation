# Mall Customer Segmentation using KMeans Clustering

## 📌 Overview

This project focuses on **segmenting mall customers** into distinct groups based on their annual income and spending behavior using **KMeans Clustering**, an unsupervised machine learning algorithm.

The goal is to help mall managers and marketers understand different types of customers and tailor their strategies accordingly.

---

## 📊 Dataset

- **Source**: [Kaggle - Mall Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Features**:
  - `CustomerID` — Unique ID for each customer
  - `Gender` — Customer gender
  - `Age` — Customer age
  - `Annual Income (k$)` — Annual income in thousands
  - `Spending Score (1-100)` — Score assigned by the mall based on customer behavior

---

## 🛠️ Tools & Libraries

- Python 3
- Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn (for visualization)
- Scikit-learn (for clustering)

---

## 🧠 Techniques Used

### 1. **Data Preprocessing**
- Dropped non-numeric columns (e.g., `CustomerID`, `Gender`)
- Applied `StandardScaler` to normalize features

### 2. **Exploratory Data Analysis (EDA)**
- Visualized distributions of `Age`, `Income`, and `Spending Score`
- Analyzed relationships between features

### 3. **KMeans Clustering**
- Used the **Elbow Method** to determine optimal number of clusters (k)
- Applied KMeans and added the `Cluster` column to the dataset
- Plotted customer groups using Seaborn scatterplots

### 4. **Hierarchical Clustering** *(Optional)*
- Built dendrogram to visualize cluster hierarchy
- Applied Agglomerative Clustering for comparison

---

## 📈 Results

- Customers were grouped into **5 clusters**
- Clear segmentation observed:
  - High income, high spending
  - Low income, high spending
  - Low income, low spending
  - Average income, average spending
- Cluster profiles help in designing targeted marketing strategies

---

## 📁 How to Use

1. Open the Colab notebook: `mall_segmentation.ipynb`
2. Upload the dataset file: `Mall_Customers.csv` (from Kaggle)
3. Run the cells sequentially
4. View plots, cluster results, and summary at the end

---

## ✅ Conclusion

This project demonstrates how unsupervised learning — specifically **KMeans Clustering** — can be used in real-world business contexts like retail customer analysis. Through data visualization and clustering, actionable business insights can be derived to improve customer retention and profitability.

---

## ✍️ Author

**Dhaanya Eday**  
B.Tech CSE
