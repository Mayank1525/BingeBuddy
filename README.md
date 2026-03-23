# 🎬 BingeBuddy – Movie Recommendation System

## 🚀 Overview

**BingeBuddy** is a content-based movie recommendation system that helps users discover movies based on their preferences. It uses machine learning techniques to analyze movie metadata and suggest similar movies through an interactive Streamlit web application.

---

## 🌐 Live Demo

👉 [https://bingebuddy-mayo15250609.streamlit.app/](https://bingebuddy-mayo15250609.streamlit.app/)

---

## ✨ Features

* 🔍 Search for movies
* 🎯 Get top 5 similar movie recommendations
* 🖼️ Fetch movie posters using TMDB API
* ⚡ Fast and interactive UI built with Streamlit
* 📊 Content-based filtering using cosine similarity

---

## 🛠️ Tech Stack

### 👨‍💻 Programming Languages

* Python

### 🤖 Machine Learning

* Pandas
* NumPy
* Scikit-learn
* Cosine Similarity
* TF-IDF / Count Vectorization

### 🌐 Web Development

* Streamlit

---

## 🧠 How It Works

1. Movie dataset is preprocessed (genres, keywords, cast, crew)
2. Important features are combined into a single text column
3. Text is vectorized using **CountVectorizer / TF-IDF**
4. **Cosine similarity** is calculated between movies
5. Based on selected movie, top similar movies are recommended

---

## 📂 Project Structure

```bash
BingeBuddy/
│
├── .devcontainer/               # Dev container configuration
├── .idea/                      # IDE configuration files
│
├── Movie-recommend-system.ipynb # Model building notebook
├── app.py                      # Streamlit frontend application
│
├── movie_dict.pkl              # Movie dictionary data
├── movies.pkl                  # Movie dataset
├── movies_dict.pkl             # Processed movie data
├── similarity_small.pkl        # Similarity matrix
│
├── requirements.txt            # Project dependencies
├── README.md                   # Project documentation
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Mayank1525/BingeBuddy.git
cd BingeBuddy
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
streamlit run app.py
```

---

## ⚠️ Disclaimer

This project is developed for educational purposes only.
It does not host or stream any copyrighted content.
It only recommends movies using publicly available metadata.

---

## 🚀 Future Enhancements

* 🔎 Auto-suggestion search bar
* 🎭 Genre-based filtering
* ⭐ Ratings and reviews integration
* ❤️ Watchlist functionality
* 🤖 Hybrid recommendation system (content + collaborative filtering)

---

## 👨‍🎓 Author

**Mayank Vishwakarma**
🔗 GitHub: [https://github.com/Mayank1525](https://github.com/Mayank1525)

* Aspiring Software Engineer
* Skilled in Java, Python, Machine Learning, and MERN Stack

---

## ⭐ Support

If you found this project useful:

* Give it a ⭐ on GitHub
* Share it with others

---
