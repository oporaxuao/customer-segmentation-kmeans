# 🛍️ Customer Segmentation with K-Means Clustering

Unsupervised machine learning project to identify distinct customer profiles and enable personalized marketing strategies based on behavioral and financial data.

---

## 🎯 Business Objective

Retail and e-commerce teams often treat their entire customer base as a single audience, resulting in low ROI on marketing campaigns. This project solves that problem by grouping customers into homogeneous segments, allowing the business to tailor communication, offers, and retention strategies to each profile.

---

## 🗂️ Methodology

### 1. Exploratory Data Analysis (EDA)
- Analyzed the distribution of income and spending score across the customer base
- Identified correlations between demographic variables and purchasing behavior

### 2. Data Preprocessing
- Normalized features using `StandardScaler` to prevent scale bias in the distance-based algorithm
- Selected the most discriminating variables for clustering: **Annual Income** and **Spending Score**

### 3. Optimal Number of Clusters
Two complementary techniques were applied to define the ideal number of groups:
- **Elbow Method**: Identified the point of diminishing returns on inertia reduction
- **Silhouette Score**: Validated cluster cohesion; the final model with **5 clusters** achieved a score of **0.272**

### 4. K-Means Model
- Trained a K-Means model with `k=5`
- Mapped cluster centers to business personas for strategic interpretation

---

## 📊 Results — The 5 Customer Personas

| Cluster | Profile | Strategy |
|---|---|---|
| 0 — Stable | Older customers, stable income, moderate spending | Loyalty programs |
| 1 — Savers | High income, low spending frequency | Exclusivity and premium campaigns |
| 2 — Engaged | Young, mid-income, high purchase volume | Events and experiences |
| 3 — Premium | High income and high recurring spending | VIP services and networking |
| 4 — Trend-driven | Young, lower income, shopping-oriented | Discounts and trend content |

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn (K-Means, StandardScaler, Silhouette Score) |
| Environment | Jupyter Notebook |

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/oporaxuao/customer-segmentation-kmeans.git
cd customer-segmentation-kmeans

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Launch the notebook
jupyter notebook
```

---

## 👤 Author

**João Alfredo de Sousa Siqueira**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-oporaxuao-blue)](https://linkedin.com/in/oporaxuao)
[![GitHub](https://img.shields.io/badge/GitHub-oporaxuao-black)](https://github.com/oporaxuao)
