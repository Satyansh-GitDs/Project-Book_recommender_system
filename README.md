# Project-Book_recommender_system
A Flask-based Book Recommendation System using Collaborative Filtering and Cosine Similarity.
# 📚 Book Recommender System

A Machine Learning-based Book Recommendation System built using Python, Flask, Pandas, NumPy and Collaborative Filtering.

## 🚀 Project Overview

This project recommends books to users based on their selected book. It uses Collaborative Filtering and Cosine Similarity to identify similar books based on user-rating patterns.

## ✨ Features

- Top 50 popular books.
- Book recommendation based on user input.
- Displays book titles, authors and cover images.
- Interactive web interface using Flask and Bootstrap.
- Collaborative Filtering recommendation algorithm.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Flask
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Algorithm:** Collaborative Filtering
- **Similarity Measure:** Cosine Similarity

## 📂 Project Structure

```text
Book_recommender_system/
│
├── templates/
│   ├── index.html
│   └── recommend.html
│
├── app.py
├── main.py
├── popular.pkl
├── pt.pkl
├── books.pkl
├── similarity_scores.pkl
├── requirements.txt
├── Procfile
└── README.md
```

## ⚙️ Installation and Setup

1. Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Navigate to the project directory:

```bash
cd Book_recommender_system
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the application:

```bash
python app.py
```

5. Open your browser:

```text
http://127.0.0.1:5000/
```

## 🧠 Recommendation Approach

The system uses Item-Based Collaborative Filtering.

Cosine Similarity measures the similarity between books based on user-rating patterns and identifies the five most similar books.

## 👨‍💻 Author

**Satyansh Singh**

M.Tech – Data Science
