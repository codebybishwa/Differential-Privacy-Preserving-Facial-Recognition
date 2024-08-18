# Differential Privacy-Preserving Facial Recognition System

## Overview

This project implements a **Differential Privacy-Preserving Facial Recognition System** that leverages advanced machine learning techniques to identify individuals while ensuring their privacy. By integrating differential privacy techniques, the system addresses critical issues related to bias, privacy concerns, and adversarial vulnerabilities commonly associated with traditional facial recognition systems.

## Key Features

- **Facial Recognition**: Utilizes a Convolutional Neural Network (CNN) to accurately identify individuals from images.
- **Privacy-Preserving Mechanisms**: Adds noise to facial data to prevent the disclosure of sensitive personal information, ensuring individual privacy while maintaining system accuracy.
- **Bias Mitigation**: Implements fairness-aware learning algorithms to reduce bias in model predictions, addressing the issue of higher error rates for specific demographic groups.
- **Adversarial Robustness**: Enhances the model's resilience against adversarial attacks and spoofing attempts, making it more secure and reliable.

## Technologies Used

- **Python**: The primary programming language for model development.
- **PyTorch**: A deep learning framework used to build and train the CNN model.
- **Opacus**: A library for implementing differential privacy in PyTorch models.
- **CelebA Dataset**: A large-scale dataset used for training and evaluating the facial recognition model.
