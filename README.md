# Fake News Classifier Using LSTM

This project is a text classification model that identifies whether a news article is **Fake** or **Real** using Natural Language Processing (NLP) techniques and a Long Short-Term Memory (LSTM) network.

## Project Overview

This classifier uses the following pipeline:
- Data preprocessing and cleaning (removing special characters, stopwords, etc.)
- Tokenization and One-Hot Encoding
- Sequence Padding
- Word Embedding using Keras' `Embedding` layer
- LSTM for sequential pattern learning
- Dense output with sigmoid activation for binary classification

## Technologies Used

- Python 3.x
- Pandas, NumPy, Matplotlib
- TensorFlow / Keras
- NLTK (for stopword removal)
- Scikit-learn (for train/test split and evaluation)

## Dataset

The dataset was downloaded from Kaggle's [Fake News Classification](https://www.kaggle.com/competitions/fake-news-classification/data) competition. It contains news headlines labeled as **real** or **fake**.

## Model Architecture

- Embedding Layer: Transforms each word into a vector of fixed size.
- LSTM Layer: Captures temporal dependencies in the text.
- Dense Layer: Outputs a binary prediction (0 = Fake, 1 = Real).

## Evaluation Metrics

- Accuracy
- Confusion Matrix
- Classification Report

## How to Run

1. Clone this repository.
2. Install required packages using `pip install -r requirements.txt`.
3. Run the notebook: `FakeNewsClassifierUsingLSTM_CLEANED.ipynb`.

## License

This project is for educational purposes only. Please check the dataset source for usage restrictions.