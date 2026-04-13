# 🎬 Hybrid Movie Recommender System

## 🚀 Project Overview
This project builds a complete movie recommendation system using the MovieLens 1M dataset.

The goal is to generate accurate and personalized movie recommendations by combining multiple machine learning and deep learning approaches.

---

## 🧠 Problem
Recommendation systems face several challenges:
- Sparse user-item interaction data  
- Cold-start problem  
- Non-linear user preferences  
- Limited performance when using a single model  

---

## ⚙️ Solution
A hybrid recommendation pipeline was developed to improve performance:

- Data preprocessing and interaction matrix creation  
- Collaborative Filtering using ALS  
- Neural Collaborative Filtering (NCF) using PyTorch  
- User clustering using K-Means  
- Content-based filtering using TF-IDF  
- Hybrid model combining multiple approaches  

---

## 📊 Results
- Users: 6,040  
- Movies: 3,706  
- Interaction Matrix: (6040 × 3706)  

- ALS RMSE: 3.71  
- NCF RMSE: 3.66  

---

## 📈 Key Insights
- Deep learning (NCF) captured complex user preferences better than ALS  
- Sparse data significantly affects recommendation quality  
- Hybrid models improve ranking performance over single models  
- Clustering helps generalize recommendations across similar users  

---

## 🧪 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- PyTorch  
- Implicit (ALS)  
- Matplotlib, Seaborn  

---

## ⚠️ Important Note
The NCF model is implemented as a baseline and can be further improved with proper training and tuning.

---

## 👩‍💻 Author
HindAlamrii
