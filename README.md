[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"


## Project Overview

In this project, a convolution neural network (CNN) pipeline is implemented to contruct a dog breed predictor. Given an image of a dog, the algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]

This is project from the Udacity Data Scientist Nanodegree, and it is built based on the instructions provided by Udacity in this repository: https://github.com/udacity/dog-project


## Motivation 

The educational goal of this project is to excercise implementing CNN models using Python’s Keras library. 3 CNN models are trained in this notebook: 1 built from scratch, the other 2 are transfer learning models based on VGG-16 and ResNet 50.


## Libraries Used:
The following libraries are used in this project:
- Machine Learning: Sklearn, Keras, cv2
- PyData: Numpy, matplotlib, Seaborn
- Utilities: glob, random, PIL, tqdm


## Files Description:
- dog_app.ipynb: The main notebook where CNN models are trained 
- extract_bottleneck_features.py: utility functions for transfer learning models
- saved_models directory contains weights from trained CNN models with best val-loss values
- image directory contains test images and images used in text section of the notebook
- haarcascades directory contains a .XML file needed for OpenCV cascade classifier
- bottleneck_features directory contains bottleneck feature files needed for transfer learning models


## Project Instructions

The IPython notebook in this repository is an end result of implementing the CNN according to instructor notes. To build the pipeline from the beginning, please refer to the README file in the Udacity repository provided above.


## Analysis

An technical write-up of the pipelines and the findings can be find here: https://medium.com/@yu90/dog-breed-classifier-be589a777cdd


## Summary 

With the ResNet-50 transfer learning CNN model, an accuracy of 80% is achieved after 20 epochs of training.


## Acknowledgement 

Credits to Udacity for the template notebook.
