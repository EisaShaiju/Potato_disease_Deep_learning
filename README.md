# **Potato Disease Classification Using Deep Learning**
This project utilizes deep learning techniques to classify potato plants into three categories based on images: Late Blight, Early Blight, or Healthy. The classification is performed using a convolutional neural network (CNN) trained on a dataset of potato plant images affected by various diseases.

## Table of Contents
Project Overview
Dataset
Model Architecture
Project Overview
The model can predict whether a potato plant is infected with Late Blight, Early Blight, or is Healthy based on images provided by the user. Early detection of these diseases is crucial for farmers to take necessary actions and prevent widespread damage to crops.

## Dataset 
The dataset consists of labeled images of potato plants categorized into three classes:

Late Blight: Images of potato plants affected by late blight disease.
Early Blight: Images of potato plants affected by early blight disease.
Healthy: Images of healthy potato plants with no visible disease.
The dataset was collected from kaggle.

## Model Architecture
The model uses a Convolutional Neural Network (CNN) architecture for image classification. The architecture was designed to efficiently learn the features in the potato plant images that distinguish between the three classes: Late Blight, Early Blight, and Healthy.

Input Layer: Accepts images of potato plants.
Convolutional Layers: Extracts relevant features from the input images.
Pooling Layers: Reduces the dimensionality of the features.
Fully Connected Layers: Classifies the extracted features into one of the three categories.
Output Layer: Provides the final classification output (Late Blight, Early Blight, or Healthy).
