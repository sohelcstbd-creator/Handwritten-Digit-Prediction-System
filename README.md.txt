# MNIST Handwritten Digit Classification using PyTorch

## Project Overview
This project focuses on recognizing handwritten digits (0-9) using an Artificial Neural Network (ANN) built with PyTorch.

The model takes a 28x28 grayscale image as input and predicts the corresponding digit.

## Dataset
- Dataset: MNIST
- Image Size: 28x28 pixels
- Number of Classes: 10 (0-9)
- Input Features: 784

## Technologies Used
- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- idx2numpy

## Model Architecture
The ANN model consists of:
- Input Layer: 784 neurons
- Hidden Layer 1: 128 neurons with ReLU
- Hidden Layer 2: 64 neurons with ReLU
- Output Layer: 10 neurons

## Model Training
- Loss Function: CrossEntropyLoss
- Optimizer: Adam
- Evaluation: Train Loss, Test Loss and Accuracy

## Evaluation
The model was evaluated using:
- Training Loss
- Testing Loss
- Accuracy
- Confusion Matrix

## Custom Image Prediction
The trained model was also tested using a custom handwritten digit image. The model successfully predicted the uploaded digit.

## Project Files
- `MNIST_Classification.ipynb` - Complete project code
- `mnist_model.pth` - Trained model weights
- `requirements.txt` - Required Python libraries

## How to Run
1. Clone this repository.
2. Install dependencies:

   `pip install -r requirements.txt`

3. Open the Jupyter Notebook.
4. Run the cells step by step.

## Author
Sohel Mahamud

GitHub: https://github.com/sohelcstbd-creator