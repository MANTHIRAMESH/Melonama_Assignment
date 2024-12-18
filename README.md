# Project Name : Melonama_Assignment
The main moto of this project is to build a CNN model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.

## Table of Contents
* [General Info](Data sets used in this project: Images Provided by Skin cancer ISIC The International Skin Imaging Collaboration as trainig data)
* [Technologies Used](Libraries used: pathlib,tensorflow,matplotlib.pyplot,PIL, Sequential from tensorflow.keras.models, Augmentor etc.,)

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Conclusions
1. Imbalanced data significantly impacted the training and performance of Model.
2. The model tends to be biased towards the majority class, resulting in poor performance in predicting the minority class.
3. The model might not learn the underlying patterns of the minority class due to the scarcity of examples.
4. Finally after augmentaion of data with sufficient samples model accuracy is increased considerably.
    Acuuracy of final model on training dataset : 0.78
    Acuuracy of final model on validation dataset : 0.75
