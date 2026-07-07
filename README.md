# 🛍️ Customer Segmentation with Clustering

## 📌 Project Overview

This project performs customer segmentation using the Online Retail dataset. It applies RFM (Recency, Frequency, Monetary) analysis and machine learning clustering algorithms to identify different customer groups. The identified segments are analyzed to provide actionable marketing strategies that can help businesses improve customer engagement and increase revenue.

---

# 🎯 Objectives

The objectives of this project are:

- Load and clean the Online Retail dataset
- Perform RFM (Recency, Frequency, Monetary) feature engineering
- Apply K-Means clustering
- Apply DBSCAN clustering
- Find the optimal number of clusters using the Elbow Method
- Evaluate clustering using the Silhouette Score
- Profile each customer segment
- Suggest marketing strategies for each customer segment

---

# 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Jupyter Notebook

---

# 📂 Dataset

**Dataset Used:** Online Retail Dataset

The dataset contains retail transaction records with the following information:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

---

# 📁 Project Structure

```
VedGrow_DS_04/
│
├── Customer_Segmentation.ipynb
├── online_retail.csv
├── README.md
└── images/
    ├── rfm_distribution.png
    ├── elbow_method.png
    ├── silhouette_score.png
    ├── kmeans_clusters.png
    └── dbscan_clusters.png
```

---

# 📊 Analysis Performed

## 1. Data Cleaning

- Removed missing Customer IDs
- Removed duplicate records
- Removed cancelled orders
- Removed invalid Quantity and Unit Price values
- Converted Invoice Date into datetime format

## 2. Feature Engineering (RFM)

Created the following customer metrics:

- **Recency:** Number of days since the customer's last purchase
- **Frequency:** Number of unique purchases made by each customer
- **Monetary:** Total amount spent by each customer

---

## 3. K-Means Clustering

- Standardized the RFM features
- Used the Elbow Method to determine the optimal number of clusters
- Applied K-Means clustering to segment customers

---

## 4. DBSCAN Clustering

Applied the DBSCAN algorithm to identify customer groups based on density and detect noise/outlier customers.

---

## 5. Cluster Evaluation

Evaluated clustering performance using:

- Elbow Method
- Silhouette Score

---

# 📈 Visualizations

The project includes the following visualizations:

- RFM Feature Distribution
- Elbow Method Graph
- Silhouette Score Graph
- K-Means Cluster Visualization
- DBSCAN Cluster Visualization

---

# 📋 Cluster Profile Report

The customer segments were created based on Recency, Frequency, and Monetary values.

### Cluster 0
- Loyal customers
- Purchase frequently
- High spending

**Marketing Strategy:**
- Offer loyalty rewards
- Early access to new products
- Premium membership benefits

---

### Cluster 1
- High-value customers
- High monetary contribution

**Marketing Strategy:**
- VIP discounts
- Personalized product recommendations
- Exclusive offers

---

### Cluster 2
- New or occasional customers

**Marketing Strategy:**
- Welcome discounts
- Product recommendations
- Encourage repeat purchases

---

### Cluster 3
- Inactive customers

**Marketing Strategy:**
- Re-engagement campaigns
- Special coupons
- Email and SMS reminders

---

# 📌 Key Insights

- RFM analysis effectively differentiated customer purchasing behavior.
- K-Means clustering grouped customers into meaningful business segments.
- DBSCAN identified dense customer groups and potential outliers.
- The Elbow Method and Silhouette Score helped determine an appropriate number of clusters.
- Customer segmentation enables businesses to create targeted marketing campaigns and improve customer retention.

---

# ▶️ How to Run the Project

### Step 1

Clone the repository.

```bash
git clone <repository-link>
```

### Step 2

Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn notebook
```

### Step 3

Launch Jupyter Notebook.

```bash
jupyter notebook
```

### Step 4

Open:

```
Customer_Segmentation.ipynb
```

### Step 5

Run all notebook cells in sequence.

---

# 📤 Project Output

The project generates:

- RFM Analysis
- Elbow Method Graph
- Silhouette Score Graph
- K-Means Customer Segments
- DBSCAN Customer Segments
- Cluster Profile Summary
- Marketing Strategy Recommendations

All generated images are available in the **images** folder.

---

# 💡 Skills Demonstrated

- Data Cleaning
- Feature Engineering
- RFM Analysis
- Customer Segmentation
- Machine Learning
- K-Means Clustering
- DBSCAN Clustering
- Cluster Evaluation
- Data Visualization
- Business Analytics

---

# 👩‍💻 Author

**Swetha C**

Business Analytics Intern (VedGrow Internship)
