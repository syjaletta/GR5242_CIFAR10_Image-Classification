# GR5242_CIFAR10_Image-Classification
## Introduction

We are aiming at implement the best deep learning classifier that we can create using CIFAR10 dataset. We train the image classification model using Keras library to build CNN model with augmentation added.

## Running

Simply run all codes, results will be printed out

## Coding & Function Explanation

- **get_data**: Get data from the dataset and split the trainning data into tranning and validataion data with ratio of 9:1 
- **CNN_model**: CNN model construction processes
- **CNN_model.fit**: Model training processes
- **plot_acc_loss**: Plot accuarcy and loss for trained model
- **evaluate_model**: Show accuracy and loss for both training and testing data
- **visualization**: Display 10 predictions
- **aug_gen**: Add data augmentation onto trained model and train again

## Model Accuarcy

  | Model | Epochs   | Accuracy | Loss |
  | :--- | :------: | :-------: | :---: |
  | `CNN_model` | 100 | **83%** | 1.35 |
  | `CNN_model`, `Data Augmentation` | 100 | **88%** | 0.60 |
    
## References
[What is the VGG neural network?](https://www.quora.com/What-is-the-VGG-neural-network)\
[Keras Convolutional Layers](https://keras.io/layers/convolutional/)\
[如何用Keras从头开始训练一个在CIFAR10上准确率达到89%的模型](https://zhuanlan.zhihu.com/p/29214791)
