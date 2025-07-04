# Task 8: Clustering with K-Means

## 🧠 Objective
Apply K-Means Clustering to segment customers based on demographics and behavior.

## 🛠️ Tools Used
- Scikit-learn
- Pandas
- Matplotlib & Seaborn

## 📊 Dataset Overview
**Features**:
- Gender (encoded)
- Age
- Annual Income (in thousands)
- Spending Score (1–100)

## 🧪 Steps Performed
1. Encoded categorical features (Gender).
2. Applied Elbow Method to determine optimal number of clusters.
3. Used KMeans to assign cluster labels.
4. Visualized clusters using `Spending Score` vs `Annual Income`.
5. Evaluated clustering using Silhouette Score.

## 📈 Results
- Number of clusters (K): 3 (example)
- Silhouette Score: ~0.54 (varies by dataset)
- Clear separation of customer groups observed.

## 📌 Insight
K-Means clustering effectively groups customers by spending patterns and income, enabling targeted marketing strategies.

OUTPUT

![Screenshot 2025-07-04 100917](https://github.com/user-attachments/assets/c16b6b96-345e-46ce-8019-b13a2487ee13)

![Screenshot 2025-07-04 100954](https://github.com/user-attachments/assets/d5f83bd8-b792-45ed-80a0-ce436a48df68)
