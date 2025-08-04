# TagPrediction-AutoTaggingPhotographers
The Photography Tag Prediction Model is a multi-label classification system designed to automatically assign relevant descriptive tags (e.g., candid, fashion, fine-art) to photographers’ portfolios based on their text descriptions. This enables intelligent tagging, improves searchability, and enhances content categorization on the platform.
# 📸 Photography Tag Prediction Model

A machine learning system for automatically tagging photographer portfolios using text descriptions. This project implements a multi-label classification model trained on photography-related data using TF-IDF and Logistic Regression.

Overview

This project helps predict multiple relevant tags (e.g., `wedding`, `candid`, `natural-light`) for photographers' portfolio descriptions. It is designed to enhance search, filtering, and discovery functionality on photography platforms.

Features

- Text Preprocessing: Lowercasing, punctuation removal, photography-specific term normalization  
- TF-IDF Vectorization: Converts text into n-gram-based feature vectors  
- Multi-label Classification: Logistic Regression with One-vs-Rest strategy  
- Evaluation Metrics: F1-score, Precision@k, Recall@k, and Hamming Loss  
- Model Persistence: Save and load models with `pickle`  
- Confidence Scores: Ranked tag predictions with associated probabilities

File Structure

├── photography_tagger.py        # Core model class and training code
├── sample_portfolio_data.csv   # Sample training data
├── photography_tagger_model.pkl# Saved model file
├── README.md                    # Project overview and instructions
