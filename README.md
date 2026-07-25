# Flower Species Image Classification using Convolutional Neural Networks (CNN)

## Project Overview

This project develops a Convolutional Neural Network (CNN) to classify images of flowers into five different species using TensorFlow.

The model was trained from scratch on the **TensorFlow Flowers (tf_flowers)** dataset and several hyperparameters were tuned to improve classification performance while reducing overfitting.

---

## Objectives

- Build a CNN for image classification
- Compare different hyperparameter configurations
- Reduce overfitting using regularisation techniques
- Evaluate the model using classification metrics
- Compare Adam and SGD optimisers

---

## Dataset

**Dataset:** TensorFlow Flowers (tf_flowers)

The dataset contains **3,670 labelled images** belonging to five flower species:

- Daisy
- Dandelion
- Rose
- Sunflower
- Tulip

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# CNN Architecture

The model consists of:

- Three Convolutional Layers
- Max Pooling
- Batch Normalisation
- Dropout
- Dense Layer
- Softmax Output Layer

---

# Hyperparameter Tuning

The following parameters were investigated:

- Learning Rate
- Batch Size
- Kernel Size
- Stride
- Pooling Method
- Batch Normalisation
- Optimiser

---

# Results

Best model configuration:

| Parameter | Value |
|------------|--------|
| Learning Rate | 0.001 |
| Batch Size | 128 |
| Kernel Size | 5×5 |
| Stride | 2×2 |
| Optimiser | Adam |

### Best Validation Accuracy

**72.9%**

---

## Evaluation

Model evaluation includes:

- Accuracy Curves
- Loss Curves
- Confusion Matrix
- Classification Report

---

# Repository Contents

- Jupyter Notebook
- Project Report
- Figures
- Requirements File

---

## Author

**Cynthia Amarachi Eze**
