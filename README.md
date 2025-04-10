🎬 MovieLens Data Analysis: Predicting Ratings and Understanding Preferences
Welcome! This project explores the MovieLens dataset with the goal of building predictive models for user ratings and uncovering hidden patterns in movie preferences. By combining statistical insights with advanced machine learning techniques, this analysis provides a robust approach to recommendation systems and predictive modeling.

🔍 Project Overview
The main focus of this analysis is to:

Predict user ratings accurately using both linear and non-linear models.

Tackle real-world challenges like the cold start problem.

Understand how movie ratings evolve over time.

Evaluate how different modeling techniques perform under various preprocessing strategies.

✨ Key Insights
📅 Temporal Trends Matter: Ratings change significantly across decades. Incorporating temporal features (like release year) helped capture evolving viewer preferences.

📊 Distribution Adjustments: Aligning the test set's rating distribution with the training set led to improved accuracy and reduced bias.

🧠 Factorization Machines: FM models captured complex feature interactions, significantly boosting predictive performance.

👥 K-Nearest Neighbors: KNN helped address the cold start problem by making predictions based on user/movie similarity.

📈 Isotonic Regression: This technique modeled non-linear patterns in yearly rating trends with surprising flexibility.

🧰 Techniques & Tools
Python (Pandas, NumPy, Scikit-learn, LightFM, Surprise)

Factorization Machines (via lightfm)

KNN-based collaborative filtering

Isotonic regression for trend fitting

Custom feature engineering (temporal bins, user/movie encoding, etc.)

🧠 What I Learned
This project sharpened my understanding of recommender systems, especially:

The importance of feature engineering in enhancing model performance.

How to handle data imbalance and bias.

Practical strategies for cold start mitigation.

The real-world value of combining classic statistical techniques with modern machine learning models.

🚀 Try It Out
You can explore the full analysis in the MovieLens_Analysis.ipynb notebook. Each step is well-commented and modular for easy replication or extension.
