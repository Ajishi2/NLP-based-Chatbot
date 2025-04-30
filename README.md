# 🧠 Multilingual AI Chatbot with FFNN and BiLSTM

This project presents a multilingual, rule-based chatbot enhanced with deep learning techniques, specifically Feedforward Neural Networks (FFNN) and Bidirectional Long Short-Term Memory (BiLSTM). The chatbot is designed to deliver intelligent, accessible, and context-aware responses across multiple languages, with added text-to-speech (TTS) support.

## 📌 Motivation

With increasing globalization, there's a critical need for intelligent systems that can understand and communicate across diverse linguistic and cultural contexts. This chatbot aims to bridge communication gaps by combining NLP techniques, rule-based logic, and deep learning architectures.

## 🎯 Objectives

- Develop a hybrid chatbot using rule-based logic and AI models (FFNN & BiLSTM).
- Integrate text-to-speech (TTS) for improved accessibility, especially for visually impaired users.
- Support multilingual input and response generation to remove language barriers.
- Evaluate accuracy, contextual performance, and user satisfaction across real-world applications like education, customer care, and healthcare.

## 🧪 Methodology

1. **Data Preprocessing**
   - Text normalization: Lowercasing, punctuation removal, multilingual corrections.
   - Tokenization and lemmatization.
   - Bag-of-words vectorization.

2. **Model Architectures**
   - **FFNN**: Dense + dropout layers (256 & 64 units with 0.5 and 0.3 dropout) for intent classification.
   - **BiLSTM**: Embedding + BiLSTM + batch normalization + dropout for contextual understanding and sequence learning.

3. **Training**
   - Dataset: 95 samples (80:20 train-test split).
   - Evaluation Metrics: Accuracy, contextual relevance, response clarity.

4. **Text-to-Speech**
   - Converts generated responses into audio for enhanced accessibility.

## 🧱 Architecture Overview

- Input: User query → Language detection → Preprocessing  
- Processing: Intent classification via FFNN / BiLSTM  
- Output: Appropriate response + TTS audio output  

## 📈 Results

- **FFNN Accuracy**: 94% for intent classification.
- **BiLSTM Accuracy**: 78% for multilingual, context-sensitive tasks.
- Improved accessibility and inclusiveness through TTS.


