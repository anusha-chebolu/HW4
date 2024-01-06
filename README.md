# Image Classification

Use transfer learning for large image classification, going through these steps:

1. Take at least 100 images per class with at least 3 classes using your phone/camera (e.g. take photos of different types of trees, flowers or animals). Display 5 examples from each class. [10 points]
2. Split the images into a training set, a validation set, and a test set. [5 points]
3. Build the input pipeline, including the appropriate preprocessing operations, and add data augmentation. [10 points]
Fine-tune a pretrained model of your choice on this dataset (the one you created in part 3). Report classification accuracy and give a few examples of correct/incorrect classification (show a few images that were correctly/incorrectly classified). [10 points]
5. Train from scratch (without pretraining) a deep neural network that contains convolutional layers on this dataset (the one you created in part 3). Report classification accuracy and give a few examples of correct/incorrect classification (show a few images that were correctly/incorrectly classified). Note: The objective of this question is to illustrate that training deep networks from scratch requires a lot of data so it is ok if your classification accuracy is low. [15 points]
