# Movie Recommendation System

deployed using streamlit:
https://movie-recommendation-system-xh29h5cljaasduvt5d3sqh.streamlit.app/

## Overview

A content-based Movie Recommendation System built using Python, Streamlit, and Natural Language Processing (NLP). The application recommends movies similar to a selected title by analyzing movie descriptions using TF-IDF vectorization and cosine similarity.

## Features

* Content-based movie recommendations
* Interactive Streamlit web application
* TF-IDF vectorization for text processing
* Cosine similarity-based recommendation engine
* Precomputed feature matrices for faster inference

## Tech Stack

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* Pickle

## Project Structure

```text
Movie-Recommendation-System/
├── app.py
├── main.py
├── movies.ipynb
├── movies_metadata.csv
├── df.pkl
├── indices.pkl
├── tfidf.pkl
├── tfidf_matrix.pkl
├── requirements.txt
├── runtime.txt
└── README.md
```

## How It Works

1. Load and preprocess the movie metadata.
2. Convert movie descriptions into TF-IDF feature vectors.
3. Compute similarity scores using cosine similarity.
4. Recommend movies most similar to the selected title through the Streamlit interface.

## Installation

```bash
git clone https://github.com/cyraemin/Movie-Recommendation-System.git
cd Movie-Recommendation-System
pip install -r requirements.txt
streamlit run app.py
```

## Acknowledgements

This project was built by following and learning from the **Sheryians AI School** tutorial on content-based movie recommendation systems. It was recreated independently for educational purposes to strengthen my understanding of NLP, TF-IDF vectorization, similarity-based recommendation systems, and Streamlit application development.

## License

This project is intended for educational and learning purposes.
