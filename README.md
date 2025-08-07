# 🎵 Music Genre Clustering using K-Means | Thaniya Internship

## 📌 Overview

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to group songs into different musical genres based on their **audio features**. The dataset used is a **Spotify dataset** (CSV format) containing various characteristics of songs such as tempo, energy, danceability, and loudness.

The entire analysis and clustering process is conducted in **Jupyter Notebook using Python**.

---

## ✨ Features

- ✅ **Unsupervised Learning**: Uses K-Means Clustering to group songs without predefined labels.
- ✅ **Feature-Based Clustering**: Songs are grouped based on attributes like **tempo**, **loudness**, **danceability**, **valence**, and **energy**.
- ✅ **Data Visualization**: Includes informative visualizations using **Matplotlib** and **Seaborn**.
- ✅ **Real-World Dataset**: Uses an actual Spotify dataset for authentic audio feature analysis.
- ✅ **Jupyter Notebook**: Complete implementation and results in a single notebook for reproducibility and ease of understanding.

---

## 📂 Dataset: Spotify Audio Features

Each song in the dataset includes features like:

- 🎵 Danceability
- ⚡ Energy
- 🔊 Loudness
- 🕺 Tempo
- 😄 Valence (positiveness of a track)
- 🎻 Instrumentalness
- 🗣️ Speechiness (presence of spoken words)

These features help group songs into **clusters** of similar characteristics, revealing hidden structures in musical data.

---

## 🧪 Programming Languages & Libraries

- **Python** – Core programming language
- **Pandas & NumPy** – For data manipulation and analysis
- **Matplotlib & Seaborn** – For data visualization
- **Jupyter Notebook** – Development environment

---

## 📊 Results & Analysis

- 🎯 The **K-Means model** groups songs into clusters based on their musical attributes.
- 🎧 Songs with high tempo and energy often clustered together.
- 🎶 Songs with lower danceability or more instrumental were grouped separately.
- 📈 Visualization of clusters helped identify patterns between song features and inferred genres.

---

## ⚠️ Challenges Faced

1. **Choosing the Right Number of Clusters (k)**  
   - Used **Elbow Method** to determine optimal value of `k`.
   - Initially misleading due to overlapping clusters; required multiple trials.

2. **Feature Scaling**  
   - Had to apply **StandardScaler** to normalize features like tempo and loudness, as they were on different scales.

3. **Interpreting Clusters Without Labels**  
   - Since K-Means is unsupervised, no predefined genre labels exist.
   - Relied on intuition and visual patterns to name or interpret clusters.

4. **Handling Outliers**  
   - Some songs had extreme values which skewed the centroids.
   - Preprocessed and removed outliers using IQR and visual inspection.

5. **Visualizing High-Dimensional Data**  
   - Difficulty in visualizing more than 2 features.
   - Used **PCA** and pairplots to understand relationships between features.

---

## 💼 How to Prepare for Interviews (Project-Based)

If you plan to talk about this project in interviews, focus on:

1. **Problem Understanding**  
   - Be clear about why K-Means was chosen over supervised learning.
   - Explain what unsupervised learning is and where it fits.

2. **Algorithm Concepts**  
   - Explain the working of K-Means: centroid selection, distance measurement (Euclidean), iterative updates.

3. **Why This Project?**  
   - Highlight real-world use cases: music recommendation engines, genre-based playlisting, Spotify-like personalization.

4. **Technical Implementation**  
   - Describe preprocessing: null value handling, feature scaling.
   - Mention how you selected `k` using the Elbow method.

5. **Visualization and Interpretation**  
   - Talk about challenges in labeling the clusters.
   - Explain how visual plots helped you understand the genre groupings.

6. **Future Scope Awareness**  
   - Show you understand the limitations and scope for improvement (see below).

---

## 🚀 Future Enhancements

- 🔹 Improve clustering using **Principal Component Analysis (PCA)** for dimensionality reduction.
- 🔹 Explore **Hierarchical Clustering** or **DBSCAN** for better handling of noise/outliers.
- 🔹 Integrate **Spotify API** to fetch real-time song features.
- 🔹 Add interactive dashboards using **Plotly** or **Streamlit**.

---

## 🏁 Conclusion

This project successfully demonstrates how **unsupervised machine learning** can be used for music genre clustering using **K-Means**. By leveraging real-world **Spotify audio features**, the project delivers meaningful insights into music structure and genre segmentation.

It builds a strong foundation for future **AI-powered recommendation systems** and shows practical use of clustering in entertainment tech.

---
