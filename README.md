# eeg-alzheimers-detection-nscnet
Deep learning framework for early detection of Alzheimer's Disease and Frontotemporal Dementia using EEG signal analysis and NeuroSpectral-Connect Net (NSCNet).
# EEG-Based Alzheimer's Detection using NeuroSpectral-Connect Net (NSCNet)

## Overview

This project presents a deep learning framework for early detection of Alzheimer's Disease (AD) and Frontotemporal Dementia (FTD) using electroencephalography (EEG) signals.

The proposed NeuroSpectral-Connect Net (NSCNet) transforms neuro-spectral connectivity features into image representations and applies a custom convolutional neural network for disease classification.

## Research Motivation

Traditional diagnostic approaches such as MRI, PET imaging, and cerebrospinal fluid biomarkers can be expensive or invasive.

EEG provides a non-invasive, affordable, and accessible alternative for early dementia screening.

## Methodology

### EEG Preprocessing

- Band-pass filtering (0.5–45 Hz)
- Common average referencing
- Artifact removal
- Epoching
- Z-score normalization

### Feature Extraction

- Phase Locking Value (PLV)
- Power Spectral Density (PSD)
- Connectivity matrices
- Neuro-spectral image generation (64×64×3)

### Deep Learning Architecture

- Custom CNN Architecture (NSCNet)
- Multi-scale feature extraction
- Attention mechanisms
- Residual connections
- Adam optimizer
- Leave-One-Out Cross Validation (LOOCV)

---

## Results

| Metric | Score |
|----------|----------|
| Mean Accuracy | 76.5% |
| AD F1 Score | 74.3% |
| FTD F1 Score | 72.8% |
| CN F1 Score | 79.4% |


## Technologies Used

- Python
- TensorFlow
- NumPy
- Pandas
- Scikit-Learn
- Deep Learning
- EEG Signal Processing

## Repository Contents

- Research Presentation (PPT)
- Research Poster
- Documentation
- Model Architecture Overview


## Future Work

- Multi-center EEG validation
- MRI + EEG multimodal learning
- Explainable AI using Grad-CAM
- Graph Neural Networks for connectivity analysis
