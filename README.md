# Emotion Recognition Model

This is a Python implementation of an emotion recognition model using machine learning techniques. The model is designed to analyze facial expressions and classify them into different emotion categories such as happy, sad, angry, etc.

# Dependencies

The following Python packages are required to run the emotion recognition model:

numpy
opencv-python
keras

# Dataset
The emotion recognition model was trained on the FER-2013 dataset, which consists of 35,887 grayscale images of faces with 48x48 pixels. Each image is labeled with one of seven emotion categories: angry, disgust, fear, happy, sad, surprise, or neutral.

The dataset is provided in a CSV file format with two columns: emotion and pixels. The emotion column contains an integer label between 0 and 6 corresponding to the emotion category, while the pixels column contains a string of comma-separated pixel values for each image.

To preprocess the dataset, we first split the pixels column into separate pixel values and reshape them into a 48x48 matrix. We then normalized the pixel values to be between 0 and 1 and split the data into training, validation, and test sets.

# Usage
To use the emotion recognition model, you can run the emotion_detector.py script. This script takes an input image path as an argument and outputs the predicted emotion category.
