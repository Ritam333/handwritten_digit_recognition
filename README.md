# Handwritten Digit Recognition Using Neural Networks

This project demonstrates a handwritten digit recognition system using the MNIST dataset and neural network models. The MNIST dataset contains grayscale images of digits (0-9) with corresponding labels.

## Overview

- **Dataset**:
  - The MNIST dataset is used, which includes 60,000 training images and 10,000 testing images.
  - Images are 28x28 pixels, grayscale, and labeled with digits from 0 to 9.
- **Data Preprocessing**:
  - Images are normalized by dividing pixel values by 255 to improve model performance.
  - Flattened 2D images (28x28) into 1D arrays (784 features) for input to the neural network.
- **Model Architecture**:
  1. **Simple Neural Network**:
     - Single dense layer with 10 units and sigmoid activation.
  2. **Advanced Neural Network**:
     - Two dense hidden layers with 100 units each and ReLU activation.
     - Output layer with 10 units and sigmoid activation for classification.
- **Evaluation**:
  - Confusion matrix and heatmap to visualize model predictions.

## Steps in the Code

1. **Dataset Loading**:
   - The MNIST dataset is loaded and split into training and testing sets.
2. **Data Preprocessing**:
   - Normalize the images.
   - Reshape the data for compatibility with the neural network.
3. **Model Training**:
   - Train a simple neural network for 5 epochs.
   - Train an advanced neural network with additional layers for 5 epochs.
4. **Model Evaluation**:
   - Evaluate the model on test data for accuracy.
   - Use a confusion matrix to analyze predictions.
5. **Visualization**:
   - Display a sample image from the dataset.
   - Plot the confusion matrix as a heatmap.

## Outputs

- Training accuracy and loss over 5 epochs for both models.
- Accuracy on the test dataset.
- Confusion matrix showing the performance of the classifier.

---

This project serves as a basic implementation of handwritten digit recognition using neural networks and can be extended for more advanced architectures.
