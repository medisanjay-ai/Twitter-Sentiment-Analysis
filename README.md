# 🐦 Twitter Sentiment Analysis

A Machine Learning project that classifies tweets as **positive** or **negative** using Logistic Regression implemented completely from scratch.

This project covers:
- Sigmoid Function
- Gradient Descent
- Feature Extraction
- Sentiment Classification
- Model Evaluation

---

# 📌 Problem Statement

The goal of this project is to analyze tweet sentiment and predict whether a tweet expresses:

- Positive sentiment 😊
- Negative sentiment 😔

using Natural Language Processing (NLP) techniques and Logistic Regression.

---

# 📊 Dataset Information

### Dataset Source
NLTK `twitter_samples` dataset

### Dataset Size
- 5,000 positive tweets
- 5,000 negative tweets
- Total: 10,000 tweets

### Train/Test Split
- 80% Training
- 20% Testing

---

# 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- NLTK
- Jupyter Notebook

---

# 📂 Project Structure

```bash
Twitter-Sentiment-Analysis/
│
├── MT.ipynb
├── sentimentalAnalysis.ipynb
├── utils.py
├── requirements.txt
├── README.md
└── w1_unittest.py
```

---

# 🧠 NLP Techniques Used

- Tweet Cleaning
- Stopword Removal
- Stemming
- Tokenization
- Frequency Dictionary Building
- Feature Extraction

---

# ⚙️ Machine Learning Algorithm

## Logistic Regression (Implemented From Scratch)

Implemented manually using:
- Sigmoid Function
- Gradient Descent
- Cost Function Optimization

No external ML model libraries were used for training.

---

# 📈 Model Performance

| Metric | Value |
|---|---|
| Accuracy | 99.5% |
| Dataset | NLTK twitter_samples |
| Algorithm | Logistic Regression |

---

# 🔍 Key Features

✅ Tweet preprocessing using NLP  
✅ Logistic Regression from scratch  
✅ Feature extraction using word frequencies  
✅ Gradient Descent optimization  
✅ High accuracy sentiment classification  

---

# 🧪 Testing

Custom unit tests included for:
- Sigmoid Function
- Gradient Descent
- Feature Extraction
- Tweet Prediction
- Logistic Regression Accuracy

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/medisanjay-ai/Twitter-Sentiment-Analysis.git
```

## Navigate to Project

```bash
cd Twitter-Sentiment-Analysis
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run The Project

## Download NLTK Datasets

```python
import nltk

nltk.download('twitter_samples')
nltk.download('stopwords')
```

---

## Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:
- `MT.ipynb`
- `sentimentalAnalysis.ipynb`

Run all cells.

---

# 📸 Workflow

1. Load Dataset
2. Clean Tweets
3. Tokenize & Stem Words
4. Build Frequency Dictionary
5. Extract Features
6. Train Logistic Regression
7. Predict Sentiment
8. Evaluate Accuracy

---

# 📌 Example Predictions

| Tweet | Prediction |
|---|---|
| I am very happy today | Positive 😊 |
| This is the worst day ever | Negative 😔 |
| Amazing experience | Positive 😊 |
| I feel terrible | Negative 😔 |

---

# 🔥 Future Improvements

- Add Streamlit Web App
- Deploy using Flask/FastAPI
- Add Real-Time Twitter API Integration
- Use Deep Learning Models (LSTM/BERT)
- Multi-class Sentiment Analysis

---

# 👨‍💻 Author

## Medi Sanjay

AI/ML Engineer | Data Scientist | Generative AI Enthusiast

📍 Hyderabad, India

---

# ⭐ Acknowledgements

- NLTK
- Kaggle
- Natural Language Processing Community
