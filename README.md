# Deep Learning Approach to Detect Photovoltaic Arrays in Aerial Images

This repository contains the code and resources for the bachelor thesis on "A Deep Learning Approach to Detect Photovoltaic Arrays in Aerial Images" by [Your Name], submitted for the Bachelor's degree in [Your Degree Program] at [Your University].

## Project Overview

The aim of this project was to develop a deep learning model to detect photovoltaic (PV) arrays in aerial images of Denmark, using a semantic segmentation approach called U-Net. The project involved labeling the PV arrays on satellite data of Denmark with QGIS, and then training the U-Net model to identify PV arrays in aerial images. The Dice Loss was used as the loss function, and the performance of the model was evaluated with the Intersection over Union (IoU) metric.

## Repository Structure

The repository is organized as follows:


### Usage

1. Download the dataset (aerial images and corresponding masks) and place them in the `data` directory.

2. Run the Jupyter notebooks in the `notebooks` directory in the following order:

    - `data_preparation.ipynb`: Prepare the dataset for training and validation.
    - `model_training.ipynb`: Train the U-Net model on the prepared dataset.
    - `model_evaluation.ipynb`: Evaluate the performance of the trained model on the test dataset.

3. Alternatively, you can run the scripts in the `src` directory to train and evaluate the model:

    - `train.py`: Train the U-Net model on the prepared dataset.
    - `predict.py`: Use the trained model to predict PV arrays in new aerial images.

## Acknowledgements

We would like to thank the [Name of Dataset Provider] for providing the dataset used in this project. We also acknowledge the support and guidance of our supervisor [Supervisor Name].
