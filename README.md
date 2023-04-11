

# Compiling and evaluating a binary classification model using a neural network.

This model should use the dataset’s features to predict whether an Alphabet Soup–funded startup will be successful based on the features in the dataset.


## Model 1: 

* Featuers removed: "EIN, Name"
* Hidden Nodes = 2
* Epoch: 100

**Original Model Results**

268/268 - 0s - loss: 0.7962 - accuracy: 0.6971 - 292ms/epoch - 1ms/step
Loss: 0.7962440848350525, Accuracy: 0.6971428394317627

## Model 2 A1:

* Featuers removed: "EIN, Name"
* Hidden Nodes = 3
* Epoch: 50

**Alternative Model 2 Results:**

268/268 - 0s - loss: 0.8492 - accuracy: 0.5251 - 291ms/epoch - 1ms/step
Loss: 0.849195122718811, Accuracy: 0.5251311659812927


## Model 2 A2

* Featuers removed: 'EIN','NAME', 'APPLICATION_TYPE','INCOME_AMT'
* Hidden Nodes = 4
* Epoch: 35
* First Layer Activation Function: Leaky Relu

**Alternative Model 2 Results:**

268/268 - 0s - loss: 0.6975 - accuracy: 0.5190 - 407ms/epoch - 2ms/step
Loss: 0.6975339651107788, Accuracy: 0.5189504623413086

-------------------------------

# Summary

Neither Alternative models were able to improve the accuracy score from model 1. Adding more hidden layers did not better the model as it progressivly got worse with model A1 to model A2 which contained 4 hidden layers. If we had more time i would have liked to try a diffrent activation function for model 1 with reduced features from mdoel A2. 

