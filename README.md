# Deep Learning for Image Segmentation

This repository contains the implementation of image segmentation using the DeepLabV3 model with PyTorch, tailored for a dataset of road scenes. It includes scripts for dataset preparation, model training, and evaluation, focusing on segmentation tasks for various classes.

## Project Structure

- `CustomDataset`: Defines the dataset class handling image and mask loading, along with transformations.
- `dataset_preparation`: Prepares and splits the dataset into training, validation, and testing subsets.
- `model_training`: Script to train the DeepLabV3 model on the processed dataset.
- `evaluate_model`: Evaluates the model using precision, recall, F1-score, and IoU metrics.

## Features

1. **Dataset Customization**
   - Initialization of a custom dataset with defined transformations.
   - Selection and storage of a subset of images and masks for processing.

2. **Model Training**
   - Implementation of the DeepLabV3 model training for image segmentation.
   - Use of various performance metrics (accuracy, precision, recall, F1-score) to evaluate the model.

3. **Visualization**
   - Visualization of the distribution of the dataset.
   - Display of images alongside their ground truth and predicted masks.

4. **Performance Metrics**
   - Detailed computation and visualization of confusion matrices and IoUs for each class.
   - Identification of classes where the model performs well or needs improvement based on predefined metrics.

## Usage

Ensure you have Python and PyTorch installed.:

