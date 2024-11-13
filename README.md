# EditREADME
##Project objective
The goal is to build a multiclass classification model using a Convolutional Neural Network (CNN) and Artificial Neural Network (ANN) to recognize spoken commands. This model will classify short audio clips into specific commands from 0 to 1. The model should achieve at least 85% accuracy on the validation or test dataset.
##Dataset information and preprocessing steps
link to dataset: https://www.kaggle.com/datasets/neehakurelli/google-speech-commands/code
This project uses the Google Speech Commands dataset. 
Dataset Structure:
The dataset consists of subfolders where each folder corresponds to a spoken word and each file in the folder is an audio recording of that word. In this project I am using folder of numbers from zero to nine.
Steps:
Loading the Audio Data
Normalization
Feature Extraction (MFCC)
One-Hot Encoding
Splitting the Dataset
##Instructions for running the code 
In my experience, I opened a new kaggle notebook so it's easier the acces the data and downloaded it as a notebook file 
##Dependencies and installation instructions
All built-in in Kaggle. Only imported libraries 
