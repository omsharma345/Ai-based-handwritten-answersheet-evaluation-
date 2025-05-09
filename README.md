# Ai-based-handwritten-answersheet-evaluation-
A deep learning project that converts handwritten text images into machine-readable text using OCR. Built with PyTorch and the IAM Handwriting Database, it trains a CRNN model with CTC loss. Ideal for exploring custom handwriting recognition and OCR pipelines.
# AI-Based Copy Correction System

## Overview
This project automates the evaluation of handwritten answer sheets using Artificial Intelligence. It leverages Optical Character Recognition (OCR) to extract text from scanned copies, then applies Natural Language Processing (NLP) to compare student answers with model answers and assign marks automatically. Designed to deliver faster, more consistent, and unbiased grading at scale.

## Features
- **OCR Layer**: Converts scanned handwritten answers into machine-readable text using EasyOCR and Tesseract.
- **NLP Layer**: Evaluates extracted text through TF-IDF vectorization and cosine similarity scoring.
- **Automated Grading**: Assigns marks based on answer similarity with model answers.
- **Instant Feedback**: Provides real-time performance evaluation.
- **Fair and Scalable**: Reduces manual effort, bias, and delay in result publication.

## Technologies Used
- **OCR**: Tesseract, EasyOCR, OpenCV (for preprocessing)
- **NLP**: spaCy, NLTK, Scikit-learn (TF-IDF Vectorizer, Cosine Similarity)
- **Python Libraries**: NumPy, Matplotlib, PIL

## How It Works
1. Preprocess scanned answer sheets (grayscale, thresholding, noise reduction).
2. Extract handwritten text using OCR.
3. Clean and tokenize text using NLP techniques.
4. Compare student answers with model answers using cosine similarity.
5. Automatically assign marks based on similarity thresholds.

   ![WhatsApp Image 2025-04-24 at 07 23 26_afe3aa82](https://github.com/user-attachments/assets/00f2aace-a8ad-434d-b39d-5db9122c8e1e)
![WhatsApp Image 2025-04-24 at 07 24 23_0ee59799](https://github.com/user-attachments/assets/ac0fe987-9039-495c-8f0e-cb87f0c991f5)
![WhatsApp Image 2025-04-24 at 07 23 41_79fc8d9d](https://github.com/user-attachments/assets/1a673f0d-29cf-40cf-8a34-b3c590d7f990)


## Installation
```bash
pip install torch torchvision easyocr opencv-python scikit-learn nltk spacy pillow matplotlib



