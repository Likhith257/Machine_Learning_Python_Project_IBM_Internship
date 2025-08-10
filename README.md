# 🎬 Movie Recommendation System & ✍️ Handwritten Digit Recognition

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Projects-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Overview
This repository contains **two machine learning projects**:

1. **Movie Recommendation System** – Suggests movies to users based on similarity in genres, descriptions, or ratings.
2. **Handwritten Digit Recognition** – Classifies handwritten digits (0–9) using deep learning.

---

## 🚀 Project 1: Movie Recommendation System

### 📖 Description
The **Movie Recommendation System** uses content-based filtering (Cosine Similarity) to recommend movies similar to a given one.  
It processes movie datasets, extracts features, and finds similar titles.

### 🛠 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Cosine Similarity

### ⚙️ How It Works
1. Load the movie dataset.
2. Clean and preprocess the data.
3. Combine features like genres, keywords, and descriptions.
4. Calculate similarity scores between movies.
5. Return top N similar movies.

### ▶️ Usage
```bash
# Clone repository
git clone https://github.com/yourusername/your-repo.git

# Navigate to folder
cd your-repo

# Run script
python movie_recommendation.py
