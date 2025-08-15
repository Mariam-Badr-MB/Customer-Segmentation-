# Mall Customers Clustering Project

## 🔍 Project Overview
This project aims to **segment mall customers** based on their **Annual Income** and **Spending Score** using **K-Means clustering**.  
The goal is to help the business understand customer behavior and design **targeted marketing strategies**.

---

## 📂 Dataset
- **Source:** [Mall Customer Dataset - Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Features Used:**
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 Steps Performed

### 1️⃣ Define the Problem
Segment customers into distinct groups based on income and spending behavior to improve marketing strategies.

### 2️⃣ Load and Explore Data
- Loaded the dataset
- Selected relevant features
- Performed **exploratory data analysis (EDA)**

### 3️⃣ Scale Features
- Applied **StandardScaler** to normalize features for clustering.

### 4️⃣ Determine Optimal Number of Clusters
- Used **Elbow Method (Inertia)** and **Silhouette Score** to select the best `k`.

### 5️⃣ Apply K-Means & Visualize Clusters
- Fitted **K-Means** with the optimal number of clusters.
- Visualized customer segments in a **2D scatter plot**.

### 6️⃣ Analyze Cluster Characteristics
- Calculated **average spending per cluster**.
- Identified groups like:
  - High income & high spenders (VIP customers)
  - Low income & high spenders
  - Low income & low spenders, etc.

### 7️⃣ Save Predictions
- Added a `Cluster` column to the dataset.
- Saved the results as `Mall_Customers_Clustered.csv`.

---

## 📊 Visualizations
- Scatter plots of customer distribution
- Clustered segments with different colors
- Bar plot of average spending per cluster

---

## 📈 Insights
- **High spenders** can be targeted with premium offers.
- **Low spenders** may need loyalty programs or promotions.
- Customer segmentation helps in **personalized marketing campaigns**.

---

## 👩‍💻 Author

**Mariam Badr**  
Faculty of Computers & Artificial Intelligence, Cairo University  
[GitHub](https://github.com/Mariam-Badr-MB) – [LinkedIn](https://www.linkedin.com/in/mariambadr13/)


## 🤝 Contributing
This project is **open for contributions ❤️**    
Feel free to:
- Suggest improvements
- Add new features or visualizations
- Extend the analysis with other clustering methods or datasets
- Collaborate on related projects  

Your contributions are **welcome** and highly appreciated to make this project even more useful for customer segmentation and marketing analysis.
