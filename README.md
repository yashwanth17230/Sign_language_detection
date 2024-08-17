
# Sign Language Detection

This Python project uses OpenCV, MediaPipe, and TensorFlow to detect sign language gestures. It includes scripts for collecting image data, training a model using Google Teachable Machine, and testing the model in real-time. The system can recognize hand gestures via webcam feed for sign language detection.


## overview

This project allows users to collect sign language data, train a model using Teachable Machine, and then test the trained model for real-time sign language detection.
## Features

-**Data Collection**: A Python script to collect sign language images and store them in a specified folder.

-**Model Training**: Integration with Google Teachable Machine for training the model on the collected images.

 -**Model Testing**: A Python script to test the trained model in real-time, detecting sign language through the webcam feed.
## Technologies Used

-**Python**

-**OpenCV**: For capturing and processing images.

-**MediaPipe**: For hand tracking and gesture recognition.

-**TensorFlow**: For using the trained model to predict sign language gestures.

-**Teachable Machine**: For training the model based on the collected images.
## Project Workflow

-**Data Collection**:
A Python script is used to capture images of various hand gestures.
The collected images are stored in a folder specified in the script.

-**Model Training**:
The collected images are uploaded to Google Teachable Machine.
The model is trained on the gestures.
After training, the model is exported for use in the project.

-**Model Testing**:
The trained model is loaded into a Python script.
The model predicts the sign language gestures in real-time using the webcam feed.
## Installation

-**Clone this repository**:git clone https://github.com/yourusername/sign-language-detection.git

-**Install the required dependencies**:
pip install openCV,tensorflow,keras,mediapipe

-**Run the data collection script**:
python data_collection.py
Train the model using Google Teachable Machine and export the trained model.

-**Run the testing script**:
python test.py


## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License - see the LICENSE file for details.




