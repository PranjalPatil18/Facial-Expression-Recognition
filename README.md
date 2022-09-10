# Facial-Expression-Recognition-with-CNNs
Facial Expression Recognition with CNNs on TensorFlow-Keras with OpenCV and Python. Flask app was used to get a web-interface to deploy the algorithm.

# Overview

In this project, I built and trained a convolutional neural network (CNN) in Keras from scratch to recognize facial expressions. I have used the 2013 Facial Emotion Recognition Dataset (https://datarepository.wolframcloud.com/resources/FER-2013). The dataset consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). I used OpenCV to automatically detect faces in images and draw bounding boxes around them. Once the model has been trained, saved, and exported the CNN, I use the trained model to a web interface and perform real-time facial expression recognition on video and image data. The video input can be changed to take in webcam by uncommenting one line of code. Real time perfomance depends on the hardware specifications.

# Project Requirements/ Dependencies
TensorFlow-GPU

OpenCV

Seaborn

Matplotlib

Keras

Livelossplot

Flask

# Command to run code
```
python main.py
```
