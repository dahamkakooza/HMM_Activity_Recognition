# Human Activity Recognition with Hidden Markov Models

## Overview
This project implements a Hidden Markov Model (HMM) for recognizing human activities from smartphone accelerometer and gyroscope data.

## Activities Recognized
- Standing
- Walking
- Jumping
- Still

## Dataset
- **Training Data:** 408 samples per activity
- **Test Data:** 408 samples per activity
- **Sensors:** Accelerometer (m/s²), Gyroscope (rad/s)
- **Sampling Rate:** 50 Hz (resampled)

## Features Extracted
### Time-Domain
- Mean
- Standard Deviation
- RMS
- SMA
- Peak-to-Peak

### Frequency-Domain
- Dominant Frequency
- Spectral Energy
- Spectral Entropy

## Results
- **Overall Accuracy:** 86%

| Activity | Sensitivity | Specificity | Accuracy |
|----------|-------------|-------------|----------|
| Standing | 0.85 | 0.92 | 0.90 |
| Walking | 0.78 | 0.95 | 0.88 |
| Jumping | 0.82 | 0.90 | 0.86 |
| Still | 0.75 | 0.88 | 0.82 |

## Repository Structure

├── data/ # Raw sensor data
├── notebooks/ # Jupyter notebook
├── report/ # Project report (PDF)
├── models/ # Trained model
├── results/ # Evaluation results
└── README.md #