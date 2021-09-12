# Eye-For-Blind
##### Image to caption and to speech

## Problem statement:

This problem statement is an application of both DL and NLP. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. 
	
The features of an image will be extracted by a CNN-based encoder and this will be decoded by an RNN model. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library. 

The project is an extended application of Show, Attend and Tell: Neural Image Caption Generation with Visual Attention paper.

## Attention-based encoder-decoder architecture:
![](https://github.com/anuprabhaprabhu/Eye-For-Blind/blob/main/Architecture.jpg)




## Dataset:
The dataset is taken from the Kaggle website and it consists of sentence-based image descriptions having a list of 8091 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.
The link is: https://www.kaggle.com/adityajn105/flickr8k 

## Steps followed:
1. Data Understanding: load the data and understand the representation.
2. Data Preprocessing: preprocess both images and captions to the desired format.
3. Train-Test Split: Combine both images and captions to create the train and test dataset.
4. Model Building: create image captioning model by building Encoder, Attention and Decoder model.
5. Model Evaluation: Evaluate the models using greedy search and BLEU score.
6. Model testing

