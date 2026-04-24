

Handwritten Character Recognition (CNN)

Project Overview

This project recognizes handwritten digits using a Convolutional Neural Network (CNN) trained on the MNIST dataset. The model can predict digits (0–9) from handwritten images.



 Objective

To build a deep learning model that accurately classifies handwritten digits using image processing and CNN.



Dataset

MNIST Dataset

Contains 60,000 training images and 10,000 test images

Digits: 0 to 9

Image size: 28×28 grayscale




Tech Stack

Python 

TensorFlow / Keras 

NumPy

Matplotlib

VS Code




Model Architecture

Convolutional Layer (32 filters)

MaxPooling Layer

Convolutional Layer (64 filters)

MaxPooling Layer

Flatten Layer

Dense Layer (64 neurons)

Output Layer (10 classes)





How It Works

1. Load MNIST dataset


2. Normalize pixel values (0–255 → 0–1)


3. Train CNN model


4. Evaluate model accuracy


5. Predict handwritten digit





Results
Test Accuracy: 98.89%

Correctly predicts handwritten digits




How to Run This Project

Install dependencies

pip install tensorflow numpy matplotlib

 Run the project

python main.py


 Project Structure

handwritten_character_recognition/
│── main.py
│── handwritten_model.h5
│── README.md
│── prediction.png
│── output.png

 Outcome

This project successfully demonstrates how deep learning can recognize handwritten digits with high accuracy using CNN.

