# Deep Learning Project


# Fruit and Vegetable Classification 

## Problem Statement

The goal of this project is to classify images of fruits and vegetables into 131 different categories using deep learning techniques. This problem is crucial for applications like automated sorting systems in agriculture and food industries.

## Explanation

In this project, several deep learning models were used to classify images of fruits and vegetables. The main model used was a custom-built **Convolutional Neural Network (CNN)**, which includes several convolutional layers, pooling layers, and fully connected layers for accurate image classification.

### Additional Models
Apart from the custom CNN, the following pre-trained models were also tested for improved performance:

- **ResNet50**: A deep residual network used for transfer learning.
- **VGG16**: A CNN architecture with 16 layers.
- **InceptionV3**: A CNN known for its efficiency in handling large-scale datasets.

These models were fine-tuned on the dataset to further enhance accuracy.

### Training Process

The models were trained on the **Fruits-360** dataset, which contains over 90,000 images of 131 different categories of fruits and vegetables. Data preprocessing and augmentation techniques were used to enhance the training set and reduce overfitting. The training process involved the following steps:
- Loading and preprocessing the dataset.
- Data augmentation to increase diversity and prevent overfitting.
- Training the models using multiple epochs.
- Evaluating the model performance on a validation set.

## Dataset Link

The dataset used in this project is the **Fruits-360** dataset, available on Kaggle:

- [Fruits-360 Dataset](https://www.kaggle.com/datasets/visionaryai/fruit360)



