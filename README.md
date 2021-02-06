# Facial Expression Recognition with Keras
In this project-based course, you will build and train a convolutional neural network (CNN) in Keras from scratch to recognize facial expressions. The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). You will use OpenCV to automatically detect faces in images and draw bounding boxes around them. Once you have trained, saved, and exported the CNN, you will directly serve the trained model to a web interface and perform real-time facial expression recognition on video and image data. 
***
special version:

- tensorflow 2.1.0
- open-cv 4.2
- python >= 3.6

***
instruction:
1) Change line 11 in camera.py to "path to video file" if you want recognize emotion on video. Or if you can recognize real-time with web-cam, use 
` cv2.VideoCapture(0)` or another number if you have more than 1 cam.
2) Run `main.py`

***
links:
* [Coursera page](https://www.coursera.org/projects/facial-expression-recognition-keras)
* [Kaggle dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
