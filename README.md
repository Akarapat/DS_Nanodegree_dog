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

## Conclusion

In conclusion, this capstone project walk through actual implementation of CNN neural network. There are 8 steps taken: (1) import dataset; (2) detect human faces in images; (3) detect dog in images; (4) create CNN to classify dog breeds from scratch; (5) use CNN to classify dog breeds via transfer learning; (6) create CNN to classify dog breeds via transfer learning; (7) write my own algorithm to check whether human faces or dogs are detected in images and output name of breeds of dog which resemble object in the images; (8) apply the algorithm to real world images. It is found that it is quite difficult to assemble CNN from scratch and it takes a lot of time to train the model. Here, transfer learning helps a lot as it utilizes pre-trained world-class architecture which helps to reduce training time and also drastically improve accuracy of the classifier. Unfortunately, all classifiers are not perfect and there will be some error. An illustration of this is when the face detector algorithm fails to detect the last human face in the previous section.

Further, there are various other ways to improve our CNN architecture for dog breeds: (1) We can try out other pre-trained CNN architecture and there are many of them, for example, VGG-19, Inception and Xception; (2) Dataset used for training can be increased; and (3) Training data set can be augmented, for example, by adding noise into the images or rotating the images, before feeding into CNN model.

## Acknowledgement

I would like to thanks Udacity for giving me the opportunity to participate and complete this project.
