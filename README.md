# Vision-Hunter
AI powered Modern Social media Trend Analyzer

> ⚠️ **Note:** This project is currently under development.

**Vision Hunter** is a full-stack web application powered by **Machine Learning and the MERN stack** that helps creators, marketers, and analysts uncover what makes content go viral.  
It analyzes real-world social media data, predicts engagement levels, and generates actionable insights to optimize content strategies.

---

## 🚀 Project Overview

In the digital era, understanding what drives *viral engagement* is a major challenge for brands and influencers.  
Vision Hunter uses **data-driven modeling** and **AI-powered analytics** to:

- Explore engagement patterns across platforms (TikTok, Instagram, YouTube, Twitter)
- Predict content engagement levels (High / Medium / Low)
- Visualize social media dynamics using interactive dashboards
- Provide AI-based recommendations for improving content performance

🧠 Machine Learning Core

The machine learning foundation of Vision Hunter is developed in Python using scikit-learn and XGBoost.  
It includes both **supervised** and **unsupervised** learning tasks.

### 🔍 Supervised Learning
- **Regression Models:** Predict continuous engagement metrics (`Views`, `Likes`, `Shares`, `Comments`)
- **Classification Models:** Predict categorical engagement level (`High`, `Medium`, `Low`)
- Models used:
  - Linear / Logistic Regression (baseline)
  - Random Forest
  - Gradient Boosting
  - XGBoost
- Model optimization using **KFold Cross Validation** and **GridSearchCV**

### 🧩 Unsupervised Learning
- **Dimensionality Reduction:** PCA, t-SNE, UMAP  
- **Clustering:** KMeans and DBSCAN for pattern discovery

### 📊 Feature Importance
Feature rankings identify which attributes drive engagement across platforms — such as likes/views ratio, platform type, and hashtag category.

---

## 💻 Full-Stack Web Application

The second phase of Vision Hunter integrates the ML models into an interactive web platform using the **MERN stack**.

### 🧱 Tech Stack

| Layer | Technology |
|--------|-------------|
| **Frontend** | React.js, Tailwind CSS, Chart.js / Recharts |
| **Backend** | Node.js, Express.js |
| **ML Service** | Python, Flask / FastAPI, scikit-learn, XGBoost |
| **Database** | MongoDB Atlas |
| **Deployment** | Docker, Render, Vercel, Railway |
