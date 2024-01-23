# Facial_data_ASD Machine Learning Models

## Overview

This repository houses machine learning models developed for the classification of facial images of children, focusing on distinguishing between those with Autism Spectrum Disorder (ASD) and those without. The implemented models include Random Forest, Gradient Boosting, and Support Vector Machine algorithms.

## Problem Statement

The primary objective is to address the classification challenge posed by facial images, with the intention of aiding in the identification of children with ASD. Leveraging machine learning techniques, we aim to discern patterns and features within facial data that contribute to the accurate categorization of individuals.

## Dataset - Facial_data_ASD

The models have been trained and evaluated using the "Facial_data_ASD" dataset (https://www.kaggle.com/datasets/shafi420/facial)

## Models

The following machine learning models have been implemented:

- **Random Forest:** A robust ensemble learning method that combines multiple decision trees to enhance classification accuracy.

- **Gradient Boosting:** A sequential training of weak learners, with each subsequent learner correcting the errors of its predecessor, leading to a powerful ensemble model.

- **Support Vector Machine (SVM):** A discriminative model that aims to find the optimal hyperplane to separate data points into distinct classes.Prior to feeding the facial data into the machine learning models, several preprocessing steps have been applied to enhance the quality and robustness of the input:

## Preprocessing

Prior to feeding the facial data into the machine learning models, several preprocessing steps have been applied to enhance the quality and robustness of the input:

- **Image Cropping:** An algorithm has been employed to crop the facial images, focusing on the region of interest and eliminating unnecessary background noise.

- **Image Flipping:** Images have been horizontally flipped to augment the dataset, providing additional variations and aiding in the model's generalization.

- **Random Rotation:** To introduce variability, each image has been randomly rotated within the range of -45 to 45 degrees. This augmentation helps the model better handle different orientations of facial features.

- **Salt and Pepper Noise Addition:** A noise generation process, specifically salt and pepper noise, has been incorporated to simulate real-world variations in image quality, enhancing the model's resilience to noisy input.
