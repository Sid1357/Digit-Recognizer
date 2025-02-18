# Digit Recognizer

## Overview
This project implements a **Digit Recognizer** using a deep learning model trained on the **MNIST dataset**. The MNIST dataset consists of 70,000 images of handwritten digits (0-9), each of size 28x28 pixels, labeled with the corresponding digit.

## Features
- Preprocessing of the MNIST dataset.
- Implementation of a **Convolutional Neural Network (CNN)** for digit classification.
- Model training and evaluation.
- Visualization of predictions.

## Dataset
The dataset is sourced from the **MNIST Handwritten Digits Database**, which is available via TensorFlow/Keras or can be downloaded from [here](http://yann.lecun.com/exdb/mnist/).

## Technologies Used
- Python
- TensorFlow/Keras
- NumPy
- Matplotlib
- Pandas

## Installation
To set up the environment and install dependencies, run:

```bash
pip install tensorflow numpy matplotlib pandas
```

## Usage
Run the following script to train and test the model:

```bash
python digit_recognizer.py
```

## Results
- The model achieves a high accuracy on the MNIST dataset.
- Misclassified images are analyzed for further improvements.
