
# Multiclass Image Scene Classification   

Classification of images using Convolutional Neural Networks (CNN) has achieved impressive accuracy in most image recognition tasks. 
I built five different powerful CNNs that classify images with high accuracy and conducted failure analysis for each of these models and created a new model that improved upon those aspects.
Although humans have an excellent sense of recognizing a place’s scene setting from its background, developing a vision system capable of recognizing different kinds of natural scene settings is not easy.

Below image shows the different kind of images within the dataset along with their classes.

![Scenes]()

## Challenges

Firstly, scenes are ambiguous in nature. For example, it is natural for a street image to contain buildings.
Another issue is the variation in the representation of a single scene. 
For example, two scenes to be classified as mountains may not be of similar shapes, sizes or even colour. 

## Best performing model

After trying various CNN models with a softmax function in the end, the 50 layer deep resnet model 
along with image augmentation performed the best. Below is the confusion matrix for the best performing model.

![Confusion Matrix]()