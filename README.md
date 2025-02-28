# 🎭 Speech Emotion Recognition using Indian Emotional Speech Corpora (IESC)  

## 📂 Dataset  
We use the **Indian Emotional Speech Corpora (IESC)** dataset, which consists of **600 audio files** recorded by **8 North Indian speakers** across **five emotions**:  
- 😠 **Anger**  
- 😨 **Fear**  
- 😃 **Happy**  
- 😐 **Neutral**  
- 😢 **Sad**  

📥 **Dataset Source:** [IESC on Kaggle](https://www.kaggle.com/datasets/ybsingh/indian-emotional-speech-corpora-iesc/data)  

# Speech Emotion Recognition (SER) using Deep Learning

## 📌 Overview
This project implements a **Speech Emotion Recognition (SER) system** using deep learning techniques. The goal is to classify emotions from speech audio using various neural network architectures.


## 🎯 Features
- **Speech Emotion Classification** using LSTM, GRU, and BiLSTM.
- **Feature Engineering:** Extracts MFCC, Mel spectrogram,Chroma ,  ZCR, and RMSE.
- **Data Augmentation:** Enhances dataset diversity.
- **Cross-Lingual Analysis:** Tests model generalization on Urdu speech.
- **Performance Metrics:** Accuracy, Confusion Matrix, Classification Report.

## 📊 Model Performance
| Model   | Accuracy |
|---------|---------|
| CNN    | 81%  |
| LSTM    | 81.25%  |
| GRU     | 85.00%  |
| BiLSTM  | 88.75%  |
