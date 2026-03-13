# Movie Recommendation System 🎬

A **Movie Recommendation System** built with **Python** using **TF-IDF** and **Cosine Similarity** to suggest movies based on their content similarity.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Technologies](#technologies)

---

## Overview
This project recommends movies to users based on the similarity of movie descriptions, genres, and keywords.  
It uses **content-based filtering**, transforming textual data into numerical vectors using **TF-IDF** and measuring similarity with **Cosine Similarity**.

---

## Features
- Finds the most similar movies to the one selected.
- Handles missing data in movie descriptions and other features.
- Easy to extend to larger datasets.
- Works entirely with Python and popular data libraries.

---

## Dataset
- The dataset should contain columns like:  
  `title`, `genres`, `keywords`, `cast`, `director`, `overview`, etc.
- Example: `movies.csv` placed in the `dataset/` folder.
- You can use any movie dataset (Kaggle has multiple options).

---

## Technologies
- **Pandas** – for data manipulation
- **Scikit-learn** – TF-IDF Vectorizer & Cosine Similarity
- **Jupyter Notebook** – interactive exploration
