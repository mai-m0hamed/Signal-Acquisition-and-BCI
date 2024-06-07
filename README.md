# EEG-Based Eye Movement Monitoring System

## Project Overview

This project aims to develop a laptop screen with an integrated LCD and alarm system that monitors the user's eye movements using EEG brain signals. The system is designed to enhance user alertness and prevent drowsiness by triggering an alarm if the user's eyes are closed for 10 seconds. The project is divided into two main parts: EEG data processing and model development.


## Introduction

The EEG-Based Eye Movement Monitoring System processes raw EEG data to monitor and analyze eye movements. The project follows these steps:

### Part 1: EEG Data Processing

1. **EEG Data Acquisition**: Search for raw EEG brain signals suitable for the project.
2. **Signal Preprocessing**: Process raw EEG data to remove noise, filter unwanted frequencies, and enhance signal quality. Techniques include artifact removal, bandpass filtering, and baseline correction.
3. **Feature Extraction**: Extract relevant features from preprocessed EEG signals, such as power spectral densities, band power ratios, or statistical measures like mean and variance.
4. **Signal Visualization**: Develop a simple GUI to compare filtered and unfiltered EEG signals.

### Part 2: Model Development

1. **Model Training**: Train a machine learning model (Support Vector Machine and KNN) using extracted features and labeled data. The model associates specific brain patterns with intended mental tasks.
2. **Actuator Control**: Translate model output into appropriate actions using an actuator control mechanism.

## System Requirements

- **Hardware**: 
  - Laptop with an integrated LCD screen
  - Alarm system (e.g., buzzer)
- **Software**: 
  - Python 3.x
  - Libraries: NumPy, SciPy, scikit-learn, Matplotlib, PyQt5 (for GUI), and any EEG-specific libraries for data acquisition
## Setup and Usage
- EEG Data Acquisition: Obtain suitable raw EEG data for the project.
- Signal Preprocessing: Run preprocessing scripts to clean and enhance EEG signals.
- Feature Extraction: Extract relevant features from preprocessed signals using provided scripts.
- Model Training: Train machine learning models using extracted features and labeled data.
- Real-time Classification: Deploy trained models to classify ongoing EEG signals in real-time.
- Actuator Control: Implement actuator control mechanisms to translate model predictions into actions.in our case the actuator was an integrated LCD and alarm system that monitors the user's eye movements using EEG brain signals to enhance user alertness and prevent drowsiness by triggering an alarm if the user's eyes are closed for 10 seconds. 
