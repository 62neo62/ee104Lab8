READ ME
YOU MUST FIRST INSTALL THE RIGHT LIBRARIES TO ACCESS DATA SET AND CREATE MODELS
-PIP INSTALL TENSORFLOW
-PIP INSTALL KERAS
-PIP INSTALL MATPLOTLIB

 All models will require the following imports
import tensorflow as tf
from tensorflow.keras import datasets, layers, models
import matplotlib.pyplot as plt
from tensorflow.keras.layers import BatchNormalization
from tensorflow.keras.optimizers import Adam, SGD

To run the code simply load the python notebook files in google colab and run each cell until the model is compiled and trained.
Layer types

Programs Included:
Baseline+Dropout+Data_Augmentation+Batch Norm.pynb
Baseline+Dropout+Data_Augmentation.pynb
Baseline+Dropout.pynb
Custom Model
2-D convultional- Convultes and extracts features from the data input using a "kernel" which inspects the pixel values a matrix and extracts based on design
Max pooling: collects the maximum pixel value within a set group. Has the ability to skip pixel groupings using something called "stride"
Dropout: Serves the purpose of dropping certain neurons/features to reduce redundancy. float value represnt a percentage.
Batch Normalization: allows for the model to train much quick and normalizes the data making it more efficent.
Fully Connected: Connects all the dense neurons each to the 10 outputs
Output: Simply the output which classifies the data into 1 on the 10 types using a softmax function
