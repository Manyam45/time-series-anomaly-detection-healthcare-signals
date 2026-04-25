# time-series-anomaly-detection-healthcare-signals

Deep learning and explainable anomaly detection for healthcare waveform signals using MIMIC-IV.

## Overview
This project develops an anomaly detection framework for healthcare time-series signals using deep learning. It focuses on identifying abnormal patterns in physiological waveform data and generating explainable alerts.

## Dataset
The project uses waveform data from the MIMIC-IV environment. The main signals used in this work are:
- ECG Lead II
- Plethysmography
- Respiration

## Models Used
- Isolation Forest
- Dense Autoencoder
- LSTM Autoencoder

## Workflow
- Data selection and filtering
- Preprocessing and normalization
- Windowing of time-series signals
- Feature engineering
- Baseline anomaly detection
- Deep learning-based anomaly detection
- Explainable anomaly analysis

## Main Result
Among the implemented models, the LSTM Autoencoder gave the most useful final performance, showing stronger sequence-aware anomaly detection and more interpretable anomaly behaviour.


## Note
The raw MIMIC-IV dataset is not included in this repository. Only code, documentation, and project outputs are provided.

## Author
Manyam Shilesh Reddy
