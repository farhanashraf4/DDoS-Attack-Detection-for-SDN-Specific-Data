# DDoS-Attack-Detection-for-SDN-Specific-Data

## CNN-Based DDoS Detection System for SDN Environments

## Overview
This repository contains a Convolutional Neural Network (CNN)-based system designed for detecting DDoS attacks in Software-Defined Networking (SDN) environments. The system focuses on achieving high accuracy and scalability using TensorFlow and Keras for model development, scikit-learn for data preprocessing, and Python for implementation.

## Key Features
- **Binary Classification:** Achieved >95% accuracy in distinguishing DDoS attacks from normal traffic using the SDN DDoS dataset.
- **Multi-class Classification:** Successfully classified traffic types (TCP, UDP, BENIGN) with >90% accuracy in the SDN Flow dataset.
- **Performance Evaluation:** Confusion matrices and ROC curves demonstrate robust performance, minimizing false positives and maximizing true positives.
- **Real-world Deployment:** Includes plans for integration with mitigation strategies to enhance SDN network resilience against evolving cyber threats.

## Repository Structure
- Jupyter notebook containing CNN model development.
- Script for data preprocessing using scikit-learn.
- Dependencies required for running the project.
- his file providing an overview of the project.

## Dataset
- **SDN DDoS Dataset:** Used for binary classification of DDoS vs. normal traffic.
- **SDN Flow Dataset:** Utilized for multi-class classification of traffic types.

## Future Improvements
- Enhance model efficiency and performance metrics.
- Expand dataset coverage and diversity.
- Incorporate real-time monitoring and adaptive learning mechanisms.
