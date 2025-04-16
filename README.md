# MajorProject
# Enhanced Multiscale Convolutional Neural Network for Human Behavior Recognition

## 📌 Project Overview

This project focuses on building an advanced deep learning model to recognize human behaviors from sensor-based time-series data using an **Enhanced Multiscale Convolutional Neural Network (MCNN)** integrated with a hybrid **CNN + GRU + Bidirectional** architecture. It addresses the limitations of conventional CNNs and RNNs in handling spatiotemporal dependencies by combining 3D CNNs, depthwise separable convolutions, and sequential modeling to improve classification accuracy.

---

## 🧠 Key Features

- Multiscale feature extraction with 3D CNNs
- Hybrid model architecture: CNN + GRU + Bidirectional for spatial and temporal learning
- Sensor data preprocessing with normalization, PCA, and augmentation
- Evaluation using Accuracy, Precision, Recall, and F1-score
- Tested on the UCI Human Activity Recognition (HAR) dataset

---

## 🏗️ Model Architecture

- **3D CNN**: Captures spatial and temporal patterns simultaneously
- **Depthwise Separable Convolutions**: Reduces computational complexity
- **GRU Layer**: Learns long-term temporal dependencies
- **Bidirectional Layer**: Processes sequences forward and backward
- **Dense + Softmax**: Outputs class probabilities for human activities

---

## 📂 Dataset

- **UCI HAR Dataset**: Contains accelerometer and gyroscope data from 30 participants performing 6 activities:
  - Walking
  - Walking Upstairs
  - Walking Downstairs
  - Sitting
  - Standing
  - Laying

