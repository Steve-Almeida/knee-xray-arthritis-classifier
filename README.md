# Knee X-Ray Arthritis Classifier
## Overview
A deep learning model that classifies knee X-rays by arthritis severity grade (0-4) using fastai and DenseNet169.
## Dataset
Used the Knee Osteoarthritis Dataset with Severity Grading from Kaggle, containing knee X-ray images graded 0-4 by severity.
## Approach

Used all 5 grades (0-4) for severity classification
Fine-tuned a pretrained DenseNet169 model using fastai
Applied data augmentation to reduce overfitting
Trained for 4 epochs

## Results

Validation accuracy: ~64.4%
Test accuracy on unseen data: ~64.19%
Comparable to published research paper results (66-71%)

## Kaggle Notebook
View the full notebook here
## Built With

fastai
PyTorch
DenseNet169
Kaggle GPU
