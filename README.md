# Data Science Nanodegree Project: Dog Breed Classifier

## Project Overview

The goal of this project is to build covolutional neural networks (CNN) to classify breeds of dogs.  CNN is often used in image classification because it takes proximity of different pixel in images into account when classifying images.  CNN is both build from scratch and also by utilizing famous CNN architecture such as VGG16 and Resnet50.  Finally, the trained CNN is also used classify human faces according to their similarity to different breed of dogs.  This project is a project chosen as the capstone project of Udacity's Data Scientist Nanodegree.

## Libraries used in the project
- Keras
- OpenCV
- Matplotlib
- Numpy

## File descriptions
- dog_app.ipynb: Jupyter notebook containing implementation of CNN to classify breeds of dogs
- dog_app.html: Jupyter notebook rendered in html format
- weights.best.from_scratch.hdf5, weights.best.VGG16.hdf5, weights.best.Resnet50.hdf5: Weight of CNN model build from scratch, and CNN model via transfer learning utilizing VGG16 and Resnet50 architecture
- image files (dog1.jpg, dog2.jpg, dog3.jpg, human1.jpg, human2.jpg, human3.jpg): These images are used to test the model

## Findings

The model via transfer learning utilziing Resnet50 architecture achieve an accuracy of more than 60%.  It is then further used to classify dog and human images download from the Internet.  Unforunately, the algorithm is unable to recognize some of the human faces
