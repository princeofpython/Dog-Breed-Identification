# Dog Breed Identification
**Final project for my Academic Course EE5180 : Introduction to Machine Learning**

## Problem Statement
Image Classification is becoming increasingly important in the digital world and has applications that go far beyond just facial recognition for humans. Image Classification, especially fine-grained image recognition, has important applications in industries ranging from social media to marketing to national security. We wanted to take this important method and apply it do something we all love. . . dogs! Have you ever seen a dog walking down the street and wondered “what type of dog is that”? If so, you are not alone. Dog breed identification models can be used not only to satisfy our own curiosity, but also help predict future behavior, match dogs to owners, help return lost dogs to their homes, and aid in targeted internet advertising. In order to accomplish our goal of building a dog breed classification model, we use the Stanford Dog Dataset and a variety of transfer learning methods, as well as built from scratch models in 120 different dog breeds. 

**Competition Link in Kaggle :** [Dog Breed Identification](https://www.kaggle.com/c/dog-breed-identification/overview)
## Existing Methods

- Merge dogs dataset with another bigger dataset with images (i.e ImageNet) and train a CNN on these merged examples. **(Very hard because we need to train many parameters and lot of tuning is required).**
- Take an already pre-trained deep neural network like Inception V3, MobileNet, VGG16, Resnet50 on a larger dataset, cut into it, and attach an additional “classification head” i.e. several additional fully connected layers with the Softmax layer on top of them. **(More Basic Approach)**


## Initial Plan
We decided to include transfer learning methods into our first approach because this is a very famous dataset, so there are many very good pre-trained models out there. For time and computing efficiency, we chose to do transfer learning methods, with a particular focus of transfer learning based on Inception V3, MobileNet, VGG16. Later on, based on the outcome we might try to make a built-from-scratch model using Google Colab.  
**Repository Link in Github** : [Dog-Breed-Identification](https://github.com/princeofpython/Dog-Breed-Identification)
### References
1.  [Dog Breed Classification using Deep Learning: a hands-on approach](https://towardsdatascience.com/dog-breed-classification-hands-on-approach-b5e4f88c333e)
2.  [Dog Breed - Pretrained keras models](https://www.kaggle.com/gaborfodor/dog-breed-pretrained-keras-models-lb-0-3)
