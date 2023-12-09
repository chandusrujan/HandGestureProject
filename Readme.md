# Hand Gesture Recognition for Music Control

## Introduction
This repository contains the dataset, trained model, and application code for a hand gesture recognition system designed to control music playback. The system interprets specific hand gestures as commands, allowing for a hands-free music experience.

## Contents
- `train.zip`: A zipped file containing the training dataset images.
- `test.zip`: A zipped file containing the test dataset images.
- `model.h5`: The pre-trained model file.
- `handchandu.ipynb`: The Jupyter notebook containing the application code for gesture recognition.
- `MLFinaltrain.ipynb`: The Jupyter notebook containing the code used for model training.

## Dataset
The `train.zip` and `test.zip` files contain images of hand gestures used to train and test the recognition model. Each gesture corresponds to a control command for music playback.

## Model
The `model.h5` file is a Keras model that has been trained on the images from the `train.zip` dataset. It can predict hand gestures with high accuracy.

## Application Code
`handchandu.ipynb` is a Jupyter notebook that demonstrates how to load the pre-trained model and use it to recognize hand gestures in real-time using a webcam.

## Model Training Code
`MLFinaltrain.ipynb` is a Jupyter notebook containing the training code for the hand gesture recognition model.

## Installation
To run the notebooks, you need to have Jupyter installed on your machine. You can install Jupyter via Anaconda or with pip:

```bash
pip install notebook
```

After installation, run the following command to start Jupyter:

```bash
jupyter notebook
```

## Usage
To use the application, follow these steps:

1. Unzip the `train.zip` and `test.zip` files to obtain the datasets.
2. Open the `handchandu.ipynb` notebook in Jupyter and run the cells.
3. To retrain the model, run the cells in `MLFinaltrain.ipynb`.

## Requirements
- Python 3.x
- TensorFlow
- OpenCV
- Pygame
- Matplotlib
- NumPy

Install the necessary libraries using pip:

```bash
pip install tensorflow opencv-python pygame matplotlib numpy
```
