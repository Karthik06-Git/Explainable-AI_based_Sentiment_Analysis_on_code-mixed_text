# Explainable-AI based Sentiment Analysis for Code-Mixed Telugu-English Text

An end-to-end NLP system for sentiment analysis on Telugu–English code-mixed text, integrating deep learning, transformer models, and Explainable AI techniques for transparent predictions.

---

## Features
- Robust preprocessing for noisy, code-mixed text
- Handles multilingual and informal social media data
- Models: RNN, LSTM, Bi-LSTM, BERT, RoBERTa
- Explainability using LIME & SHAP
- Provides interpretable sentiment predictions

---

## Project Structure
```
Sentiment_Analyzer
├── Data/                          # Dataset (CMTET)
├── Sentiment_Analysis_CMTET.ipynb # Main notebook (pipeline + models)
├── LICENSE                        # License file
└── README.md                      # Project documentation
```

## Tech Stack
- Python, NumPy, Pandas
- TensorFlow / PyTorch
- Hugging Face Transformers
- NLTK / SpaCy
- LIME, SHAP

---

## Results

| Model   | Accuracy | F1 Score |
| ------- | -------- | -------- |
| RNN     | 70%      | 68.87%   |
| GRU     | 74%      | 73.27%   |
| LSTM    | 73%      | 72.16%   |
| Bi-LSTM | 76%      | 74.23%   |
| BERT    | 79%      | 77%      |
| RoBERTa | **80%**  | **78%**  |
