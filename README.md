# RegNetY-8GF Image Classification
## Overview
This project is all about training a RegNetY-8GF model—a sleek and efficient CNN—for a 6-class image classification task using PyTorch. The pipeline covers data preprocessing, augmentation, model training, evaluation, and some neat visualizations, making the most of transfer learning to get solid results.

## Features
### Data Prep:
Loads and tweaks the dataset with augmentation to boost generalization.
### Model: 
Fine-tunes a pre-trained RegNetY-8GF from ImageNet, customized for 6 classes.
### Training:
Runs with Cross-Entropy Loss, Adam optimizer, and a cosine annealing scheduler for smart learning rate adjustments.
### Evaluation: 
Delivers accuracy, confusion matrices, and classification reports, plus visuals to see how it’s doing.
### Requirements
1. Python 3.x
2. Libraries: PyTorch, Torchvision, Matplotlib, Seaborn, Scikit-learn
