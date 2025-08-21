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
1. Load the movie dataset. (from kaggle tmdb top 5000 movies dataset)
2. Clean and preprocess the data.
3. Combine features like genres, keywords, and descriptions.
4. Calculate similarity scores between movies.
5. Return top N similar movies.


## 🚀 Project 2: Handwritten Digit Recognition 

### 📖 Description
This project implements a machine learning model to classify images of handwritten digits (0-9). The model is trained on the sklear.datasets. It uses a classification algorithm like Random Forest to identify the digits.

### 🛠 Technology Used
- Scikit-learn
- NumPy
- Matplotlib

### ⚙️ How it Works
1.  Data Loading: The script loads the MNIST dataset, which consists of thousands of 28x28 pixel images of handwritten digits and their corresponding labels.
2.  Data Preprocessing: The pixel values of the images are normalized (scaled) to a range between 0 and 1. This helps the model learn more effectively.
3.  Model Training: The dataset is split into a training set and a testing set. A classifier model learns the underlying patterns from the training images and their labels.
4.  Evaluation & Visualization: The trained model's performance is evaluated on the unseen test set. The script then displays a sample of the test images, showing the model's prediction alongside the actual digit for comparison.


### ▶️ Usage
```bash
# Clone repository
git clone https://github.com/Likhith257/Machine_Learning_Python_Project_IBM_Internship.git

# Navigate to folder
cd Machine_Learning_Python_Project
```
