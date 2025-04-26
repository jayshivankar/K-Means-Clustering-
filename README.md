# K-Means Clustering on Customer Spending Data

This project demonstrates how to perform K-Means clustering on customer spending data to uncover potential patterns or segments among customers based on their spending behavior.

## 📁 Dataset

The dataset used is [`Cust_Spend_Data.csv`](./Cust_Spend_Data.csv), which contains anonymized records of customer spending behavior.

### Sample Columns:
- `CustomerID`: Unique ID for each customer
- `Age`: Age of the customer
- `Annual_Income`: Yearly income of the customer
- `Spending_Score`: A score assigned based on spending habits

## ⚙️ Methodology

1. **Data Preprocessing**
   - Load and inspect the dataset
   - Handle missing values (if any)
   - Normalize/scale features as necessary

2. **K-Means Clustering**
   - Determine optimal number of clusters using the Elbow Method
   - Fit K-Means model
   - Visualize clusters

3. **Results**
   - Display cluster centers
   - Visualize clusters using 2D or 3D plots

## 📊 Visualizations

- Elbow curve to determine optimal clusters
- Clustered scatter plot of customers by key features
- Optional: PCA or t-SNE for dimensionality reduction

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/customer-kmeans-clustering.git
   cd customer-kmeans-clustering
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the analysis script:
   ```bash
   python kmeans_clustering.py
   ```

## 📌 Notes

- The K-means algorithm may produce different clusters depending on the initialization.
- Preprocessing and feature selection heavily impact clustering quality.


