# National Anthem Classifier

## Overview
This project classifies national anthems into clusters based on their linguistic and semantic features. The process involves text preprocessing, vectorization using TF-IDF, and clustering using K-Means. The results are visualized on a world map to showcase cluster groupings.

---

## Features
- Tokenization of national anthem texts.
- Stemming and stopword removal for efficient preprocessing.
- Calculation of TF-IDF scores to represent text numerically.
- Application of K-Means clustering to group anthems into clusters.
- Visualization of the clusters on a world map.

---

## Technologies Used
- **Python**: Programming language for the entire pipeline.
- **Libraries**:
  - `nltk` for text preprocessing.
  - `sklearn` for TF-IDF vectorization and K-Means clustering.
  - `pandas` for data manipulation.
  - `geopandas` and `matplotlib` for data visualization.
- **Data Source**: National anthem lyrics and country geo-data.

---

## Steps to Run the Project
1. **Preprocessing**:
   - Load the dataset of national anthems.
   - Perform tokenization, stemming, and stopword removal.
2. **TF-IDF Vectorization**:
   - Convert the text into a TF-IDF matrix.
3. **Clustering**:
   - Define the optimal number of clusters (e.g., 7).
   - Apply K-Means to group the anthems.
4. **Visualization**:
   - Map the clusters on a world map using `geopandas`.

---

## Requirements
- Python 3.8 or later
- Required libraries (install via pip):
  ```bash
  pip install pandas numpy nltk scikit-learn geopandas matplotlib

---
