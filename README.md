# Custom DataLoader and Image Classification with PyTorch

## Project Overview
This project demonstrates the process of building a custom DataLoader using the PyTorch framework to handle datasets in various forms. It focuses on converting any given dataset into a format that PyTorch can efficiently process for batch-based operations. Additionally, the project implements an image classification problem, utilizing data augmentation techniques from PyTorch and constructing a small VGG-like model from scratch for training.

## Key Features
1. **Custom DataLoader**: 
   - Handles datasets in multiple formats and converts them into a PyTorch `DataLoader` for batch processing.
   - Ensures seamless integration of datasets into PyTorch’s training pipeline.
   
2. **Image Classification**:
   - Implements a classification model to work with image data.
   - Supports flexible input data types and formats.

3. **Image Augmentation**:
   - Applies various augmentation techniques from PyTorch’s `torchvision.transforms` to improve model generalization.
   - Techniques include random rotations, flips, color jitter, and more.

4. **Tiny VGG Model**:
   - Built a tiny version of the VGG model from scratch using PyTorch.
   - Optimized for training smaller datasets and quick iterations.

5. **Training and Evaluation**:
   - Trains the model using the custom DataLoader and evaluates it using standard metrics.
   - Tracks performance by visualizing loss and accuracy curves over the training process


![FashionMNIST Sample](https://github.com/username/repository-name/blob/main/images/sample_image.png)
