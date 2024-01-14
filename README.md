# Convolutional Neural Network (CNN) for Image Classification

# Overview
This project implements a Convolutional Neural Network (CNN) using the Keras Sequential model for image classification. The CNN architecture consists of three Convolutional Layers followed by MaxPooling Layers. BatchNormalization layers are included for stable and fast training, and a Dropout layer is added before the final layer to prevent overfitting. The final layer is the output layer, providing soft probabilities for three classes. The model achieves an accuracy close to 95%.


## Dataset

The dataset used for training and testing this model can be found on Kaggle. Please download the dataset from the following link and place it in the `dataset/` directory in the root of the project:

[Dataset on Kaggle](https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images)

## Model

Three Convolutional Layers with MaxPooling Layers
Flatten layer to flatten the output of the convolutional layer
Two Fully Connected Layers
BatchNormalization layers for stable training
Dropout layer to avoid overfitting
Output layer providing soft probabilities for three classes
Results
The model achieves an accuracy of close to 95% on the test dataset.

Feel free to experiment with the model architecture or hyperparameters to further improve performance.
