# 🎶 Music Analysis Notebook

**Music Analysis Notebook** is a repository that consolidates two independent **Data Science** and **Machine Learning** projects applied to the world of music, utilizing real datasets from Kaggle. The goal is to explore and model complex data regarding artist popularity and audio characteristics, using regression and classification.

---

## 🚀 Main Projects

This repository contains two complete analyses, each focusing on a distinct Machine Learning challenge:

| Project | Topic | Winning Model | Performance |
| :--- | :--- | :--- | :--- |
| **🎤 Artist Popularity** | Regression | **MLP Regressor** | $R^2$ of **0.7748** |
| **🎵 Genre Classification** | Classification | **MLP Classifier** | Accuracy of **75.85%** |

---

## 🧠 Details and Conclusions

### 1. 🎤 Artist Popularity Estimation (Regression)

This project focuses on predicting the number of listeners for an artist based on historical data from Last.fm.

* **📊 Dataset:** 'Music artists popularity' (Kaggle).
* **✨ Strategy:** Utilizing regression to estimate the continuous variable (number of listeners).
* **💡 Key Conclusion:** The **MLP Regressor** outperformed traditional models (Linear, SVR, Decision Tree), and it was crucial to note that **robust data filtering** (removal of outliers and nulls) was the determining factor for successful training.
* **File:** `artist_popularity.ipynb`

### 2. 🎵 Music Genre Classification

This project aims to classify music into 11 distinct genres based on its audio characteristics.

* **📊 Dataset:** 'Music Genre Classification' (Kaggle).
* **✨ Strategy:** Utilizing multiclass classification.
* **💡 Key Conclusion:** The **MLP Classifier** demonstrated the best learning capability, achieving **75.85% accuracy**. Feature analysis indicated that **energy** (`energy`) and **acousticness** (`acousticness`) are the most relevant characteristics for genre differentiation.
* **File:** `music_genre.ipynb`

---

## 🏗️ Repository Structure

```bash
.
├── artist_popularity.ipynb     # Notebook: Artist Popularity Estimation
├── music_genre.ipynb           # Notebook: Music Genre Classification
├── music_genre/
│   └── music_genre.csv         # Dataset for Genre Classification
├── artist_popularity/
│   └── artist_popularity.csv   # Dataset for Popularity Regretion
└── README.md

```

---

## 👤 Author
- **Artur Gomes Simão**

Credits to Dr. João Paulo Reus Rodrigues Leite
