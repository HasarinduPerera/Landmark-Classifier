# Landmark Classification & Tagging for Social Media 2.0 Project

## Project Overview

This project is a part of the Machine Learning Fundamentals Udacity Nanodegree and focuses on building a landmark classifier. The objective is to predict image locations based on the landmarks depicted in the images, a critical component for photo sharing and storage services. The project covers data preprocessing, CNN model design and training, model comparison, and app deployment.

## CNN from Scratch (cnn_from_scratch.ipynb)

### Data Preprocessing

- Transformed data into tensors using resizing, cropping, tensor conversion, and normalization.
- Designed data augmentation for the train set to improve model performance.

### Model Definition

- Created a CNN architecture for landmark classification.
- Implemented a dynamic output layer with a variable number of outputs and adjustable dropout.

### Model Training and Evaluation

- Successfully trained and evaluated the model, achieving a test accuracy of at least 50%.
- Exported the model using TorchScript for potential deployment.

## Transfer Learning (transfer_learning.ipynb)

### Transfer Learning

- Leveraged a pre-trained model with frozen parameters for landmark classification.
- Set reasonable hyperparameters for the task to ensure efficient training.

### Model Training and Evaluation

- Trained and evaluated the transfer learning model, achieving a test accuracy of at least 60%.
- Exported the transfer learning model using TorchScript.

## App Development (app.ipynb)

### App Development

- Created a user-friendly app to display images and make predictions using the exported model.

This project demonstrates proficiency in data preprocessing, CNN model design, training, model deployment, and landmark classification, serving as a valuable skillset in machine learning and computer vision.