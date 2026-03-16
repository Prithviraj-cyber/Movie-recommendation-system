# 🎬 Movie Recommendation System

A Machine Learning based web application that recommends movies similar to a selected movie using **content-based filtering** and **cosine similarity**.

The system analyzes movie metadata such as genres, keywords, cast, and overview to suggest relevant movies.

The application is built using **Python and Streamlit** and deployed on **Hugging Face Spaces** for live interaction.

---

## 🚀 Live Demo

🔗 Hugging Face App  
https://huggingface.co/spaces/anandsinghcyber/Movie-Recommendation-system

📊 Kaggle Notebook  
https://www.kaggle.com/code/anandsinghchauhan077/movie-recommendation-system

---

## 🧠 Project Overview

The **Movie Recommendation System** suggests movies similar to the one selected by the user.

It works by analyzing movie features and calculating similarity between movies using **cosine similarity**.

The system processes movie metadata and returns a list of recommended movies with similar characteristics.

This project demonstrates an **end-to-end machine learning workflow**, including:

- Data preprocessing
- Feature engineering
- Model building
- Similarity computation
- Streamlit web app deployment

---

## ✨ Features

- Recommend movies based on similarity
- Content-based recommendation algorithm
- Interactive **Streamlit web application**
- Fast movie similarity search
- Deployed on **Hugging Face Spaces**

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Jupyter Notebook

---

## 📂 Project Structure
movie-recommendation-system
│
├── app.py # Streamlit web application

├── movie-recommender.ipynb # Model training notebook

├── movies.pkl # Processed movie dataset

├── tmdb_5000_movies.csv # Original movie dataset

├── tmdb_5000_credits.csv # Movie credits dataset

├── README.md # Project documentation
│
├── .idea # IDE configuration files

├── venv # Virtual environment

└── .ipynb_checkpoints # Notebook checkpoints


---

## 🔍 How It Works

1. The TMDB movie dataset is loaded and cleaned.
2. Important features such as genres, keywords, cast, and overview are combined.
3. Text features are converted into numerical vectors.
4. Cosine similarity is used to compute similarity between movies.
5. When a user selects a movie, the system returns the most similar movies.

---

## ⚙️ Installation

Clone the repository:

```bash id="mrv12"
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system

Install dependencies:
pip install -r requirements.txt

Run the Streamlit app:
streamlit run app.py

