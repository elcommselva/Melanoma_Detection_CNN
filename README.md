# Project Name
Multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* EDA, Data preparation 
* CNN without data augmentation, dropout
* CNN with data augmentation & dropouts
* CNN with more epochs from previous checkpoint

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Conclusions
In Train Set: Below have fewer images with respect to other types

    Actinic keratosis
    Dermatofibroma
    Seborrheic keratosis
    Vascular lesion

In Test Set: Below have fewer images with respect to other types

    Seborrheic keratosis
    Vascular lesion

Pigmented benign keratosis has the dominant data

The Data had Imbalance and after handling the imbalance along with Drop outs, Data Augmentation, the Validation Accuracy improved and the Loss decreased.

## Technologies Used
### Linear algebra & data processing
pandas
### Scientific and technical computing
tensorflow
keras
### Visualization
matplotlib 
plotly
seaborn


## Acknowledgements
IIIT-B Study Materials


## Contact
Created by [@elcommselva] - feel free to contact me!