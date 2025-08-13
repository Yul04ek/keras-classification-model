# Handwritten Digit Classification Using Keras

This project demonstrates how to build and train a simple neural network to classify handwritten digits (0–9) using the TensorFlow/Keras library.

## Description

The model is trained on the MNIST dataset, which contains 60,000 images for training and 10,000 images for testing.  
A fully connected neural network is used, with Dropout layers to prevent overfitting and L2 regularization for better generalization.

## Technologies Used

- Python 3.10+
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- JupyterLab

## Getting Started

Clone the repository:

git clone https://github.com/your-nickname/repository-name.git  
cd repository-name

Install dependencies:

pip install -r requirements.txt

## Usage

Download the trained model file (model.h5) and run the script to classify digits:

python digit_1.py --model model.h5

You can also test the model on custom input images or visualize predictions using the built-in plotting functions.

## Files

- digit_1.py — main script for loading and testing the model  
- model.h5 — trained model file  
- requirements.txt — list of dependencies  
- README.md — project documentation

## License

This project is licensed under the MIT License.
