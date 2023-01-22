# Project Name
Multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* EDA, Data preparation 
* CNN without data augmentation, dropout
* CNN with data augmentation & dropouts
* CNN with more epochs from previous checkpoint

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
![Overview](https://user-images.githubusercontent.com/40735287/213917280-8f310361-488f-48b2-8520-79f7c9c9a569.jpg)

![Imbalance](https://user-images.githubusercontent.com/40735287/213917289-e53aa130-f942-48be-bf1b-1329d81eca74.jpg)

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

![Metrics](https://user-images.githubusercontent.com/40735287/213917070-de182045-4db2-4b9d-b54c-a0b142f94a9b.jpg)
Further Learning without Over Fitting
![Metrics_1](https://user-images.githubusercontent.com/40735287/213917168-445e6d54-a4c0-46c5-9614-b9850bdaa970.jpg)

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
