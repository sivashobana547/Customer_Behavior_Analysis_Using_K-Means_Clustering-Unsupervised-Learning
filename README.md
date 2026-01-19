# Customer Segmentation using K-Means Clustering

This project demonstrates how **K-Means clustering**, an unsupervised machine learning algorithm, can be used to segment customers based on their purchasing behavior.

The model is built using the popular **Mall Customers Dataset**, which contains information such as age, annual income, and spending score. The goal is to identify meaningful customer groups that can help businesses understand their customers better.

---

## 📊 Dataset

The dataset contains the following features:

- Customer ID  
- Age  
- Annual Income (k$)  
- Spending Score (1–100)

This dataset is commonly used to explain customer segmentation in machine learning.

---

## ⚙️ Approach

1. Loaded and explored the dataset
2. Selected relevant features for clustering
3. Applied **K-Means clustering**
4. Used the **Elbow Method** to find the optimal number of clusters
5. Visualized customer segments using scatter plots

---

## 🧠 Algorithm Used

- **K-Means Clustering**
  - Unsupervised learning algorithm
  - Groups customers based on similarity
  - Uses distance metrics to form clusters

---

## 📈 Results

The clustering algorithm successfully grouped customers into distinct segments such as:
- High income, high spending customers
- Low income, low spending customers
- Budget-conscious customers
- Potential target customers

These insights can be useful for **marketing strategies and business decision-making**.

---

## 🛠️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 🚀 How to Run the Project

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/repository-name.git
   
2.Install the required libraries

    pip install -r requirements.txt
    
3.Run the notebook or Python script
