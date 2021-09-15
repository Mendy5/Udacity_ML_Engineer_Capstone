# Udacity_ML_Engineer_Capstone
This repository contains all related files of Udacity Machine Learning Engineer Capstone Project: Dog Breed App

## Installation
Install all the required libraries by using the [environment.yml](https://github.com/Mendy5/Udacity_ML_Engineer_Capstone/blob/main/environment.yml)

## Data Source
Users would like take images of the dog and ask for the breed. Therefore, we need to feed images as input for the models. The data sources are showing below:
1.	dog dataset: [Link](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
2.	human dataset: [Link](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)

There are 13233 colored human images with size 250*250. in the human dataset. While there are 8351 dog images with various image sizes. All the dog images are colored with the heights from 113 to 4003 and the weights from 105 to 4278. To make a better training and prediction, it would be better to transform the dog images with same size before feeding into the model.

The datasets including 3 parts: the training, validation, and testing datasets. All the datasets will be used for training, valid and testing the model to get the best model with low losses.

The human images will use for the model identifies the object in the image is a human or a dog. While the dogs in the images have different breeds, backgrounds, postures, and orientations. These dogs images will feed into another model predict the dog’s breed

## Project Motivation
People see a dog and wonder it's breed. Also, some owners are wondering their dogs' breed. Without understand the breed of their dogs, their dog is at risk for a number of problems that come from breeding. Finding the answer by google the descriptions of the dog is difficult and time consuming. However, the process will be much easier if they can submit an image of the dog and get an answer via a web or mobile app.

In this project, I will create a web application that can distinguish an image of dog from human images and classify the breed of the dog.

## File Description

## Results

# Licensing, Authors, Acknowledgements
