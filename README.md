# DDoS-Attack-Detection-for-SDN-Specific-Data

**CNN-Based DDoS Detection System for SDN Environments**

## Overview
This repository contains a Convolutional Neural Network (CNN)-based system designed for detecting DDoS attacks in Software-Defined Networking (SDN) environments. The system focuses on achieving high accuracy and scalability using TensorFlow and Keras for model development, scikit-learn for data preprocessing, and Python for implementation.

## Key Features
- **Multi-class Classification:** Successfully classified traffic types (TCP, UDP, BENIGN) with >95% accuracy in the SDN Flow dataset.
- **Performance Evaluation:** Confusion matrices and ROC curves demonstrate robust performance, minimizing false positives and maximizing true positives.
- **Feature Importance Graph** A visual representation ranking features by their significance in predicting DDoS attacks, using a Random Forest classifier to highlight the most critical features for accurate classification in an SDN environment.

## Repository Structure
- Jupyter notebook containing CNN model development.
- Script for data preprocessing using scikit-learn.
- Dependencies required for running the project.

## Dataset
- **SDN DDoS Dataset:** Utilized for multi-class classification of traffic types.

## Future Improvements
- Enhance model efficiency and performance metrics.
- Expand dataset coverage and diversity.
- Incorporate real-time monitoring and adaptive learning mechanisms.
