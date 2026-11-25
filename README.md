# Vegetable Image Classification using CNN

A Convolutional Neural Network (CNN) built from scratch with Keras to classify vegetable images into 15 classes.

## Dataset

[Kaggle Vegetable Image Dataset](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset)

- 15 classes: Bean, Bitter Gourd, Bottle Gourd, Brinjal, Broccoli, Cabbage, Capsicum, Carrot, Cauliflower, Cucumber, Papaya, Potato, Pumpkin, Radish, Tomato
- Split into `train`, `validation` and `test` folders
- The dataset is balanced (same number of images in every class)

## Project Steps

1. Load the dataset and define the paths
2. Count the images in each class
3. Build a summary DataFrame and plot the class distribution
4. Prepare image generators with augmentation (`ImageDataGenerator`)
5. Load images with `flow_from_directory` (224x224, batch size 32)
6. Build the CNN model
7. Train with EarlyStopping
8. Evaluate the model and
