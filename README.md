# 🎬 Movie Recommender System

This project is a **content-based movie recommendation system** built using Python. It takes a movie selected by the user and recommends similar movies based on features like genre, keywords, cast, director, and more. The system is implemented using a Jupyter Notebook and leverages NLP and machine learning techniques.

---

## 📁 Project Structure

```
📦 movie-recommender/
 ┣ 📓 movie recommender.ipynb
 ┣ 📄 README.md
 ┗ 📂 data/
     ┗ movies.csv (if used)
```

---

## 🔧 Technologies Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- (Optional) NLTK / Regex for text cleaning

---

## 🧠 Features

- ✅ Recommends movies similar to a given movie
- ✅ Uses text-based similarity (genre, keywords, cast, etc.)
- ✅ Vectorization using `CountVectorizer` or `TfidfVectorizer`
- ✅ Measures similarity using cosine similarity
- ✅ Easy-to-understand code in a step-by-step notebook format

---

## ⚙️ How It Works

1. **Data Preprocessing:** Merge genres, keywords, cast, director into a single string per movie.
2. **Text Vectorization:** Convert text to vectors using `CountVectorizer` or `TfidfVectorizer`.
3. **Similarity Matrix:** Calculate cosine similarity between all movies.
4. **Recommendation:** Retrieve top N similar movies for the input title.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/jatingulia27/movie-recommendtion-system.git
cd movie-recommendtion-system
```

### 2. (Optional) Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

> If `requirements.txt` is missing, install manually:
```bash
pip install numpy pandas scikit-learn jupyter
```

### 4. Launch the Notebook

```bash
jupyter notebook
```

Open `movie recommender.ipynb` and run the cells one by one.

---

## 📸 Example Output

```
Input Movie: "Inception"
Recommended:
1. Interstellar
2. The Prestige
3. The Matrix
4. Shutter Island
5. Memento
```

---

## 📂 Dataset

If you’re using an external dataset (like TMDB), include the source:

- Dataset: [TMDB 5000 Movie Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata)
- License: As per dataset's original license (Kaggle)

---


## 📃 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---


## ⭐ Support This Project

- 🌟 Star this repository
- 🧠 Suggest ideas
- 🔧 Report issues
- 🤝 Contribute!

---

## 🔮 Future Plans

- Add collaborative filtering
- Streamlit or Flask web app version
- Real-time API connection (TMDB)
- User login and profile-based recommendations
