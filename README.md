# Road-Image-Captioning-using-CNN-LSTM

This project aims to generate descriptive captions for road images using a CNN-LSTM architecture. By combining convolutional neural networks (CNNs) for image feature extraction and long short-term memory (LSTM) networks for sequence generation, the model can produce meaningful captions for a variety of road scenes.


## Introduction
The goal of this project is to create a system that can automatically generate captions for images of roads and describe if they are suitable for travel. This involves training a neural network model on a dataset of road images and their corresponding captions. 

## Dataset
A custom dataset was created consisting of 2000 images of roads that appear dangerous, and similary a csv file consisiting of 2000 captions for each image was created.

## Model Architecture
The model uses a CNN (VGG16) network for image feature extraction and an LSTM network for generating captions. The architecture is designed to capture both the spatial features of the images and the sequential nature of the captions.

![image](https://github.com/user-attachments/assets/fac7120a-ac18-4091-b539-eb3e08f96b4b)


## Installation
To get started, clone the repository and install the necessary dependencies.

```bash
git clone https://github.com/your-username/Road-Image-Captioning.git
cd Road-Image-Captioning
pip install -r requirements.txt
