# smile-classification

## Introduction

This project is a Convolutional Neural Network (CNN) based image classification model that does a binary classification of images into two classes: smiling and non-smiling. The used dataset is [CelebA Dataset](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html).


## Download the dataset

According to a [bug](https://github.com/pytorch/vision/issues/8204#issuecomment-1935737815) in torchvision v0.17.0, manual installation for the CelebA dataset is required. 
Availabe link at drive: [CelebA Dataset](https://drive.google.com/file/d/1J7pY2j0-SYxpqNY2AEUhCR3q1npON1-v/view?usp=sharing)

**note**: unzip the dataset and put it in the root directory of the project.


## Results

Loss and accuracy plots are shown below:

![Loss-Accuracy](assets/loss_accuracy.png 'loss-accuracy chart')

Testing result:

![Testing](assets/results.png 'testing result')
