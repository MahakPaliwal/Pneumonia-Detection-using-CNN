# Pneumonia Detection using CNN

A deep learning model to detect pneumonia from chest X-ray images.

## Problem Statement
Pneumonia is a life-threatening disease. Early and accurate detection from chest X-rays can significantly improve patient outcomes. This project automates the classification of X-ray images as Normal or Pneumonia.

## Dataset
- Source: Kaggle Chest X-Ray Images (Pneumonia)
- Classes: Normal, Pneumonia
- Total Images: 5,863 X-Ray images

## Approach
- Preprocessed images with resizing and normalization
- Applied data augmentation to handle class imbalance
- Built a CNN model using TensorFlow and Keras
- Applied regularization techniques to reduce overfitting
- Evaluated using accuracy, confusion matrix, classification report

## Tech Stack
Python | TensorFlow | Keras | Pandas | NumPy | Matplotlib | Seaborn

## How to Run
1. Open notebook in Google Colab or Jupyter
2. Download dataset from Kaggle and upload to Colab
3. Run all cells sequentially

## Results
- Evaluated on accuracy, precision, recall, and F1-score
- Confusion matrix and classification report included
