# Lumpy-Skin-Disease-Detection

## Introduction
This repository contains a deep learning model trained for binary classification of lumpy skin disease in cows. The model is intended to assist veterinarians in detecting this disease efficiently.

## Model Architecture
The base model used for training is DenseNet169, chosen for its robust performance in image classification tasks. 

## Dataset
The model was trained on a dataset consisting of images of cows affected by lumpy skin disease as well as healthy cows. The dataset was appropriately labeled for binary classification.

## Training
The model was trained using transfer learning techniques, where the pre-trained DenseNet169 model was fine-tuned on our dataset. The training process involved optimizing the model's parameters to minimize a chosen loss function and maximize accuracy.

## Performance
After training, the model achieved an accuracy of 95% on the validation dataset. This high accuracy indicates the potential effectiveness of the model in detecting lumpy skin disease in cows.

## Usage
To use the model for detecting lumpy skin disease, follow these steps:
1. Load the trained model weights.
2. Preprocess input images to match the format expected by the model.
3. Use the model to predict whether the input image depicts a cow with lumpy skin disease or not.

