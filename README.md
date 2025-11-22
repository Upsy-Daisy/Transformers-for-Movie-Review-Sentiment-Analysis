# Transformers-for-Movie-Review-Sentiment-Analysis
Transformer-based sentiment analysis on IMDB dataset


# SentimentScope: Sentiment Analysis using Transformers

A transformer-based binary sentiment classification model for IMDB movie reviews, using PyTorch.

## Project Overview
This project implements a custom transformer model (DemoGPT) to classify movie reviews as positive or negative.

## Results
- **Test Accuracy: 76.78%** (Exceeds 75% requirement)
- Validation Accuracy: 78.96% (after 3 epochs)

## Model Details
- Architecture: Custom DemoGPT transformer with 4 layers, 4 attention heads
- Embedding dimension: 128
- BERT tokenizer (bert-base-uncased)

## Dataset
- IMDB Movie Reviews
- 25,000 training samples (split: 22,500 train / 2,500 validation)
- 25,000 test samples
- Training: 3 epochs, batch size 32, AdamW optimizer

## Files
- `Project_SentimentScope.ipynb`: Complete implementation and results
- `best_model_state.pth`: Trained model weights
