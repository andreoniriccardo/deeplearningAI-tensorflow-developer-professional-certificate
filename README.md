# Applied Data Science with Python Specialization
This specialization is composed of 4 independent courses.

In this document, for each course, I summarize what I learned, how it enhanced my data scientist skills and what programming assignment consists to.

This GitHub repository contains all the coding material that I wrote and studied for this specialization.

## 01 - [Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning](https://www.coursera.org/learn/introduction-tensorflow/home/welcome)

### How did this course enhance my Data Science skills?
- I am familiar with the TansorFlow programming environment and its API
- I know how to build a convolutional neural network which is able to classify the input images
- I mastered the use of the `ImageDataGenerator` function

### What does this course deal?
- The "hello world" in TensorFlow
- Exploring the **Fashon MNIST** dataset
- Using **callbacks** in neural networks
- **Convolutions** and **pooling** layers
- **`ImageDataGenerator` function**
- **Image compression**

### Coding assignments
- **House Prices**: building a neural network that predicts the price of a house.
- **Implementing Callbacks in TensorFlow**: using the Fashon MNIST dataset, implementing a neural network that uses callbacks to control training
- **Improving the MNIST with convolutions**
- **Handling Complex Images**: use more complex images to build a convolutional neural network

---
# 02 - [Convolutional Neural Networks in TensorFlow](https://www.coursera.org/learn/convolutional-neural-networks-tensorflow/home/week/1)

### How did this course enhance my Data Science skills?
- I can go through all the steps required to build an efficient convolutional neural network for image classification in TensorFlow
- I can perform both binary and multiclass classification, and I built complete CNN using large datasets
- I know different tools to reduce overfitting in my convolutional neural network, such as data augmentation and dropout
- I learned how to build customized CNNs starting from state-of-the-art networks (like InceptionV3 or MobileNet) thanks to transfer learning


### What does this course deal?
- Cat vs. Dogs classifier
	- inspecting the datases
	- **building a classifier in TensorFlow**
	- data preprocessing in TensorFlow
	- model predictions and **model evaluation**
- **Data augmentation** in TensorFlow
- **Transfer learning** in TensorFlow
	- Coding transfer learning from the **Inception** network
- **Dropout** in TensorFlow
- **Multiclass classification** in TensorFlow

### Coding assignments
- **Cats vs. Dogs**: building a convolutional neural network to classify cats and dogs in images.
- **Data Augmentation**: implementing data augmentation to improve the neural network performance and reduce overfitting.
- **Transfer Learning**: implementing transfer learning to build an effective horse vs. human neural network classifier, starting from the InceptionV3 network.
- **Classification Beyond two classes**: using the [Sign Languade dataset](https://www.kaggle.com/datamunge/sign-language-mnist) from Kaggle build a multiclass classifier neural network.

---
# 03 - [Natural Language Processing in TensorFlow](https://www.coursera.org/learn/natural-language-processing-tensorflow?specialization=tensorflow-in-practice)

## How did this course enhance my Data Science skills?
- I learned how to retrieve and to prepare a dataset for Natural Language Processing applications, which includes tokenizing, padding and embedding, besides removing common stopwords.
- I know how to define and train a model for NLP in TensorFlow.
- I know how to build NLP models for tasks like sentiment analysis, categorization of news articles, and auto-completing sentences.


## What does this course deal?
- Word based **encoding**
- **Text to sequence**
- **Tokenizer**
- **Padding**
- **Detecting sarcasm** in text
- Word **embeddings**
- **Models for NLP**
- Long Short Term Memory algorithm (**LSTM**)
- **Evaluating a NLP model**
- **NLP** with **convolutional networks**
- **Auto-completing** the sentences


## Coding assignments
- **BBC news archive - 01**: retrieving the BBC text archive, tokenizing the dataset and removing common stopwords
- **BBC news archive - 02**: building a neural network to determine the category of the articles contained in the BBC news archive.
- **Exploring Overfitting in NLP**: training a NLP model on large datasets and implementing transfer learning.
- **Predicting the next word**: using Shakespeare sonnets to train a model able to auto-complete sentences.

---