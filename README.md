# 🎬 Movie Recommendation System

A Machine Learning based web application that recommends movies similar to a selected movie using content-based filtering techniques.  
The system analyzes movie features and calculates similarity between movies to suggest relevant recommendations.

The application is built with **Python and Streamlit** and deployed on **Hugging Face Spaces** for live interaction.

---

## 🚀 Live Demo

🔗 Hugging Face App  
https://huggingface.co/spaces/anandsinghcyber/Movie-Recommendation-system

📊 Kaggle Notebook  
https://www.kaggle.com/code/anandsinghchauhan077/movie-recommendation-system

---

## 🧠 Project Overview

The **Movie Recommendation System** suggests movies based on similarity with the selected movie.  
It uses **content-based filtering** and **cosine similarity** to recommend movies with similar genres, keywords, and features.

Users can select a movie from the list and the system will display recommended movies instantly.

This project demonstrates a complete **Machine Learning pipeline**, including:

- Data preprocessing
- Feature extraction
- Similarity calculation
- Model building
- Web app deployment

---

## ✨ Features

- Recommend similar movies instantly
- Content-based recommendation algorithm
- Interactive **Streamlit web interface**
- Fast movie similarity search
- Deployed on **Hugging Face Spaces**

---

## 🛠 Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Streamlit**
- **TMDB API**
- **Jupyter Notebook**

---

## 📂 Project Structure
movie-recommendation-system
│
├── app.py # Streamlit web application

├── movie-recommendation.ipynb # Model training notebook

├── movies.pkl # Movie dataset

├── similarity.pkl # Cosine similarity matrix

├── README.md # Project documentation



---

## 🔍 How It Works

1. The movie dataset is loaded and cleaned.
2. Important features like genres, keywords, cast, and overview are combined.
3. Text features are converted into numerical vectors.
4. Cosine similarity is used to calculate similarity between movies.
5. When a user selects a movie, the system returns the top recommended similar movies.

---

## ⚙️ Installation

Clone the repository:

```bash id="mrs02"
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system

Install dependencies:

pip install -r requirements.txt

Run the Streamlit app:

streamlit run app.py

