# A-Comparison-of-ED-SVM-ANN-and-CNN-for-Face-Recognition-using-SIFT-and-HoG
ED - Eucledian Distance
SVM - Support Vector Machine
ANN - Artificial Neural Network
CNN - Convolutional Neural Network
SIFT - Sift Invariant Transform Features
HoG - Histogram of Gradients

Problem Statement:
- Face recognition using SIFT and HoG features
- Performance comparision of different classifier
- Check robustness against affine transformation (Rotation, Scaling, Translation).

Database:
 - Ahmedabad University student database was used.
 - Total face images: 36 x 16 = 576 (8 original image + 8 sketch image)
 - Joy, fear, disgust, surprise, sadness, anger, cap and goggles
 - No of Person - 36
 - No of image per person in training - 12
 - Total training images - 36*12 = 432
 - No of image per person in testing - 4
 - Total testing images - 36*4 = 144

Preprocessing Database: 
- Images are converted to gray scale
- Resized to 200 x 200

Feature exraction:
- Scale Invariant Feature Transform. 
- Histogram of Oriented Gradient. 
  
  
