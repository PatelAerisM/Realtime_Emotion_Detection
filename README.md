# Realtime_Emotion_Detection
This project implements a Convolutional Neural Network (CNN) for emotion detection using images. The CNN is trained to classify facial expressions into seven different emotions: anger, disgust, fear, happiness, sadness, surprise, and neutral.


## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Results](#results)
- [Usage](#usage)

## Introduction

This project aims to demonstrate the process of building and training a CNN model for emotion detection. The project uses the Keras library to define the model architecture and train it on a custom dataset of facial expression images.

## Setup

1. Clone this repository to your local machine.
2. Install tensorflow, opencv, pandas, and numpy.
3. Download the dataset and adjust the `folder_path` in the code to match the dataset location.
4. Run the main.py file to start the application.

## Dataset

The project uses a custom dataset of facial expression images categorized into seven classes: anger, disgust, fear, happiness, sadness, surprise, and neutral. There are training and validation sets created from the dataset. Make that the dataset is located in the correct directory, as specified by the code.

## Model Architecture

The CNN model consists of multiple convolutional and pooling layers, followed by fully connected layers. Batch normalization and dropout layers are incorporated to prevent overfitting.

## Training

The model is compiled using the Adam optimizer and categorical cross-entropy loss function. Callbacks including ModelCheckpoint, EarlyStopping, and ReduceLROnPlateau are used to monitor and enhance training.

## Results

After training, the model's performance is evaluated on the validation set. Plots are generated to visualize the loss and accuracy trends during training.

## Usage

To use this project:

1. Follow the setup instructions to prepare your environment.
2. Adjust any hyperparameters or paths as needed.
3. Run the code and notice the results.


