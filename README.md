# Pup Identify
This repository contains an end-to-end dog breed classification system capable of identifying different breeds of dogs. It employs a deep learning approach, utilizing a convolutional neural network (CNN) architecture to achieve high accuracy. The goal is to create a classifier capable of determining a dog's breed from a photo. 

Huggingface Spaces Link - https://huggingface.co/spaces/yatin-ys/pup-identify

## Dataset
The dataset used in this project is 'Stanford Dogs Dataset'. This dataset contains images of 120 breeds of dogs from around the world. This dataset has been built using images and annotation from ImageNet for the task of fine-grained image categorization.

Link - https://www.kaggle.com/competitions/dog-breed-identification/data

## Model 
We use a MobileNetV2 model from TensorFlow Hub. TF Hub model uses the TF-Slim implementation of mobilenet_v2 with a depth multiplier of 1.3 and an input size of 224x224 pixels.

Link - https://tfhub.dev/google/imagenet/mobilenet_v2_130_224/classification/5

