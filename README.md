# Cat and Dog Object Classification using VGG16

This project aims to classify images of cats and dogs using the VGG16 convolutional neural network architecture. VGG16 is a popular deep learning model known for its effectiveness in image classification tasks.

## Overview

The VGG16 model is pre-trained on the ImageNet dataset, which contains a vast number of images across 1,000 categories. In this project, we will fine-tune the VGG16 model on our dataset of cat and dog images to leverage its learned features for our specific task.

## Dataset

The dataset consists of images of cats and dogs obtained from kaggle. 

## Requirements

- Python 3.x
- TensorFlow 
- NumPy
- Matplotlib (for visualization)
- Flask
- Jupyter Notebook (optional for running and viewing notebooks)
- Vs Code


## How to Run
#### 1.
    conda create -n catdog python=3.7 -y 
#### 2.
    conda activate catdog

## Install the required dependencies:
#### 3.
    pip install -r requirements.txt
#### 4.
    python app.py
#### 5.
    open in browser: http://localhost:8080/
