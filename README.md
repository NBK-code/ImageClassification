# ImageClassification
In this project we build two different image classification models for the SVHN Dataset - a MLP (MultiLayer Perceptron) model and a CNN (Convolutional Neural Network) model. The MLP model is made out of just dense layers and hence does not take into account of the 2D structure of the input data. On the other hand, the CNN model consisting of convolutional layers makes complete use of the 2d structure of the input images. So it is expected that the CNN model is much more efficient in classifying images. But how do we quantify this? In this project, we train both the models on the same SVHN dataset and ask how many model parameters are reqiored to achieve the same amount of accuracy after training for the same number of epochs. Of course, it is not guranteed that both the models will have similar accuracy after a certain number epochs. But here, we were lucky enough to achieve just that. Here is what we found:

___________________________________
### MLP model 

## Training epochs: 13
## Test set accuracy: 0.69

## Parameters: 697,930

___________________________________
## CNN model

## Training epochs: 13
## Test set accuracy: 0.69

## Parameters: 1,918

___________________________________

For similar performance, the CNN model uses lesser parameters than the MLP model.
