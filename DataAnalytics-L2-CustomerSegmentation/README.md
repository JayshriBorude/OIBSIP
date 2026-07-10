# 🛍️ Customer Segmentation Analysis using K-Means Clustering

## 📌 Project Overview

Customer segmentation is a powerful data analytics technique that groups customers based on their purchasing behavior. Businesses use these customer segments to design personalized marketing strategies, improve customer retention, and maximize revenue.

This project performs **Customer Segmentation** using the **K-Means Clustering** algorithm on an Online Retail dataset. Customer behavior is analyzed using **RFM (Recency, Frequency, Monetary)** analysis to identify different customer groups.

---

## 🎯 Objective

- Load and preprocess customer transaction data.
- Handle missing values and inconsistent records.
- Perform Exploratory Data Analysis (EDA).
- Generate RFM (Recency, Frequency, Monetary) features.
- Standardize the data using StandardScaler.
- Apply K-Means clustering.
- Determine the optimal number of clusters using the Elbow Method.
- Visualize customer segments.
- Profile each customer cluster.
- Provide business recommendations for each customer segment.

---

## 📂 Dataset

**Dataset:** Online Retail Dataset

The dataset contains transactional records of an online retail store including:

- Invoice Number
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📚 Project Workflow

### 1️⃣ Data Loading

- Import dataset
- Display dataset structure
- Check data types

### 2️⃣ Data Cleaning

- Remove missing Customer IDs
- Remove cancelled transactions
- Remove invalid Quantity and Unit Price values
- Handle duplicate records

### 3️⃣ Exploratory Data Analysis (EDA)

- Dataset overview
- Missing value analysis
- Descriptive statistics

### 4️⃣ Feature Engineering

Created RFM Features:

- **Recency** → Days since last purchase
- **Frequency** → Number of purchases
- **Monetary** → Total amount spent

### 5️⃣ Data Standardization

Applied **StandardScaler** to normalize RFM features before clustering.

### 6️⃣ K-Means Clustering

Applied K-Means algorithm to segment customers into different groups.

### 7️⃣ Elbow Method

Used the Elbow Method to determine the optimal number of clusters.

**Optimal Number of Clusters (K): 3**

### 8️⃣ Cluster Visualization

Visualized customer segments using:

- Recency vs Monetary Scatter Plot
- Frequency vs Monetary Scatter Plot
- Customer Count Bar Chart

### 9️⃣ Customer Profiling

Calculated average values of:

- Recency
- Frequency
- Monetary

for each customer cluster.

---

## 📊 Customer Segments

### 🟢 Cluster 0 – Regular Customers

Characteristics:

- Moderate spending
- Moderate purchase frequency
- Recent purchases

Recommendation:

- Loyalty rewards
- Personalized product recommendations
- Cross-selling offers

---

### 🟡 Cluster 1 – Inactive Customers

Characteristics:

- Long time since last purchase
- Low purchase frequency
- Low spending

Recommendation:

- Re-engagement campaigns
- Discount coupons
- Reminder emails

---

### 🔴 Cluster 2 – VIP Customers

Characteristics:

- Very high spending
- Frequent purchases
- Most valuable customers

Recommendation:

- Premium membership
- Exclusive offers
- Early product access
- VIP loyalty programs

---

## 📈 Key Results

- Successfully performed customer segmentation using K-Means.
- Identified three distinct customer groups.
- Generated meaningful business insights for targeted marketing.
- Visualized customer behavior through multiple charts.

---

## 📸 Output Screenshots

Add screenshots of the following outputs inside the **images/** folder:

- Dataset Overview
- Elbow Method
- Customer Count Bar Chart
- Recency vs Monetary Scatter Plot
- Frequency vs Monetary Scatter Plot

Example:

```
images/
│
├── elbow_method.png
├── cluster_distribution.png
├── recency_vs_monetary.png
└── frequency_vs_monetary.png
```

---

## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone <repository-url>
```

2. Navigate to the project folder.

```bash
cd DataAnalytics-L2-CustomerSegmentation
```

3. Install dependencies.

```bash
pip install -r requirements.txt
```

4. Open the notebook.

```bash
jupyter notebook Customer_Segmentation.ipynb
```

Run all cells sequentially.

---

## 🎯 Learning Outcomes

- Customer Segmentation
- RFM Analysis
- Feature Engineering
- Data Standardization
- K-Means Clustering
- Elbow Method
- Data Visualization
- Business Insight Generation

---

## 👩‍💻 Author

**Jayshri Borude**

B.Tech Information Technology

Sanjivani College of Engineering, Kopargaon

---

## 📄 License

This project is developed for educational and internship purposes under the Oasis Infobyte Data Analytics Internship.