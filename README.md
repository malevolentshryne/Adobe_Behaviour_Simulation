# Adobe_Behaviour_Simulation

For inter iit 13.0 selection IIT Dhanbad

## Project Overview
This project aims to simulate user behavior and content to help marketers estimate social media engagement and create content that drives desired KPIs like likes, comments, and purchases.

## Tasks
1. **Behavior Simulation**: Predict user engagement (likes) given tweet content.
2. **Content Simulation**: Generate content to elicit desired KPIs from the audience.

## Dataset
- Twitter data from enterprise accounts over the past 5 years
- Includes tweet ID, company name, username, timestamp, tweet text, media links, and user likes

## Problem Statement
### Task 1: Behavior Simulation
- Input: Tweet content (text, company, username, media URLs, timestamp)
- Output: Predicted user engagement (likes)
- Training data size: 300K samples
- Evaluation:
  - Predicting likes for unseen brands
  - Predicting likes for unseen time periods

## Files
- `README.md`: Project overview
- `adobe-cnn-baseline.ipynb`: CNN baseline model
- `adobe-eda.ipynb`: Exploratory Data Analysis
- `adobe-effnet-finetuning.ipynb`: EfficientNet fine-tuning for embeddings
- `adobe-trying-all-models.ipynb`: Experimenting with different models
- `effnet-finetuned.pth`: Fine-tuned EfficientNet model state dict

For more details, refer to the individual notebook files in the repository.
