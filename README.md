# Explainable-AI based Sentiment Analysis for Code-Mixed Telugu-English Text

An end-to-end NLP system for sentiment analysis on Telugu–English code-mixed text, integrating deep learning, transformer models, and Explainable AI techniques for transparent predictions.

---

## Features
- Robust preprocessing for noisy, code-mixed text
- Models: RNN, LSTM, Bi-LSTM, BERT, RoBERTa
- Explainability using LIME & SHAP
- Handles multilingual and informal social media data
- Provides interpretable sentiment predictions

---

📂 Project Structure
├── Data/                          # Dataset (CMTET)
├── Sentiment_Analysis_CMTET.ipynb # Main notebook (pipeline + models)
├── LICENSE                        # License file
└── README.md                      # Project documentation

## Tech Stack
- Python, NumPy, Pandas
- TensorFlow / PyTorch
- Hugging Face Transformers
- NLTK / SpaCy
- LIME, SHAP

---

📊 Results
RoBERTa: 80% Accuracy, 78% F1-score
BERT: 79% Accuracy, 77% F1-score
Bi-LSTM: 76% Accuracy
