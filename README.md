# fake_news_detection
# 📰 Fake News Detection Using Machine Learning

This project demonstrates the use of Natural Language Processing (NLP) and Machine Learning to classify news articles as **REAL** or **FAKE**.

## 📌 Technologies Used:
- Python
- Pandas
- Scikit-learn
- TfidfVectorizer
- Logistic Regression
- Pickle

## 📂 Dataset:
A small sample dataset of news headlines and articles with labels:
- **REAL** → Legitimate news
- **FAKE** → Misinformation

## 🛠 Methodology:
1. Data Preprocessing (label mapping, cleaning)
2. Feature Extraction using TF-IDF
3. Training Logistic Regression Model
4. Model Evaluation using accuracy & confusion matrix
5. Model Deployment using Pickle

## 🚀 How to Run:
1. Load the dataset (`fake_or_real_news.csv`)
2. Train model and save as `logistic_model.pkl`
3. Use `predict_news(text)` function to classify new text

## 📈 Results:
- Achieved high accuracy on the test set
- Model is able to distinguish between FAKE and REAL news articles

## 💡 Future Improvements:
- Larger, real-world dataset
- More advanced NLP techniques (BERT, transformers)
- Web application for public use

---

