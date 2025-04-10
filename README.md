## 🎥 MovieLens Data Analysis: Predicting Ratings and Understanding Preferences

Welcome! This project explores the [MovieLens dataset](https://grouplens.org/datasets/movielens/) with the goal of building predictive models for user ratings and uncovering hidden trends in movie preferences. By combining statistical insights with advanced machine learning techniques, this analysis provides a robust approach to recommendation systems and predictive modeling.

---

### 🔍 Project Overview

The main focus of this analysis is to:

- Predict user ratings using both linear and non-linear models.
- Tackle real-world challenges like the cold start problem.
- Understand how movie ratings evolve over time.
- Evaluate how different modeling techniques perform under various preprocessing strategies.

---

### ✨ Key Insights

- 📆 **Temporal Trends Matter**  
  Ratings change significantly across decades. Incorporating temporal features such as release year helped capture evolving viewer preferences.

- 🎯 **Distribution Adjustments**  
  Aligning the test set’s rating distribution with the training set led to improved accuracy and reduced bias.

- 📚 **Factorization Machines (FM)**  
  FM models captured complex feature interactions and outperformed traditional matrix factorization techniques.

- 👥 **K-Nearest Neighbors (KNN)**  
  Used to mitigate the cold start problem, KNN-based models leveraged user/item similarity to generate better recommendations for new users and movies.

- 📈 **Isotonic Regression**  
  This technique provided a flexible, non-linear fit for capturing yearly variations in rating trends.

---

### 🧰 Tools & Techniques

- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Surprise, LightFM  
- **Models Used**:  
  - Linear Regression  
  - K-Nearest Neighbors  
  - Factorization Machines  
  - Isotonic Regression

- **Techniques**:  
  - Temporal feature engineering  
  - Cold start problem handling  
  - Rating distribution normalization  
  - RMSE and MAE evaluation

---

### 📁 Repository Structure

├── py/ # Scripts for collaborative filtering and vector processing │ ├── CollabFilterOneVectorPerItem.py │ └── read_svd_vectors.py ├── Movie Recommendation Project.ipynb # Main notebook with full analysis ├── .gitignore ├── README.md

---

### 📫 Author

**HyunSu (John) Lee**  
Graduate Student in Data Science  

---

> This project was completed as part of a graduate-level data science course and demonstrates end-to-end recommendation system development—from feature engineering to model evaluation.
