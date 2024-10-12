# Adobe Behaviour Simulation

## Overview
This project predicts user engagement (likes) on social media posts for Adobe's marketing analytics.

## Problem Statement
Predict likes based on tweet content and media for:
1. Unseen companies, seen time stamp
2. Seen companies, unseen time stamp

## Dataset
- 300K training samples, 10K test samples
- Includes tweet content, company info, and engagement metrics

## Approach
1. Data Preprocessing:
   - Image processing: EfficientNet-B0 embeddings
   - Text processing: BERTweet embeddings
   - Date feature extraction

2. Modeling:
   - Tried various models: LightGBM, XGBoost, Random Forest, CatBoost, Neural Networks
   - Final approach: Ensemble of LightGBM and Neural Network

## Results
- 2.1K RMSE on cross-validation set

## Files
- `README.md`: Project overview
- `adobe-10k-using-finetuned-effnet.ipynb`: EfficientNet-B0 256 embeddings
- `adobe-cnn-baseline.ipynb`: CNN baseline model
- `adobe-eda.ipynb`: Exploratory Data Analysis
- `adobe-effnet-finetuning.ipynb`: EfficientNet fine-tuning
- `adobe-inference.ipynb`: Inference notebook
- `adobe-trying-all-models.ipynb`: Model experimentation
- `effnet-finetuned.pth`: Fine-tuned EfficientNet model

For more details, refer to the individual notebook files.
