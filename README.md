# Bilingual Depression Detection using XLM-R with Explainable AI

## Overview
This project detects depression from social media posts written in English and Bangla using a multilingual transformer model (XLM-RoBERTa).

Explainable AI techniques such as Attention Visualization and LIME are used to interpret predictions.

## Features
- Multilingual depression detection
- XLM-RoBERTa transformer model
- Explainable AI (LIME + Attention)
- Cross-lingual evaluation
- Social media text analysis

## Dataset
The dataset combines:

- English Reddit Depression Dataset
- Bangla Social Media Depression Dataset (BSMDD)

Labels:
0 → Normal  
1 → Depressed

## Model
Model used:
XLM-RoBERTa

Training parameters:
- Max length: 128
- Batch size: 16
- Learning rate: 2e-5
- Loss: Binary Cross Entropy
- Optimizer: AdamW

## Results
Accuracy: 92%  
AUC: 0.97

## Explainability
- Attention heatmaps
- LIME feature importance

## Run the Project

Install dependencies:

pip install -r requirements.txt

Run notebook:

FDD.ipynb

## Authors
- Sudeepa R
- Varun S S
- Vikas Padmashali Lakshmipathi
- Vikranth Subramanyam
