# Emotion Recognition from Text Messages

## Overview

This project explores and implements machine learning and natural language processing (NLP) techniques for 
emotion recognition from text messages. It addresses the growing demand for understanding emotional context in 
digital communication, with applications in marketing, psychology, user support, and social sentiment analysis.

## Key Features

1. **Comprehensive Literature Review**: Analysis of classical methods (SVM, Naive Bayes), deep neural networks (RNN, LSTM, GRU), 
   and transformer-based models (BERT, RoBERTa).
2. **Dataset Exploration**: Utilization of the DailyDialog dataset, addressing data imbalance issues through augmentation.
3. **Model Development**: Implementation of classical machine learning algorithms and advanced deep learning models for emotion classification.
4. **Telegram Bot**: Creation of a user-friendly bot for real-time emotion recognition.

## Highlights

- **Best Model Performance**:
  - **RoBERTa**: Achieved highest accuracy (73.45%) and F1 score (73.12%).
  - Superior at handling complex language constructs, sarcasm, and context.
  
- **Comparison of Models**:
  - Classical methods like SVM and Naive Bayes performed adequately but lacked contextual understanding.
  - LSTM demonstrated significant improvement over RNN due to its ability to capture long-term dependencies.
  - Transformer-based models (BERT, RoBERTa) outperformed all others, showcasing state-of-the-art capabilities.

- **Data Augmentation**:
  - Balancing of underrepresented emotion classes using synthetic data generation.
  - Notable trade-offs in performance observed post-augmentation.

## Results

- **Before Augmentation**:
  - RoBERTa Accuracy: 73.45%
  - SVM Accuracy: 64.92%
  
- **After Augmentation**:
  - Drop in accuracy across all models due to challenges in synthetic data quality.

## Applications

- Emotion recognition enhances human-computer interaction, customer sentiment analysis, and mental health monitoring.
- The developed Telegram bot demonstrates practical implementation, offering real-time emotion insights.

## Recommendations

- Further improve data augmentation techniques to enhance model generalization for underrepresented classes.
- Extend the functionality of the Telegram bot, including multi-language support and broader NLP capabilities.

## Acknowledgments

This work was guided by Asel Karakuchukova under the supervision of O.A. Sviridova at the Financial University under the 
Government of the Russian Federation.
