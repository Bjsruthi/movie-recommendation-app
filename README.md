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


![<img width="1489" height="662" alt="image" src="https://github.com/user-attachments/assets/90d15de5-61f1-46eb-a864-7732cc959d1e" />](https://via.placeholder.com/900x400.png?text=Add+Screenshot+Here)  

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
