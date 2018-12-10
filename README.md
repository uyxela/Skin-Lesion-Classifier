# Skin-Lesion-Classifier
A classifier written in native Keras that can be used to identify seven different types of skin lesions.

This model uses the MobileNet architecture and was retrained on the HAM10000 dataset which contains 100015 documented images of skin lesions.
https://arxiv.org/abs/1803.10417

The goal of the project was to deploy the model as a web app by converting a Keras model to a Tensorflow.js model. The live version can be found at: https://alexyu.me/projects/skinlesionclassifier.html

The model obtains an accuracy of approximately 80%, with a top-3 accuracy of approximately 94%. 
