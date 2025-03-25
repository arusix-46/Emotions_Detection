# Emotion Recognition & Contextual Summarization

## 📌 Project Overview

This project, Emotion Recognition and Contextual Summarization for Mental Health Conversations, provides AI-driven mental health assistance by recognizing emotions in conversations and summarizing contextually relevant content. We implemented two distinct approaches to achieve robust emotion detection and contextual understanding:

### 🔹 1. Audio-Driven Emotion Recognition (ADER)

Converts text to speech using Google Text-to-Speech (GTTS).

Extracts key speech features using Mel-frequency cepstral coefficients (MFCC).

Trains XGBoost and Random Forest models with K-fold cross-validation for emotion classification.

Predicts emotions from unseen audio inputs for enhanced conversational analysis.

### 🔹 2. Contextual Summarization and Emotion Prediction (CSEP)

Tokenizes and encodes text data, including Dialogue Acts & Emotions.

Uses a custom BERT-based model for contextual understanding.

Applies BART for summarization when text length exceeds a threshold.

Predicts emotional states from both raw and summarized text.




## 🚀 How to Run

### 1. Audio-Driven Emotion Recognition (ADER)

📂 File: Conversion-to-audio-emotion-detection.ipynb📊 Dataset: 5247-rows_3-Emotions_No-Type.xlsx

🔹 Steps:

Install dependencies: pip install gTTS

Upload dataset

Run Conversion-to-audio-emotion-detection.ipynb (Converts text to speech and detects emotions)

Saves audio files to audio_outputs_gtts

Upload .mp3 file for emotion prediction

### 2. Contextual Summarization and Emotion Prediction (CSEP)

📂 File: Emotions-Detection-Using-Text-Utterance.ipynb📊 Dataset: 5247-rows_3-Emotions_No-Type.xlsx

🔹 Steps:

Install dependencies

Upload dataset

Run Emotions-Detection-Using-Text-Utterance.ipynb (Detects emotions from text)

Upload any text; if word count > 30, it summarizes before emotion prediction

## 🎯 Key Contributions

✅ Emotion Recognition through Audio & Text: ADER analyzes speech while CSEP enhances text-based emotion detection.✅ Advanced Modeling Techniques: Utilizes XGBoost, Random Forest, and a Custom BERT Model for robust classification.✅ Summarization for Context Understanding: BART enables better context interpretation in long conversations.

This project enhances AI-driven mental health support by integrating speech and text-based emotion recognition with contextual summarization, ensuring actionable insights for improved therapeutic interactions.
