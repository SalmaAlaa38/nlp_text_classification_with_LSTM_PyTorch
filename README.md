# 🧠 NLP Text Classification with LSTM (PyTorch)

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

------------------------------------------------------------------------

## 📌 Overview

This project implements a complete **Natural Language Processing (NLP)
pipeline** for text classification using a **Long Short-Term Memory
(LSTM)** model built with PyTorch.

------------------------------------------------------------------------

## 🚀 Features

-   Text preprocessing (tokenization, stopword removal, lemmatization)
-   Custom vocabulary building
-   Sequence encoding and padding
-   LSTM-based deep learning model
-   Bidirectional LSTM support (optional)
-   Model training with batching
-   Evaluation using multiple metrics
-   Model saving & loading pipeline

------------------------------------------------------------------------

## 🧱 Project Pipeline

Raw Text → Preprocessing → Tokenization → Encoding → Padding → Embedding
→ LSTM → Prediction

------------------------------------------------------------------------

## 🧪 Model Architecture

-   Embedding Layer
-   LSTM Layer(s)
-   Dropout Layer
-   Fully Connected Layer

------------------------------------------------------------------------

## ⚙️ Hyperparameters

-   Embedding Size: 128
-   Hidden Size: 256
-   Batch Size: 32
-   Epochs: 5--20
-   Learning Rate: 0.001
-   Dropout: 0.3

------------------------------------------------------------------------

## 📊 Evaluation Metrics

-   Accuracy\
-   Precision\
-   Recall\
-   F1-score\
-   Confusion Matrix

------------------------------------------------------------------------

## 💾 Saving & Loading the Model

### Save

torch.save({...}, "lstm_model.pth")

### Load

checkpoint = torch.load("lstm_model.pth")

------------------------------------------------------------------------

## 📁 Project Structure

NLP_Neurova_toxic_content_classification.xlsx\
lstm_model.pth\
label_encoder.pkl\
processed_dataset.xlsx\
README.md\
text_classifier.ipynb
vocab.pkl

------------------------------------------------------------------------

## 🛠️ Technologies Used

Python, PyTorch, NumPy, Pandas, Scikit-learn, NLTK, Matplotlib, Seaborn, String, Re, Collections, Pickle

------------------------------------------------------------------------

## 📌 Future Improvements

-   Pretrained embeddings
-   Transformer models (BERT)
-   API deployment

------------------------------------------------------------------------

⭐ If you found this project useful, consider giving it a star!
