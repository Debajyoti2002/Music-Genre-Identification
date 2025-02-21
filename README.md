# Music-Genre-Identification
The project contains a deep learning model that is capable of detecting the genre of a audio file. 
Overview

This project focuses on classifying music genres using deep learning techniques. It involves training a neural network on audio features extracted from a dataset of music tracks. The model is then tested to predict the genre of new music samples.

Dataset

The model is trained on a dataset containing audio files with labeled genres. The dataset is processed to extract Mel spectrograms, which serve as the primary input features for the deep learning model.

Model Architecture

The deep learning model is based on a Convolutional Neural Network (CNN), which efficiently processes the spectrogram images of audio samples. The key components include:

Convolutional layers for feature extraction

Pooling layers for dimensionality reduction

Fully connected layers for classification

Softmax activation for genre prediction

Training Process

Data Preprocessing: Convert audio files into Mel spectrograms.

Model Training: Train the CNN model using a labeled dataset.

Evaluation: Assess model performance using validation data.

Testing: Apply the trained model to classify new audio samples.

Testing the Model

A separate script is provided to test the model on unseen audio samples. The testing involves loading the trained model and predicting the genre of new music files based on extracted spectrogram features.
