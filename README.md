📱 TikTok Claim Classification & Engagement Analysis

End-to-end data analytics project focused on classifying TikTok videos as claims or opinions using engagement metrics and machine learning.

📌 Overview

This project builds and evaluates classification models to support content moderation by identifying videos that may require review.

The modeling objective prioritizes recall to minimize false negatives (claims misclassified as opinions).

📊 Dataset

~20,000 TikTok videos including:

Engagement metrics (views, likes, shares, downloads)

Account attributes

Video transcription text

Binary target variable: claim_status

🧠 Methods

Exploratory Data Analysis (EDA)

Hypothesis testing

Feature engineering (including NLP n-grams)

Logistic Regression

Random Forest

XGBoost

Cross-validation with recall optimization

📈 Results

Strong classification performance on validation and test sets

Engagement metrics were highly predictive

Random Forest selected as champion model

Recall prioritized to support moderation risk management

🛠 Tools

Python • Pandas • NumPy • Scikit-learn • XGBoost • Matplotlib • Seaborn

🔎 Key Takeaway

User engagement patterns and textual features can effectively distinguish claim-based content, supporting scalable moderation workflows.
