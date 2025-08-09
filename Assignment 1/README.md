# Digit Recognition using TensorFlow

## Project Overview  

This project is a simple **machine learning application** that recognizes handwritten digits (0–9) from the **MNIST dataset** using **TensorFlow** and **Keras**.  
It uses a neural network to classify digits based on image pixel data.  

## Objective  

- Load and preprocess the MNIST dataset.  
- Train a neural network model for digit classification.  
- Evaluate model performance on test data.  
- Predict and display results for sample images.  

## Technologies Used  
- **Python**  
- **TensorFlow / Keras**  
- **NumPy**  
- **Matplotlib**  

## Dataset  
The project uses the **MNIST dataset**, which contains:  
- **60,000** training images  
- **10,000** testing images  
- Image size: **28x28 pixels** in grayscale  

## Steps Implemented  
1. **Import required libraries**  
2. **Load MNIST dataset**  
3. **Normalize pixel values** (0–255 → 0–1)  
4. **Build a neural network** with:
   - Flatten layer (input: 28×28 → output: 784)  
   - Dense layer (128 neurons, ReLU activation)  
   - Dense output layer (10 neurons, Softmax activation)  
5. **Compile the model** (Adam optimizer, categorical crossentropy loss)  
6. **Train the model** on the training set  
7. **Evaluate accuracy** on the test set  
8. **Predict sample images** and compare results  

##  Results  
- **Test Accuracy:** ~97% (may vary per run)  
- Displays first 10 predictions with actual vs predicted labels.  

