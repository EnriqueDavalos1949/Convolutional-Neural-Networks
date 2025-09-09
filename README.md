# MNIST CNN Handwritten Digit Classifier

This repository contains a **Convolutional Neural Network (CNN)** implemented in **TensorFlow** for classifying handwritten digits from the **MNIST dataset**.  
It includes preprocessing, model training, visualization of sample images, and conversion to **TensorFlow.js** for web deployment.

## Features
- Data normalization and batching using TensorFlow Datasets.
- CNN architecture with Conv2D, MaxPooling2D, Dropout, and Dense layers.
- Training with Adam optimizer and sparse categorical crossentropy.
- Visualization of the first 25 samples from the training dataset.
- Export trained model to Keras H5 format and conversion to TensorFlow.js.

## Repository Structure
- `notebooks/` → Jupyter notebooks for interactive exploration.
- `src/` → Python scripts for training and preprocessing.
- `models/` → Trained Keras models (`numeros_conv.h5`).
- `tfjs_model/` → TensorFlow.js converted model for web use.

## Requirements
- Python 3.9+  
- TensorFlow  
- TensorFlow Datasets  
- Matplotlib  
- TensorFlow.js (for conversion)

Install dependencies:
```bash
pip install -r requirements.txt


