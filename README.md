# Early-Stage Alzheimer’s Disease Detection using Machine Learning

## Overview
This project is based on my final-year undergraduate project focused on **early-stage Alzheimer’s disease detection using handwriting (HW) data**.
The work explores machine learning and deep learning approaches with a strong emphasis on **Reservoir Computing (RC)** for efficient and accurate classification.

This repository contains a **reconstructed implementation** that highlights the core methodology, modeling approach, and results from the academic project.

---

## Problem Statement
Alzheimer’s disease has an insidious onset and is difficult to diagnose in its early stages.
Traditional diagnostic techniques such as PET scans and cerebrospinal fluid analysis are intrusive and expensive.

The goal of this project is to **detect early-stage Alzheimer’s disease using handwriting-based temporal data**, enabling a non-invasive, cost-effective, and scalable diagnostic approach.

---

## Dataset
- Handwriting (HW) temporal data
- Features extracted from writing dynamics such as motion patterns and timing
- Classification target:  
  - Healthy Control  
  - Early-Stage Alzheimer’s Disease (ES-AD)

> Note: This repository uses reconstructed/demo data for implementation purposes.

---

## Methodology
1. Data preprocessing and normalization  
2. Feature extraction from handwriting signals  
3. Model training and evaluation  
4. Performance comparison based on **accuracy vs computational efficiency**

---

## Models Explored
- **Reservoir Computing (RC) – Primary model**
- Bidirectional LSTM (BiLSTM)
- Convolutional Neural Network (CNN)

Reservoir Computing was chosen as the primary approach due to:
- Reduced training complexity
- Lower energy consumption
- Competitive classification accuracy

---

## Results Summary
- Reservoir Computing achieved **~85% classification accuracy**
- BiLSTM achieved slightly higher accuracy (~88%) at significantly higher computational cost
- RC demonstrated **lower training, optimization, and inference costs**, making it more efficient and environmentally friendly

---

## Tech Stack
- Python
- NumPy, Pandas
- Scikit-learn
- PyTorch (for deep learning models)

---

## Notes
## Implementation Status
The original implementation for this project was developed as part of an academic final-year project.

This repository currently focuses on:
- Problem formulation
- Methodology
- Model comparison and results

A cleaned and reproducible code implementation may be added in a future iteration.

This repository is intended for **academic and demonstration purposes**.
The implementation reflects the original project’s approach while focusing on clarity and reproducibility rather than full-scale deployment.
