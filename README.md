# end-to-end-dog-vision

his notebook builds an end-to-end multi class image classifier using Tensorflow 2.0 and Tensorflow Hub.

1. Problem
Identifying the breed of a Dog given an image of a dog.

When i'm sitting at a cafe and I take a photo of it, I want ot know the breed of the dog it is.

2. Data
The data we're using is from Kaggle's dog breed identification.

https://www.kaggle.com/c/dog-breed-identification/data

3. Evaluation
The evaluation is a file with prediction probabilites with each test image.

www.kaggle.com/competitions/dog-breed-identification/overview/evaluation

4. Features
Some information about the data:

We are dealing with images(Unstructured data) so it's probably best we use deep learning/transfer learning.

There are 120 breeds of dogs (this means there are 120 different classes).

There are around 10,000+ images in the training set (these images have labels)

There are around 10,000+ images in the test set (these images have no labels, because we'll want to predict them)
