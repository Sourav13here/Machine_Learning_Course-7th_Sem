Digit Recognition using TensorFlow
 Project Overview
This project is a simple machine learning application that recognizes handwritten digits (0–9) from the MNIST dataset using TensorFlow and Keras.
It uses a neural network to classify digits based on image pixel data.


Objective

Load and preprocess the MNIST dataset.

Train a neural network model for digit classification.

Evaluate model performance on test data.

Predict and display results for sample images.

🛠️ Technologies Used
Python

TensorFlow / Keras

NumPy

Matplotlib

Dataset

The project uses the MNIST dataset, which contains:

60,000 training images

10,000 testing images

Image size: 28x28 pixels in grayscale

Steps Implemented
Import required libraries.

Load MNIST dataset.

Normalize pixel values (0–255 → 0–1).

Build a neural network with:

Flatten layer (input: 28×28 → output: 784)

Dense layer (128 neurons, ReLU activation)

Dense output layer (10 neurons, Softmax activation)

Compile the model (Adam optimizer, categorical crossentropy loss).

Train the model on the training set.

Evaluate accuracy on the test set.

Predict the first 10 test images and compare results.

Results
Test Accuracy: ~97% (may vary per run)

Displays first 10 predictions with actual vs predicted labels.
