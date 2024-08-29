# Sign Language to Text Conversion

This project is a basic college project that converts sign language gestures to text using a machine learning model. The model is trained using a dataset of 8,400 images captured through the webcam. The model was built with the help of Google Teachable Machine.

## Overview

The project consists of two main scripts:

1. **main.py**: This script captures live video from the webcam, detects hand gestures, and converts them into text using a pre-trained model.
2. **Traner.py**: This script is used to collect hand gesture data, which is then used for training the machine learning model.

## Features

- Real-time hand gesture detection.
- Sign language to text conversion.
- Easy to use and extend for further development.

## Installation

To run this project, you'll need to install the following libraries:

- [OpenCV](https://opencv.org/): A library for real-time computer vision.
- [cvzone](https://pypi.org/project/cvzone/): A Python library that makes computer vision tasks easier. It provides modules for hand tracking and gesture recognition.
- [TensorFlow](https://www.tensorflow.org/): An open-source machine learning framework used for training the model.
- [numpy](https://numpy.org/): A library for numerical operations in Python.

### To install these libraries, you can run the following command:

```bash
pip install opencv-python cvzone tensorflow numpy
