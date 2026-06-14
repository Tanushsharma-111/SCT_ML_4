# Hand Gesture Recognition Using CNN

## Project Overview
This project implements a Hand Gesture Recognition System using a Convolutional Neural Network (CNN). The model is trained on the LeapGestRecog dataset to classify different hand gestures from images.

## Features
- Image preprocessing and resizing
- Label encoding and data preparation
- CNN-based gesture classification
- Model training and evaluation
- Confusion matrix visualization
- Model saving and loading
- Gesture prediction on test images

## Dataset
Dataset Used: LeapGestRecog

The dataset contains hand gesture images belonging to multiple gesture classes collected from different individuals.

## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Model Architecture
- Conv2D (32 filters)
- MaxPooling2D
- Conv2D (64 filters)
- MaxPooling2D
- Flatten Layer
- Dense Layer (128 neurons)
- Dropout (0.5)
- Output Layer (Softmax)

## Workflow
1. Load dataset
2. Preprocess images
3. Encode labels
4. Split training and testing data
5. Train CNN model
6. Evaluate model performance
7. Visualize results
8. Save trained model

## Results
The model is trained to recognize multiple hand gesture classes and evaluated using:
- Accuracy Score
- Classification Report
- Confusion Matrix
## How to Run

- Install required dependencies.
- Download the LeapGestRecog dataset.
- Open the notebook in Jupyter Notebook or Google Colab.
- Run all cells in order.
- ## Supported Gestures

- Palm
- Fist
- Thumb Up
- Thumb Down
- Index
- L Shape
- OK Sign

## Author
Tanush
