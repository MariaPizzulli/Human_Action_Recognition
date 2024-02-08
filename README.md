# Human_Action_Recognition
## Overview
Human Action Recognition (HAR) aims to understand human behavior and assign a label to each action. It has a wide range of applications, and therefore has been attracting increasing attention in the field of computer vision.
The request on Kaggle is to to build an Image Classification Model using CNN that classifies to which class of activity a human is performing.

Additional information:

• The dataset features 15 different classes of Human Activities.

• The dataset contains about 12k+ labelled images including the validation images.

• Each image has only one human activity category and are saved in separate folders of the labelled classes


## Input file
• Train - contains all the images that are to be used for training your model. In this folder you will find 15 folders namely - 'calling', ’clapping’, ’cycling’, ’dancing’, ‘drinking’, ‘eating’, ‘fighting’, ‘hugging’, ‘laughing’, ‘listening_to_music’, ‘running’, ‘sitting’, ‘sleeping’, texting’, ‘using_laptop’ which contain the images of the respective human activities.

• Test - contains 5400 images of Human Activities. For these images you are required to make predictions as the respective class names -'calling', ’clapping’, ’cycling’, ’dancing’, ‘drinking’, ‘eating’, ‘fighting’, ‘hugging’, ‘laughing’, ‘listening_to_music’, ‘running’, ‘sitting’, ‘sleeping’, texting’, ‘using_laptop’.

• Testing_set.csv - this is the order of the predictions for each image that is to be submitted on the platform.

• Training_set.csv - this file contains the mapping between image name and label

## Useful links

• How to import Data from Kaggle: https://www.geeksforgeeks.org/how-to-import-kaggle-datasets-directly-into-google-colab/

• Keras CNN model list: https://keras.io/api/applications/
