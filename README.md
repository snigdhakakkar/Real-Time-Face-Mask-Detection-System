# Real-Time-Face-Mask-Detection-System
**Summary: **
Face Mask Detection System built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.

**Problem Statement:**
During these COVID times, indoor places, such as banks, restaurants and stores are legally mandated to ensure that visitors wear masks for their own safety and stop the spread of virus. But the purpose of wearking masks gets defeated when there is a person meeting everyone to see if they are wearing masks. In such a scenario, a real-time face mask detection system comes in picture. It is not a new concept in machine learning. Computer vision has been used in image recognition and face detection systems. A common example is face detection in phone unlocking mechanisms.

The goal of this face mask detection system is to create an image recognition system which understands how image classification works, and it should work with great accuracy so that our model can be applied in the realtime situations. It will work by recognizing the boundaries of the face and predicting whether or not you are wearing a face mask in real-time. We would utilize VideoCapture function in the OpenCV library in Python. The Cascade classifier, designed by OpenCV, can be used to detect the frontal face in live video via detectMultiScale. We will use a while loop to continue capturing images from the webcam.

Based on the performance and accuracy of our model, the result of the binary classifier will be indicated by showing a green rectangle superimposed around the section of the face indicating that the person at the camera is wearing a mask, or a red rectangle indicating that the person on camera is not wearing a mask.


