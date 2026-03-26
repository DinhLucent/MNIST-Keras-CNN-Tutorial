# MNIST-Keras-CNN-Tutorial

A comprehensive tutorial project demonstrating MNIST digit classification using Keras and TensorFlow. This repository is structured to showcase best practices in project organization, modular source code management, and automated training/testing pipelines.

## ┬┐ Project Overview
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. This project implements a Convolutional Neural Network (CNN) to achieve high accuracy in digit recognition.

## ┬┐ Features
- **Modular Architecture**: Separate modules for dataset handling, model definition, and utility functions.
- **High Accuracy**: Optimized CNN layers achieving >99% accuracy on the test set.
- **Easy Deployment**: Standardized environment setup and clear execution entry points.

## ┬┐ Project Structure
- `src/`: 
    - `train.py`: Script to train the CNN model.
    - `test.py`: Script to evaluate the model on the test dataset.
    - `inference.py`: Standalone script for digit recognition.
    - `model.py`: CNN architecture definition.
    - `dataset.py`: Data loading and preprocessing logic.
    - `utils.py`: Common helper functions.
- `models/`: Directory for storing trained model weights and architectures.

## ┬┐ Getting Started

### 1. Environment Setup
Recommended to use Conda for environment management:
```bash
conda create -n mnist_env python=3.8
conda activate mnist_env
pip install -r requirements.txt
```

### 2. Training the Model
To start the training process, run:
```bash
python src/train.py
```

### 3. Evaluation
After training, evaluate the model accuracy:
```bash
python src/test.py
```

## ┬┐ Results
Expected performance on the MNIST test set:
- **Test Loss**: ~0.027
- **Test Accuracy**: >99.1%

---
*Created by DinhLucent - 2022 (Updated 2026)*
