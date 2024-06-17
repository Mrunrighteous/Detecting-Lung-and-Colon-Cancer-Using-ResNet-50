# Lung and Colon Caner Detection Using ResNet-50 on Histopathology Images

This repository contains a deep learning project for detecting lung and colon cancer from histopathology images using the ResNet-50 architecture. The goal is to classify images as either normal or cancerous to aid in the early diagnosis of lung and colon cancer.

## Table of Contents

- Introduction
- Dataset
- Installation
- Model Architecture
- Training
- Evaluation
- Contribution

## Introduction

Histopathology is the study of the microscopic structure of tissues, and it is a crucial method for diagnosing various types of cancers. This project leverages deep learning, specifically a ResNet-50 model; To automate the detection of lung and colon cancer from histopathology imgages. By accurately classifying these images, the model can assist pathoogists in diagnosing cancer more efficiently and accurately.

## Dataset

The dataset used in this project consists of histopathology images from lung and colon tissues. The dataset is divided into training, validation and test set.

dataset link - https://academictorrents.com/details/7a638ed187a6180fd6e464b3666a6ea0499af4af

## Installation 
To run this project, you need to have Python and several Python libraries installed. You can install the required libraries using the following command:

> pip install -r requirements.txt


## Model Architecture

The model is based on the ResNet-50 architecture, a deep residual network that is widely used for image classification tasks. I fine-tuned the ResNet-50 model on the histopathology dataset.

## Training

The model is trained using the following hyperparameters:

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Epochs: 60

## Evaluation

The model's performance is evaluated using accuracy, precision, recall, and F1-Score.

## Contribution

Contribution are welcome! Please open an issue or submit a pull request if you have any suggestion or improvements.

  
