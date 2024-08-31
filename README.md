# Nexus Labs EEG Research sandbox
## Dataset Information
The dataset used in the program is from [openneuro](https://openneuro.org/datasets/ds004504/versions/1.0.6), containing resting state closed eyes recordings from 88 subjects: 36 of them were diagnosed with Alzheimer's disease (group A), 23 were diagnosed with Frontotemporal dementia (F), and 29 are healthy subjects (C).

## Overview
- **compute_eeg_spectra.py** calculates the alpha, beta, gamma, delta, epsilon power band across each EEG recording and each lead to generate spectral features outputted to **eeg_spectra.csv**
- **eeg_spectra_lr_pipeline.py** runs basic logistic regression pipeline on the spectral features and outputs the ROC curve and some basic evaluation metrics
- **eda.py** generates some summary plots for the current data, and provides function to view EEG waveforms

## Summary
Visit [LinkedIn post](https://www.linkedin.com/posts/charlene-chenn_ai-for-detecting-dementia-using-resting-state-activity-7173436597105840128-P-Ra?utm_source=share&utm_medium=member_desktop) for more information on the presentation and collaboration for this project.
