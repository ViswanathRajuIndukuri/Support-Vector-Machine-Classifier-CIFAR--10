# Support Vector Machine Classifier | CIFAR 10

[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org)
[![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

## Overview
This project involves using a Support Vector Machine (SVM) Classifier to classify images from the CIFAR-10 dataset consisting of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The goal is to classify these images into the correct categories. In this project, I've used the SVM classifier to perform this classification task and compare their performance on color and grayscale versions of the CIFAR-10 dataset and to explore various techniques related to SVM, such as kernel choice and hyperparameter tuning.

## Features
- **Data Loading**: Functions to load CIFAR-10 batches and preprocess the data.
- **Model Training**: Training SVM classifiers using GridSearchCV to find the best hyperparameters.
- **Evaluation**: Evaluating model performance using F1 score and classification reports.
- **Analysis**: Comparing the performance of models trained on color and grayscale CIFAR batches and analyzing the results.

## Results
- **Optimal SVC Parameters Identified**: For both the color and B/W images, the project determines the best SVC parameters, enabling the enhancement of classifier performance.
- **Color vs. B/W CIFAR Dataset Analysis**: A comparative study of F1 scores between the color and B/W CIFAR datasets reveals significant findings. Notably, the models trained on the color dataset consistently demonstrated better F1 scores compared to those trained on the B/W dataset. This outcome underscores the importance of color information in improving the classification accuracy and overall model performance.

This enhanced performance on the color dataset suggests that color features play a crucial role in the effective classification of images.
