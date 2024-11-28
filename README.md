

# **Fake News Detection Using Machine Learning**

## 📌 Overview
This project focuses on building a **Fake News Detection System** using machine learning and natural language processing (NLP) techniques. By analyzing and classifying textual data, the system aims to accurately distinguish between fake and real news. The project utilizes various machine learning models, evaluates their performance, and includes robust visualizations to understand data and results effectively.

---

## 🛠️ Features
- **Preprocessing**: Cleaning text data, generating word counts, character counts, and sentiment polarity scores.
- **Visualization**: Word clouds, distribution plots, and interactive graphs for data exploration.
- **Balanced Dataset**: Utilizes **SMOTE** for oversampling to handle class imbalance.
- **Model Training**: Trains and compares multiple models:
  - Logistic Regression
  - Multinomial Naive Bayes
  - Random Forest Classifier
- **Metrics**: Detailed evaluation using accuracy, precision, recall, F1 score, ROC-AUC score, and confusion matrices.

---

## 📊 Visualizations
- **Word Clouds**: Showcasing commonly used words in fake and real news.
- **Confusion Matrices**: Heatmaps for model predictions.
- **Feature Importance**: Bar graphs of feature weights for the Random Forest model.

---

## ⚙️ Technical Details
- **Dataset**: The project uses a news dataset containing text, author names, and labels (FAKE/REAL).
- **Libraries**:
  - `Pandas`: For data manipulation.
  - `Seaborn` and `Matplotlib`: For visualization.
  - `TextBlob`: For sentiment analysis.
  - `Scikit-learn`: For machine learning models and metrics.
  - `Imbalanced-learn (SMOTE)`: For balancing data.

---

## 🎯 Results
The models were evaluated, and the **Random Forest Classifier** performed the best, achieving the following metrics:
- **Accuracy**: ~96%
- **Precision**: ~95%
- **Recall**: ~96%
- **F1 Score**: ~95%
- **ROC-AUC**: ~0.97

---

## 📷 Visualizations
1. **Word Cloud for Fake News**
2. **Word Cloud for Real News**
3. **Confusion Matrix (Logistic Regression)**

---

## 🚀 Future Work
- Expand the dataset to include multilingual news articles.
- Incorporate deep learning models like **LSTM** and **BERT** for enhanced accuracy.
- Develop a live web application for real-time fake news detection.

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request with your improvements or ideas.

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).

---

## 🌟 Acknowledgments
Special thanks to the creators of the dataset and the open-source community for their excellent tools and resources.
"""
