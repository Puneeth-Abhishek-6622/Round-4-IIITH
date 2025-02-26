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
- MFCC (Mel-Frequency Cepstral Coefficients)**: Extracts 40 MFCC features per audio sample.  
- Mel Spectrograms: A time-frequency representation of the audio signals. We extracted 128 mel spectrogram features per audio file to capture energy distribution over different frequency bands.
- ZCR (Zero Crossing Rate): Measures the rate at which the signal changes its sign, useful for detecting voiced versus unvoiced segments.
- RMSE (Root Mean Square Energy): Represents the overall energy of the audio signal, helping in emotion detection by analyzing loudness variations



📊 The best-performing model was **CNN (81%)**, followed by **XGBoost (79%)**.  

## 📌 How to Run  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/yourusername/speech-emotion-recognition.git
   cd speech-emotion-recognition
