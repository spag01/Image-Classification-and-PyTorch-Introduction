# Image-Classification-and-PyTorch-Introduction

## Overview
This project aims to provide practical experience in designing and training advanced deep convolutional neural networks (CNNs) using PyTorch. The project is structured in two main parts: enhancing a baseline CNN architecture for classifying images into 100 categories using the CIFAR100 dataset, and applying transfer learning techniques using a pre-trained ResNet model on the Caltech-UCSD Birds dataset. Performance evaluation will be conducted through a Kaggle competition, providing an automatic ranking and evaluation system.

## Objectives:
### 1.Enhance CNN Architecture:
      - Improve upon a provided baseline architecture (BaseNet) for image classification.
      - Experiment with various architectural adjustments, data preprocessing, and augmentation techniques to enhance model performance.
  
### 2.Apply Transfer Learning:
      - Utilize a pre-trained ResNet model and fine-tune it for a different dataset (Caltech-UCSD Birds).
      - Explore the effects of freezing certain layers versus fine-tuning the entire network.
  
### 3.Performance Evaluation:
      - Evaluate model performance by participating in a Kaggle competition.
      - Analyze the impact of different architectural choices and hyperparameters on model accuracy.
      
## Deliverables:
### 1.Code and Notebook:
    - A Jupyter notebook (lab2.ipynb) containing the implemented models, experiments, and visualizations.
    - The notebook should be well-documented and structured, detailing the process and findings.
    
### 2.Kaggle Submission:
      - CSV file with predicted test labels, uploaded to the specified Kaggle competition for performance evaluation.

### 3.Report:
      - A comprehensive report detailing the methodology, experiments conducted, and results obtained.
      - The report should include visualizations of training loss and validation accuracy, tables illustrating the architecture of the final networks, and discussions on the ablation studies conducted.

## Key Components:

### 1.Improving the BaseNet Architecture (Part 1):
      - Experiment with architectural changes, data normalization, augmentation, deeper network structures, and normalization layers.
      - Evaluate the impact of these changes through ablation studies and Kaggle submissions.
      
### 2.Transfer Learning with ResNet (Part 2):
      - Fine-tune a pre-trained ResNet model for the Caltech-UCSD Birds dataset.
      - Compare the performance between using ResNet as a fixed feature extractor and fine-tuning the entire network.
      - Experiment with different hyperparameters, learning rates, and additional techniques like dropout and regularization.

#### This project offers a comprehensive experience in advanced deep learning techniques for image classification, emphasizing practical application, experimentation, and performance evaluation.
