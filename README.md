# Manual TF-IDF vs Sklearn Vectorizers

This project demonstrates how to calculate TF-IDF manually using Python and compares the results with `CountVectorizer` and `TfidfVectorizer` from scikit-learn.

## 📘 Corpus
```
corpus = [
    'the sun is a star',
    'the moon is a satellite',
    'the sun and moon are celestial bodies'
]
```

## ✅ Files
- `manual_tfidf_vs_sklearn.ipynb`: Jupyter Notebook with code and explanation
- `README.md`: Summary of what this project does

## 🧠 Key Learnings
- **TF (Term Frequency)** measures how often a word appears in a document.
- **IDF (Inverse Document Frequency)** reduces the score of common words.
- Words like `"the"` have lower scores in TF-IDF because they appear in all documents and do not help distinguish them.
- TF-IDF is a more meaningful way to convert text into numbers for NLP tasks.

## 📊 Tools Used
- Python
- pandas
- scikit-learn
- math (for logarithm)

This notebook is written in a simple way, ideal for beginners in NLP or first-year BTech students.
