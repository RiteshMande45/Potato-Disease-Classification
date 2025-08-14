# Potato-Disease-Classification
A Potato Disease Classification project is typically a computer vision and machine learning project that identifies diseases in potato plants based on images of their leaves or tubers.

### Overview

This project detects and classifies diseases in potato plants from leaf images using deep learning.
It classifies leaves into three categories:
a.Healthy  
b.Early Blight  
c.Late Blight  
It helps farmers quickly identify plant diseases and take action to reduce crop loss.

### Dataset

a.Images of potato leaves labeled as Healthy, Early Blight, or Late Blight.  
b.Data preprocessing steps include:  
  1.Resizing images  
  2.Normalizing pixel values  
  3.Data augmentation (rotation, flipping, zooming)  

### Model Training

a.Frameworks used: TensorFlow/Keras, OpenCV, NumPy  
b.Training steps in notebook:  
  1.Import libraries and dataset  
  2.Preprocess and augment images  
  3.Split data into training and validation sets  
  4.Build a Convolutional Neural Network (CNN)  
  5.Compile the model (categorical crossentropy + Adam optimizer)  
  6.Train the model for multiple epochs  
  7.Evaluate model accuracy  
  8.Save the trained model as potato_model.h5  

### Benefits

a.Quickly detects potato diseases from leaf images.  
b.Reduces crop loss by enabling early intervention.  
c.Can be expanded to detect other crop diseases in the future.  
