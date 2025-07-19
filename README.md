# 🎬 Cinemetrics

![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

Cinemetrics is a **Jupyter Notebook**–based toolkit for exploring and recommending IMDb’s Top 1000 movies. Dive into data cleaning, EDA, and a content-based recommendation engine—all in one notebook!

---

## 🔍 What’s Inside

- **Data Preprocessing**  
  - Handle missing values & outliers  
  - Normalize, scale & encode features  
- **Exploratory Data Analysis**  
  - Genre distributions & certificate associations  
  - Statistical tests (Chi-squared)  
- **Dimensionality Reduction**  
  - PCA for feature insights  
- **Content-Based Recommendations**  
  - Custom features:  
    - 🎯 Commercial Impact  
    - 🌟 Entertainment Quality  
    - 🏛 Cultural Significance  
    - 🧐 Critical Intensity  
    - ⭐ IMDb Rating  
    - 🎭 Genre one-hot vectors  
  - Cosine similarity → “If you liked X, you’ll love Y”  
- **Interactive Visuals**  
  - Plotly heatmaps, scatterplots & more  

---

## 🚀 Quick Start

1. **Clone the repo**  
   ```bash
   git clone https://github.com/bogdan-chis/cinemetrics.git
   cd cinemetrics
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**  
   ```bash
   jupyter notebook Cinemetrics.ipynb
   ```  
   - Execute all cells from top to bottom  
   - Play with the recommendation function:
     ```python
     recommend_movies("The Godfather", df, similarity_matrix, label_encoder, n=5)
     ```

---

## 📊 Features

- **Flexible Pipeline**: Swap in your own datasets or tweak preprocessing steps.  
- **Rich Visuals**: Static (matplotlib/seaborn) + interactive (Plotly).  
- **Extendable Recommender**: Add new features (e.g., runtime, director) in minutes.  

---

## 🛣️ Roadmap

- ✨ Web-app wrapper (Streamlit / Dash)  
- 🔄 Real-time API for live recommendations  
- 📈 Advanced NLP features (plot & synopsis similarity)  

---

## 📄 License

This project is MIT-licensed — see the [LICENSE](LICENSE) file for details.

---

*Happy movie-hunting!* 🍿✨
