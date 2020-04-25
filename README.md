# INFO7390Spring2020Project
Advance Data Science final project for Spring 2020 term

## Project Title: Image Caption Generator

<b>Contributors:</b>
<br><b>Harshad Jaju</b> https://www.linkedin.com/in/harshad-jaju
<br><b>Aman Kapoor</b> https://www.linkedin.com/in/aman-kapoor22

## Objective -
The objective of our project is to learn the concepts of CNN, LSTM and Keras Imagenet pre-trained application models and build our own model of Image caption generator.

In this Python project, we will be implementing the caption generator using CNN (Convolutional Neural Networks) and LSTM (Long short term memory). The image features will be extracted from ResNet50 which is a CNN model trained on the imagenet dataset and then we will feed the features into the LSTM model which will be responsible for generating the image captions.

## Dataset
For the image caption generator, we will be using the Flickr_8K dataset. There are also other big datasets like Flickr_30K and MSCOCO dataset but it can take weeks just to train the network so we will be using the 8K Flickr8k dataset. The advantage of a huge dataset is that we can build better models.

<b>Dataset Size:</b> 1GB
<b>Dataset Link:</b> https://www.kaggle.com/ming666/flicker8k-dataset

<b>Flicker8k_Dataset</b> - Contains all images
<b>Flickr_8k_text</b> - Contains captions of all images and training, test data files
<b>Flickr_8k_text</b> folder contains file Flickr8k.token which is the main file of our dataset that contains image name and their respective captions separated by newline(“\n”).

<b>Pre-requisites</b>
This project requires good knowledge of Deep learning, Python, working on Jupyter notebooks, Keras library, Numpy, and Natural language processing.

## Make sure you have installed all the following necessary libraries:

<b><br>pip install tensorflow
<br>keras
<br>pillow
<br>numpy
<br>tqdm
<br>jupyterlab

## How to run the notebook

It is a standalone notebook, which is not dependednt on any other file. All you have to do is download the folders and place in the directory where you have kept this python notebook and change the paths in the code as per your local structure.

# MIT License

The license details are in the Lincense file, which can be found with other project files above.
