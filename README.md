# 🎬 Netflix Content Classification & Recommendation System

An **AI-powered system** that classifies Netflix titles (Movie vs. TV Show) and recommends similar content using both **TF-IDF** and **Transformer-based semantic models**.  
Built with **Python, scikit-learn, Sentence Transformers, and Gradio** for an interactive UI.  

---

## 📌 Project Overview
OTT platforms like Netflix have thousands of titles, making it challenging for users to discover relevant content.  
This project aims to:
- Automatically **classify Netflix titles** as *Movie* or *TV Show* using ML models.
- Provide **intelligent recommendations** using both keyword-based and semantic similarity.
- Deliver an **interactive UI** for end users and stakeholders.

---

## 🚀 Features
- **Classification Module**
  - TF-IDF feature extraction.
  - Logistic Regression, SVM, and Naive Bayes classifiers.
  - Tuned with GridSearchCV for optimal performance.
- **Recommendation Engine**
  - **TF-IDF based recommender**: Keyword-level similarity.
  - **Semantic recommender**: Sentence-BERT (`all-MiniLM-L6-v2`) embeddings for context-aware recommendations.
- **Visualization**
  - Distribution of Movies vs TV Shows.
  - Release year trends.
  - Genre and country analytics.
  - Confusion matrices and classification reports.
- **Interactive UI**
  - Built with Gradio.
  - Two Tabs: 
    1. Classification (predict Movie/TV Show).
    2. Recommendations (TF-IDF & Semantic suggestions).

---

## 🛠️ Tech Stack
- **Languages & Libraries**: Python, Pandas, NumPy, Matplotlib, Seaborn
- **ML/NLP**: scikit-learn, Sentence-Transformers
- **Deployment**: Gradio
- **Dataset**: [Netflix Titles Dataset (Kaggle)](https://www.kaggle.com/datasets/venkateshsuvarna27/netflix-title)

---
