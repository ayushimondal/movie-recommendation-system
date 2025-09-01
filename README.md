# 🎬 Movie Recommendation System  

This project is a **content-based Movie Recommendation System** built with **Python** and **Streamlit**, designed to help users discover movies similar to their favorites. It leverages the **TMDB 5000 Movie Dataset** for metadata and enriches the experience with **movie posters and details fetched dynamically using the TMDB API**. By applying **cosine similarity** on vectorized features (genres, cast, crew, keywords, etc.), the system delivers accurate and visually engaging recommendations through a simple, interactive web app.  

The project demonstrates the complete journey of building a recommendation system: **data collection, preprocessing, feature engineering, similarity modeling, and deployment**. Beyond just functionality, it highlights how data science can be combined with real-world APIs to create a seamless user experience.  

---

## ✨ Features  
- **Content-based recommendations** using cosine similarity  
- Powered by the **TMDB 5000 Movie Dataset**  
- **TMDB API integration** for fetching movie posters and additional metadata  
- **Streamlit web app** with an intuitive and responsive UI  
- End-to-end pipeline: data → preprocessing → model → deployment  

---

## 📌 Project Workflow  

1. **Introduction** → Define the goal of recommending similar movies.  
2. **Dataset Collection** → Use the **TMDB 5000 Movie Dataset** for movie metadata.  
3. **Preprocessing** → Clean and structure data, handle missing values, and prepare text features.  
4. **Vectorization** → Convert textual and categorical metadata into numerical vectors.  
5. **Cosine Similarity** → Measure similarity scores between movies.  
6. **Recommendation Function** → Return the top N most similar movies.  
7. **Poster Fetching** → Integrate **TMDB API** to display posters and movie details.  
8. **Streamlit Deployment** → Build an interactive UI for real-time recommendations.  

---

## 🚀 Tech Stack  

- **Python**  
- **Streamlit**  
- **Scikit-learn** (for vectorization & similarity)  
- **Pandas / NumPy** (for data preprocessing)  
- **TMDB 5000 Movie Dataset**  
- **TMDB API** (for posters & movie details)  

---

## 📂 Project Structure  

* `app.py` # Streamlit app script
* `movie-recommendation-system.ipynb` # Jupyter Notebook (EDA & model building)
* `README.md` # Project documentation

---

## 🚀 How to Run

1.  Clone the repository:
    ```bash
    git clone [https://github.com/ayushimondal/movie-recommendation-system.git](https://github.com/ayushimondal/movie-recommendation-system.git)
    cd movie-recommendation-system
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```
