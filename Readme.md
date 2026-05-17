# NLP and Sequence Modeling Mini Project

## Project Overview

This project focuses on Natural Language Processing (NLP) and Sequence Modeling techniques for customer sentiment classification. The objective is to understand how textual data is transformed into numerical representations and how machine learning and deep learning models process sequential text information.

The project uses a customer support text dataset containing customer messages and sentiment labels.

---

# Dataset Description

Dataset File:
`customer_support_text_classification.csv`

The dataset contains customer support messages with sentiment labels such as:
- Positive
- Negative
- Neutral

### Main Columns

| Column Name | Description |
|---|---|
| ticket_id | Unique ticket identifier |
| customer_message | Customer support message |
| sentiment_label | Sentiment category |
| channel | Communication channel |
| urgent_flag | Urgency indicator |

---

# Project Tasks

## Task 1: Dataset Understanding
Performed exploratory analysis including:
- Number of records
- Class distribution
- Sample text analysis
- Average text length

---

## Task 2: Text Preprocessing
Applied preprocessing techniques such as:
- Lowercasing
- Removing special characters
- Tokenization
- Stopword removal
- Sequence padding

---

## Task 3: Text Vectorization
Converted text into numerical format using:
- TF-IDF Vectorization
- Tokenizer-based sequences

---

## Task 4: Baseline Model
Built a baseline NLP classification model using:
- Logistic Regression
- TF-IDF features

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Task 5: Sequence Model
Implemented an LSTM-based sequence model using TensorFlow/Keras.

Model architecture includes:
- Embedding Layer
- LSTM Layer
- Dense Output Layer

---

## Task 6: Attention and Transformer Reflection
Discussed:
- Limitations of RNNs
- Advantages of LSTMs
- Attention mechanism
- Importance of Transformers in modern NLP and Generative AI

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- NLTK
- Matplotlib
- Jupyter Notebook

---

# Project Structure

```text
part-3-nlp-sequence-modeling/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
│
└── results/
    ├── model_evaluation.png
    └── sample_predictions.txt


```python

```
