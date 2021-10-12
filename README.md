# CS867-Computer-Vision-Assignment-01

Image features Detection and Matching Image Classification

## Task-1 : Human Classification / Detection

Human Detection is a branch of Object Detection. Object Detection is the task of identifying the presence of predefined types of objects in an image. This task involves both identification of the presence of the objects and identification of the rectangular boundary surrounding each object (i.e. Object Localisation). An object detection system which can detect the class “Human” can work as a Human Detection System.
Human detection is an essential and significant task in any intelligent video surveillance system, as it provides the fundamental information for semantic understanding of the video footages. It has an obvious extension to automotive applications due to the potential for improving safety systems. Many car manufacturers (e.g. Volvo, Ford, GM, Nissan) offer this as an ADAS option in 2017. Some of the applications be given as;
o Self-driving cars: Identifying pedestrians on a road scene
o Security: Restrict access for certain people to certain places o Retail: Analysing visitors behaviour within a supermarket
o Fashion: Identify specific brands and persons who wear them

## Task-2 : Image Classification Using Bag of Visual Words
The concept of “Bag of Visual Words” is taken from the related “Bag of Word” concept of Natural Language Processing.
In the bag of word model, the text is represented with the frequency of its word without taking into account the order of the words (hence the name ‘bag’).

The main idea behind the counting of the word is:
Documents that share a large number of the same keywords, regardless of the order the
keywords appear in, are considered to be relevant to each other.

### Bag of Visual Words
In Computer Vision, the same concept is used in the bag of visual words. Here instead of taking the word from the text, image patches and their feature vectors are extracted from the image into a bag. Features vector is nothing but a unique pattern that we can find in an image.
To put it simply, Bag of Visual Word is nothing but representing an image as a collection of unordered image patches.

### What is the Feature?
Basically, the feature of the image consists of keypoints and descriptors. Keypoints are the unique points in an image, and even if the image is rotated, shrink, or expand, its keypoints will always be the same. And descriptor is nothing but the description of the keypoint. The main task of a keypoint descriptor is to describe an interesting patch(keypoint)in an image.

### Image classification with Bag of Visual Words
This Image classification with Bag of Visual Words technique has three steps:
1. Feature Extraction – Determination of Image features of a given label.
2. Codebook Construction – Construction of visual vocabulary by clustering, followed by frequency analysis.
3. Classification – Classification of images based on vocabulary generated using SVM.
 
