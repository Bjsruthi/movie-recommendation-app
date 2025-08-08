# 🎬 Movie Recommendation System  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)  
![TMDB](https://img.shields.io/badge/TMDB-API-green)  
![License](https://img.shields.io/badge/License-MIT-yellow)  

A **content-based movie recommendation system** built with **Python**, **Streamlit**, and **TMDB API**.  
It suggests similar movies based on **cosine similarity** of movie metadata, fetching real-time posters and details from TMDB.  

---

## ✨ Features  
✅ Content-based filtering using cosine similarity  
✅ Real-time movie posters & details from TMDB API  
✅ Interactive Streamlit web interface  
✅ Dropbox integration for automatic similarity data download  

---

## 📸 Demo Preview  

<img width="1258" height="664" alt="image" src="https://github.com/user-attachments/assets/3122d6de-57f5-4999-b761-9ed37d319f5a" />

---

## 🛠️ Tech Stack  
- **Python** (Pandas, Pickle, Requests)  
- **TMDB API** (for movie data & posters)  
- **Streamlit** (web app frontend)  

---

## 🚀 Getting Started  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
```
### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Add your TMDB API key
# Edit the fetch_poster function in app.py and replace with your key
```bash
api_key = "YOUR_API_KEY"
```
### 4️⃣ Run the Streamlit app
```bash
streamlit run app.py
```

---

## 🖥️ Usage

1. When the app launches in your browser, select a movie from the dropdown menu.  
2. Click the **"Recommend"** button.  
3. The app will display the top 5 most similar movies along with their posters and details fetched from TMDB.

---
