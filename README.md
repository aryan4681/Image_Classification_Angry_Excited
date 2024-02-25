# Image_Classification_Angry_Excited

## Overview
This project contains an image classification model that distinguishes between images of excited and angry people. It was developed by following a tutorial for a similar task, which involved detecting sad and happy people. The model is built using a Convolutional Neural Network (CNN) and trained on a dataset of labeled images.

## Model
The CNN model is implemented in Python using TensorFlow. It consists of several convolutional layers, max pooling, and dense layers, culminating in a binary classification output.

## Dataset
The dataset comprises two sets of images: 
- Images of excited people.
- Images of angry people.
Each image has been preprocessed and labeled accordingly.

## Installation
To set up your environment to run the code, follow these steps:

1. Clone this repository.
2. Create a virtual environment: `python -m venv env`
3. Activate the environment:
   - Windows: `.\env\Scripts\activate`
   - macOS/Linux: `source env/bin/activate`

## Usage
Run the Jupyter notebook `code.ipynb` to train the model and test its performance.

## Acknowledgments
This project was inspired by a tutorial created by [nicknochnack](https://github.com/nicknochnack/ImageClassification). A huge thanks to him for providing the guidance and resources that helped make this project a reality.

