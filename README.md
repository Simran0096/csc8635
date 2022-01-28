## CSC8635 Machine Learning Project

## Introduction
Convolutional Neural Networks are one of the most used neural networks today. They are being used for audio processing, images processing and so on. Their efficiency over the deep neural networks and low resource consumption made them so popular. In this project, I selected the fashion MNIST dataset from Zalando. The MNIST dataset for digits is mostly considered to be a benchmark for various machine learning models. This dataset acts in a similar way but instead of digits, this dataset contains 60000 training images of various types of clothing and 10000 test images. This dataset is widely used and is built in the Keras library. The images were read using keras modules and then split into the test and training sets to be validated by the CNN. The convolutional neural networks are one of the best and successful approaches to train an image dataset. I designed the CNN and trained the model on the training set and predicted the results for different classes. The results from the neural network were highly accurate. The training and validation accuracy plots showed how the neural network had a constant drop in loss along with an increase in the accuracy. The confusion matrix showed how the classes were predicted on the test data, i.e., how many of the labels were incorrectly classified.

## Pre-requisites
1. First and foremost we require an OS like windows, MacOS, Linux etc.
2. Good GPU for processing the data easily
3. Anaconda as software and jupyter notebook for reproductability
4. Import tenserflow, numpy, seaborn, keras, matplotlib

## Reproducability 
1. Install the above mentioned libraries 
2. Open python notebook and execute the code

## Directory Structure
---
Project

       |-->code
       |    |-->project>ipynb
       |-->report
       |    |-->Abstract.docx
       |    |-->Written Report.docx
       |-->README.md

---