# Handwritten-Digit-Recognition

A machine learning project for recognizing handwritten digits (0-9) using the MNIST dataset, built with Python and TensorFlow/Keras.

## Features
- Preprocess the MNIST image data (28×28 grayscale).
- Build and train a neural network model (Dense).
- Apply regularization techniques (such as L2) to improve generalization.
- Evaluate model accuracy on test data and save the trained model.
- Visualize sample input images and model predictions.

## Model Architecture
- **Input**: 28×28 grayscale image  
- **Hidden layers**: Dense (e.g., ReLU)  
- **Output layer**: 10 classes (digits 0-9)  
- **Optimizer**: Adam  
- **Loss Function**: Sparse Categorical Crossentropy  
- **Metrics**: Accuracy  
- **Regularization**: L2 applied to kernel weights  

##  Dataset
We use the classic MNIST of handwritten digits, containing:
- 60,000 training images  
- 10,000 test images  
- Grayscale images sized 28×28 pixels  

##  Requirement
- tensorflow
- keras
- numpy
- matplotlib

