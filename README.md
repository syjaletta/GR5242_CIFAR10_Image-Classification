# GR5242_CIFAR10_Image-Classification
## Introduction

We are aiming at implement the best deep learning classifier that we can create using CIFAR10 dataset. We train the image classification model using Keras library to build CNN model with augmentation added.

## Coding & Function

- **get_data**: Get data from the dataset and split the trainning data into tranning and validataion data with ratio of 9:1 
- **CNN_model**: CNN model construction processes
- **CNN_model.fit**: Model training processes
- **plot_acc_loss**: Plot accuarcy and loss for trained model
- **evaluate_model**: Show accuracy and loss for both training and testing data
- **visualization**: Display 10 predictions
- **aug_gen**: Add data augmentation onto trained model and train again

## Running

Simply run all codes, results will be printed out

## Model Accuarcy

  | Model | Epochs   | Accuracy |
  | :--- | :------: | :-------: |
  | `CNN_model` | 100 | **83%** |
  | `CNN_model`, `Data Augmentation` | 100 | **88%** |
    
    
