# Knee X-Ray Arthritis Classifier
## Overview
A deep learning model that classifies knee X-rays as either normal or arthritic using fastai and ResNet34.
## Dataset
Used the Knee Osteoarthritis Dataset with Severity Grading from Kaggle, containing knee X-ray images graded 0-4 by severity.
## Approach

Used grades 0 (normal) and 4 (severe arthritis) for binary classification
Fine-tuned a pretrained ResNet34 model using fastai
Trained for 4 epochs

## Results

Validation accuracy: ~98.8%
Test accuracy on unseen data: ~85.5%

## Kaggle Notebook
[View the full notebook here](https://www.kaggle.com/code/stevealmeidadatasets/knee-x-ray-arthritis-classifier)
## Built With

fastai
PyTorch
Kaggle GPU
