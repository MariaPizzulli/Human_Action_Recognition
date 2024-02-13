# Human_Action_Recognition
## Overview
Human Action Recognition (HAR) aims to understand human action and assign a label to each one of them. It has a wide range of applications, and therefore is attracting increasing attention in the field of computer vision.
This project builds an image classification model using CNN.

Additional information:

• The dataset contains 15 different classes of Human Activities.

• The dataset contains more than 12k labelled images for training and validation.

• The dataset contains 5400 images for testing.

• Each image has only one human activity class.


## Running the Project on Colab
Before running the code, it is advisable to change the Runtime typology from CPU to T4 GPU in order to speed up training phase of CNN.

The project upload a folder containing the four files into the Colab environment at the beginning of the notebook, it is called 'human-action-recognition-har-dataset'. These files are essential for train and test the model.

It is possible to save the model on Google Drive during the execution.

## Requirements

• _Python Libraries_:

numpy; 
pandas; 
opendatasets;
seaborn; 
keras; 
tensorflow; 
matplotlib;
sklearn;

• _Credentials_:

Kaggle username and secret key for downloading dataset;
Google Drive account;


## Useful links

• How to import Data from Kaggle: https://www.geeksforgeeks.org/how-to-import-kaggle-datasets-directly-into-google-colab/

• Keras CNN model list: https://keras.io/api/applications/

• How to save model weights, load model Weights: https://machinelearningmastery.com/save-load-keras-deep-learning-models/

• Adam optimizer parameter: https://keras.io/api/optimizers/adam/  
