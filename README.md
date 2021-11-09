# Image Captioning Project

A deep Learning models that takes as input an image and describes its contents. 

Concepts used : Convolutional Neural Networks, Recurrent Neural Networks, Transfer Learning, Word embeddings, Image and Text Processing, Multi Layered Perceptrons, Backpropagation, Gradient Descent, and many more... 

Language used : Python

Libraries used : Tensorflow, Keras, Numpy, Pandas, re, etc.

For transfer Learning, used glove embeddings and resnet50 model.

## REAL WORLD APPLICATIONS OF IMAGE CAPTIONING

1. In self driving cars, it can be used to properly caption scene around a car and give a boost to the self driving system.

2. It can serve as an aid to the blind, wherein we can first convert the scene into text abd then text into voice. This can help guide them on roads and crowded places.

3. In CCTV cameras, alongwith viewing the world, if we can also generate relevant captions, then we can raise alarms if some malicious activity takes place. Malicious cativity could be detected based on generated captions.

4. It can help make Google Image Search as good as Google Search. Every image could be first converted to a caption and then search could be performed for other similar images.

## DATA DESCRIPTION (Dataset used - Flickr8K)
A total of around 8000  images are there in Flickr8k dataset, divided into training and testing sets. 
Each image is given 5 different captions by 5 different humans, to account for the fact that an image can be described multiple ways. 

## METHODOLOGY ADOPTED 

## STEP 1 : 
Words will be generated one at a time in order to generate complete sentences. To generate each word, we provide 2 types of inputs :
1. Image
2. Part of the sentence that has already been predicted so that the model can use the context and predict the next word.

## STEP 2 : PREPROCESSING TEXT DATA
1. We add 2 special tokens to each caption that represents start of sentence and end of sentence.
2. Then we make multiple data samples for each caption and image pair.

## STEP 3 : EXTRACTING TEXT FEATURES 
1. We use word embeddings to represent our words. 

## Results obtained on test images :

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture1.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture10.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture11.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture12.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture13.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture14.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture15.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture16.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture17.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture18.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture2.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture3.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture4.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture5.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture6.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture7.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture8.png)

![Alt text](https://github.com/ChetnaAgarwal/Image-Captioning-Project/blob/master/image%20captioning%20results/picture9.png)
