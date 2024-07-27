# Sign Language Captioning

This project focuses on developing a machine learning model to caption sign language videos. The model uses a transformer-based architecture to generate captions from video features extracted from sign language videos.

## Overview

The objective of this project is to create a system that can automatically generate textual descriptions (captions) for sign language videos.


## Installation

To run this project, you need to have the following dependencies installed:

Install the required packages using pip:
pip install -r requirements.txt

## Data Preparation

The dataset consists of sign language videos and their corresponding captions. The preprocessing steps include extracting frames from videos, resizing them, and normalizing pixel values.

## Model Architecture

The model architecture is based on a transformer encoder-decoder structure. The encoder processes video features, and the decoder generates the corresponding captions.

## Training

The model is trained on preprocessed video features and their corresponding captions. The training process includes data augmentation and optimization techniques to improve performance.

## Evaluation

The model’s performance is evaluated using metrics such as Word Error Rate (WER). A confusion matrix and other visualizations help in understanding the model’s performance.