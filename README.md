
# Sentiment Analysis for Arabic and English Text

This project is a traditional machine learning-based sentiment analysis system built from scratch to support both Arabic and English texts. It uses TF-IDF vectorization and classic classifiers like Logistic Regression and SVM.

---

## 📚 Project Overview

- 🔤 Supports: English & Arabic text
- 🔍 Techniques: Text preprocessing, TF-IDF, Classical ML (SVM / Logistic Regression)
- 📦 Models: Trained and saved separately for each language
- 📊 Evaluation: Accuracy, Classification Report, Confusion Matrix

---

## 📁 Folder Structure

```
merge/
├── Actual Sentiment Analysis.ipynb    # Main notebook with all logic
├── Arabic.csv                         # Arabic training data
├── English.csv                        # English training data
├── ar_reviews_100k.tsv                # Raw Arabic dataset
├── arabic_sentiment_model.pkl        # Saved Arabic model
├── arabic_tfidf_vectorizer.pkl       # Saved Arabic TF-IDF
├── english_sentiment_model.pkl       # Saved English model
├── english_tfidf_vectorizer.pkl      # Saved English TF-IDF
```

---

## 🛠 How to Run This Project

Follow these steps:

### 1. Clone the Repo
```
git clone https://github.com/m-albalushi/sentiment-analysis-ar-en.git
cd sentiment-analysis-ar-en
```

### 2. Set Up the Environment
Recommended: Use a virtual environment.
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

If requirements.txt is missing, install manually:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk snowballstemmer joblib
```

Then, run the following once to download NLTK data:
```python
import nltk
nltk.download('stopwords')
```

### 3. Open the Notebook
Use Jupyter or VSCode:
```
jupyter notebook "Actual Sentiment Analysis.ipynb"
```

Run each cell step-by-step.

---

## ✅ Skills Demonstrated

- Preprocessing Arabic & English text
- Applying classical ML models
- Saving/loading models with joblib
- Handling multiple languages
- Building an end-to-end sentiment pipeline

---

## 🤔 Why This Project Matters

This was built as a university-level machine learning project to demonstrate:
- Full NLP pipeline understanding
- Ability to build without external NLP APIs or frameworks
- Support for right-to-left languages like Arabic

Even though it uses classic ML (not deep learning), it's an excellent base to learn from.

---

## 📈 Future Improvements

- Upgrade to transformers (e.g. BERT, AraBERT)
- Add visual interface using Streamlit
- Improve Arabic preprocessing (diacritics, normalization)
- Use balanced datasets and more robust metrics (F1, ROC AUC)

---

## 🧑‍🎓 Author

Musallam Albalushi  
Electrical & Computer Engineering  
Sultan Qaboos University  
