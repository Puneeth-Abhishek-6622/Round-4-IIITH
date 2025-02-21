# 🎭 Speech Emotion Recognition using Indian Emotional Speech Corpora (IESC)  

## 📌 Overview  
This project is a **Speech Emotion Recognition (SER) system** that classifies emotions from speech audio using **MFCC features** and multiple machine learning models, including **CNN, LSTM, SVM, and XGBoost**. The goal is to analyze and compare different models for accuracy and effectiveness in detecting emotions from Indian speech data.  

## 📂 Dataset  
We use the **Indian Emotional Speech Corpora (IESC)** dataset, which consists of **600 audio files** recorded by **8 North Indian speakers** across **five emotions**:  
- 😠 **Anger**  
- 😨 **Fear**  
- 😃 **Happy**  
- 😐 **Neutral**  
- 😢 **Sad**  

📥 **Dataset Source:** [IESC on Kaggle](https://www.kaggle.com/datasets/ybsingh/indian-emotional-speech-corpora-iesc/data)  

## 🚀 Features Extracted  
- **MFCC (Mel-Frequency Cepstral Coefficients)**: Extracts 13 MFCC features per audio sample.  
- **Mean Aggregation**: Averaging over time to get a fixed-length feature vector.  

## 📊 Models Used  
We implemented and compared multiple models:  
1. **Convolutional Neural Network (CNN)** 🧠  
2. **Long Short-Term Memory (LSTM)** 🔄  
3. **Support Vector Machine (SVM)** 🔍  
4. **XGBoost Classifier** 🚀  

## 🏆 Model Performance  
| Model  | Accuracy (%) |  
|--------|-------------|  
| **CNN**  | **81%**  |  
| **LSTM**  | **61%**  |  
| **SVM**  | **70%**  |  
| **XGBoost**  | **79%**  |  

📊 The best-performing model was **CNN (81%)**, followed by **XGBoost (79%)**.  

## 📌 How to Run  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/yourusername/speech-emotion-recognition.git
   cd speech-emotion-recognition
