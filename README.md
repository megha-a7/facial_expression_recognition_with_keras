# facial_expression_recognition_with_keras

This project is a part of Coursera's Guided Project - Facial Expression Recognition with Keras

In this project, we will build and train a convolutional neural network (CNN) in Keras from scratch to recognize facial expressions. The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). We will use OpenCV to automatically detect faces in images and draw bounding boxes around them. Once we have trained, saved, and exported the CNN, we will directly serve the trained model to a web interface and perform real-time facial expression recognition on video and image data.

The project can be braodly divided into two parts -

Build and train a model in Keras for Facial Expression Recognition.
Deploy the model on web using FLASK and run it on videos.

To run the application, run all the files successfully then run python main.py file (click the localhost link to view the results)

## Features
- Explore the Dataset
- Generate Training and Validation Batches
- Create a Convolutional Neural Network (CNN) Model
- Train and Evaluate Model
- Save and Serialize Model as JSON String
- Create a Flask App to Serve Predictions
- Create a Class to Output Model Predictions
- Design an HTML Template for the Flask App
- Use Model to Recognize Facial Expressions in Videos
