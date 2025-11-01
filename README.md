# 🎬 Movie Recommendation System (Content-Based)

This project is a **Content-Based Movie Recommendation System** built using **Python**.  
It recommends movies similar to a selected title by analyzing movie metadata such as genres, keywords, cast, and crew.

---

## 🧠 How It Works
The system uses **Natural Language Processing (NLP)** and **cosine similarity** to measure how closely movies resemble each other based on textual features.

### Steps:
1. **Data Loading** — Reads the movie dataset using pandas.  
2. **Data Cleaning** — Handles missing values and parses text columns (genres, cast, etc.).  
3. **Text Preprocessing** — Uses stemming (via NLTK’s PorterStemmer) to normalize words.  
4. **Vectorization** — Converts text into numerical form using `CountVectorizer`.  
5. **Similarity Computation** — Applies `cosine_similarity` to find movies similar to a given one.  
6. **Recommendation** — Returns the top 5–10 similar movies.

---
