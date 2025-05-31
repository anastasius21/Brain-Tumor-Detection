# Brain Tumor Detection using CNN

This deep learning project classifies MRI brain scans into two categories: **Tumor** and **No Tumor**. It uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

## Dataset
The dataset consists of brain MRI images organized into two folders: yes/ (with tumor) and no/ (without tumor). Images were preprocessed using ImageDataGenerator with rescaling and validation split.

## Model Architecture
- Multiple Conv2D layers with ReLU activation
- MaxPooling for spatial reduction
- Dropout layers to reduce overfitting
- Fully connected Dense layers
- Output layer with sigmoid for binary classification

## Training
- Used early stopping and model checkpointing
- Trained on 80% of data with 20% for validation
- Achieved high validation accuracy with effective generalization

## Prediction
The model predicts whether a given brain MRI shows signs of a tumor. It takes a new image and classifies it with high confidence.


