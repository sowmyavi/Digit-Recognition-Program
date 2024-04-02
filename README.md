# Digit-Recognition-Program

## Overview
This project involves developing a deep learning model capable of recognizing sequences of digits from images. We aim to train the model using synthetic datasets, created by merging character images from the MNIST dataset, to identify sequences of up to five digits.

## Objective
The main goal is to implement a model that can accurately identify sequences of handwritten digits, enhancing the capabilities of optical character recognition (OCR) systems. By introducing an additional 'blank' character, the model can handle sequences of variable lengths.

## Data Description
The model is trained and tested on synthetic datasets derived from the MNIST dataset. These synthetic datasets consist of images containing sequences of one to five digits, with additional 'blank' spaces used to fill sequences shorter than five digits.

## Methodology
**Data Preparation**: Synthetic datasets are created by merging images from the MNIST dataset to form sequences of digits.

**Model Architecture**: A deep learning model with five classifiers is implemented in Keras, each predicting a digit or a blank in the sequence.

**Training and Testing**: The model is trained on 60,000 synthetic training images and tested on 10,000 synthetic test images.

## Technologies Used
Python
Keras
NumPy
TensorFlow
Scikit-Image
Matplotlib

## Results
The model achieved an individual digit recognition accuracy of 95.91% and was able to correctly predict entire sequences of digits 81.4% of the time. These results demonstrate the model's effectiveness in recognizing digit sequences from images.
