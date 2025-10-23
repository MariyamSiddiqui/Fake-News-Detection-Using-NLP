# 📰 Fake News Detection using NLP

A machine learning project that detects fake news articles using Natural Language Processing (NLP).  
It includes text preprocessing (cleaning, lemmatization, stopword removal), TF-IDF vectorization, and classification using Logistic Regression and other ML models.

## 🔧 Steps Involved
1. **Data Acquisition** – Load or import a fake news dataset.
2. **Data Preprocessing** – Clean text, remove stopwords, and lemmatize words.
3. **Vectorization** – Convert text into numerical form using TF-IDF.
4. **Model Building** – Train models like Logistic Regression, Naive Bayes, or SVM.
5. **Evaluation** – Measure accuracy, precision, recall, and F1-score.
6. **Prediction Pipeline** – Make predictions on new unseen text.

## 🧠 Tech Stack
- Python  
- NLTK  
- Scikit-learn  
- Pandas / NumPy  

## 📊 Example Usage
```python
text = "Breaking news: Scientists discover water on Mars!"
predict(text)
# Output: {'label': 'Real', 'probability': 0.92}
