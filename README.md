# Cat vs. Dog Image Classification using VGG19

This repository contains code for a simple image classification task to classify images of cats and dogs using the VGG19 model with fine-tuning. The dataset used in this project consists of cat and dog images downloaded from Kaggle.

## Requirements:

Python 3.x
TensorFlow
Matplotlib
Kaggle API

## Dataset:

The dataset used in this project can be found on Kaggle. The dataset contains a collection of cat and dog images for classification. The data has been split into training, validation, and test sets.

To access the dataset, you need to have a Kaggle API key, which should be stored as kaggle.json in the root directory.

## Model Architecture

The model used in this project is based on the VGG19 architecture, pre-trained on the ImageNet dataset. The fully connected layers are fine-tuned for the cat vs. dog classification task.

## Training

The training data is augmented using ImageDataGenerator from TensorFlow to improve model generalization. The images are resized to (256, 256) and pixel values are rescaled to [0, 1]. The data is split into 70% training, 20% validation, and 10% test sets.

## Evaluation

The model is trained using the training data and validated using the validation data. The training history is stored to analyze model performance. The model is then evaluated on the test data to measure its performance on unseen data.

## Results

The model's performance on the test data is evaluated in terms of test loss and accuracy.

## License

This project is licensed under the MIT License.


