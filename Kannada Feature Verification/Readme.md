# Kannada Emotional Speech Dataset (Subset)

## 📌 Overview
The **Kannada Emotional Speech Dataset** is a publicly available dataset designed for **speech emotion recognition (SER)** in the **Kannada language**. The original dataset, hosted on Zenodo ([link](https://zenodo.org/records/6345107)), consists of **468 audio samples** recorded by **13 speakers** (4 male, 9 female) across **six emotions**:

1. **Anger**
2. **Sadness**
3. **Surprise**
4. **Happiness**
5. **Fear**
6. **Neutral**

Each speaker pronounced **six different sentences**, and the dataset follows a structured **naming convention** (e.g., `AA-EE-SS.wav`), where:
- `AA` represents the **speaker ID** (01-13).
- `EE` represents the **emotion ID** (01-06).
- `SS` represents the **sentence ID** (01-06).

The dataset was **collected from volunteers** and is freely available under a **Creative Commons license**. However, since the recordings were made in an **uncontrolled environment**, they may include background noise or variations in speech clarity.

## 📌 Subset Used in This Project
For this project, we selected a **balanced subset of 100 samples** from the original dataset with an approximate distribution of:
- **Anger** → 16 samples
- **Sadness** → 16 samples
- **Surprise** → 17 samples
- **Happiness** → 17 samples
- **Fear** → 17 samples
- **Neutral** → 17 samples

## 📌 Feature Extraction
We extracted key **acoustic features** from the audio files:
- **MFCCs** (Mel-Frequency Cepstral Coefficients) – 40 coefficients
- **Mel Spectrogram** values – 128 coefficients
- **ZCR** (Zero Crossing Rate)
- **RMSE** (Root Mean Square Energy)

## 📌 Preprocessing
Before feeding the extracted features into the model:
- **Standardization**: We applied `StandardScaler()` to normalize the features.
- **Label Encoding**: Emotions were mapped to numeric values:
  - **Anger → 0**
  - **Sadness → 1**
  - **Surprise → 2**
  - **Happiness → 3**
  - **Fear → 4**
  - **Neutral → 5**

## 📌 Model Used
We trained a **CNN** model for **emotion classification**, leveraging the extracted features to improve prediction accuracy.

## 📌 Acknowledgments
This dataset is credited to the original contributors on Zenodo. The subset used here is for **research and educational purposes** in the field of speech emotion recognition.
