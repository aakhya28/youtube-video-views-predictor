# youtube-video-views-predictor
# YouTube Video Views Predictor

This project predicts YouTube video views using **Linear Regression** based on video engagement and metadata features.

---

## 📌 Problem Statement
Predict the number of views a YouTube video might receive using features such as likes, comments, title length, and video age.

---

## 🧠 Approach
- Cleaned and preprocessed the dataset
- Performed feature engineering (title length, video age)
- Built simple and multiple linear regression models
- Evaluated model performance using R² score
- Deployed the model using Gradio for real-time predictions

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Gradio  

---

## 📊 Model Evaluation
- Metric Used: **R² Score**
- The model explains a reasonable portion of variance in video views using available metadata features.
- Performance is limited by unobserved factors such as content quality and platform recommendation algorithms.

## 🚀 Deployment
The model is deployed using **Gradio**, allowing users to input video details and get predicted views interactively.
This project focuses on building an interpretable baseline regression model and understanding its limitations rather than maximizing accuracy.

