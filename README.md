# Faces
Detection and Recognition of faces using ML Classification Algorithms, Neural Networks, Siamese Network and face-recognition library at Python

## Phase 1
1) Face Detection using HAAR-LIKE  features
2) Finding similarity between two faces using Classification algorithms (1==similar && 0==dissimilar)
3) Using the concept of Principle Component Analysis for building Eigen faces over the dataset lfw_people from sklearn.datasets with min_faces_per_person = 50
4) Using a Neural Network to distinguish between 12 people faces using softmax in the outer layer.
5) Building the same neural network using PyTorch
6) Implement a Siamese Network (Didn't train it)

The above implementations can be found in [Faces.ipynb](Faces.ipynb) and [Siamese_network.ipynb](Siamese_Network.ipynb)

I have also made a video for explaining the [PHASE 1](https://youtu.be/3Kqd5SJbG7s)

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/3Kqd5SJbG7s/0.jpg)](https://www.youtube.com/watch?v=3Kqd5SJbG7s)

## Phase 2
7) Face Detection and recognition on the webcam. (Done using python library face_recognition)

The above implementation can be found in [face_recognition_on_webcam.py](face_recognition_on_webcam.py)
