# Character-level Convolutional Networks for Text Classification

## Introduction

Here is my tensorflow implementation of the paper "Character-level Convolutional Networks for Text Classification". There is only one modification I made: Instead of using SGD, I use Adam as the optimizer, since it is well-recognized that Adam outperforms SGD in NNs. The dataset used in default mode is AG’s News with 4 classes. 

## Preparation

For faster training phase, I create a script for converting data in csv file to h5 format. You could cd into the **src** folder, then run the following command for this conversion task:

- **python data_preprocessing.py**

Then, cd into the parent folder, and begin the training process by:

- **python train.py**


