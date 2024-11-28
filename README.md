
# **Fake News Detection Using Machine Learning**

## 📌 Overview
This project implements a robust **Fake News Detection System** using **Natural Language Processing (NLP)** and **Machine Learning**. The system classifies news articles as either **Fake** or **Real** based on their content, leveraging various supervised learning models.

## 🛠️ Features
- **Text Preprocessing**: Cleaned and tokenized news text for feature extraction.  
- **Feature Engineering**: Extracted TF-IDF features, sentiment polarity, word counts, and character counts.  
- **Dataset Balancing**: Resolved class imbalance using **SMOTE**.  
- **EDA (Exploratory Data Analysis)**:  
  - Word clouds to identify frequent terms in fake and real news.  
  - Sentiment analysis and visualized distributions of text properties.  
- **Machine Learning Models**: Implemented **Logistic Regression**, **Naive Bayes**, and **Random Forest** models.  
- **Model Evaluation**: Used metrics like accuracy, precision, recall, F1-score, and ROC-AUC to evaluate performance.  
- **Visualization**: Displayed confusion matrices, feature importance plots, and ROC curves for each model.

---

## 📂 Project Structure

Fake-News-Detection/
├── data/
│   ├── news.csv              # Dataset used for training
│   └── example.csv           # Optional sample dataset (if full data isn't shareable)
├── notebooks/
│   └── fake_news_detection.ipynb # Full code in a Jupyter notebook
├── scripts/
│   ├── preprocessing.py      # Text preprocessing and feature extraction
│   ├── modeling.py           # Model training and evaluation
│   └── visualization.py      # Visualization functions
├── visuals/
│   ├── word_cloud_fake.png   # Word cloud for fake news
│   ├── word_cloud_real.png   # Word cloud for real news
│   └── other_plots.png       # Any additional EDA/analysis plots
├── README.md                 # Documentation
├── requirements.txt          # List of Python dependencies
├── LICENSE                   # Licensing information
