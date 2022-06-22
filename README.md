# Brain MRI Tumor Classification
# ============================
## Table of Contents
- [Introduction](#introduction)
- [dataset](#dataset)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Contributing](#contributing)

## Introduction
This project is a simple implementation of a convolutional neural network for
detect brain tumors.

## Dataset
The dataset used for this project is the [Brain_MRI_images](https://www.cbica.upenn.edu/sbia/Spyridon.Bakas/MICCAI_BraTS/MICCAI_BraTS_2017_Data_Processing.html) dataset.
The dataset contains 253 images of brain tumors. The images are cropped to a
size of 256x256 pixels. The images are normalized to have a mean of 0 and a
standard deviation of 1. The dataset is split into training, validation and testing
sets.
Data augmentation is used to increase the number of training samples.

## Usage
To run the training, validation and testing of the model, open the notebook and run every cell.



