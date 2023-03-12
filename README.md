# Melanoma-detection-CNN
> The aim of the project is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

- The data set contains the following diseases:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion

## Conclusions
- The final model used the Augmentor library to artificially generate enough samples to come up with a model that can detect a correct cancer type with a validation accuracy around 88%. 
- The validation loss for the final model was 0.51

## Technologies Used
- Keras - 2.11.0
- Tensorflow - 2.11.0
- Augmentor - 0.2.10

## Acknowledgements
- This project was inspired by a case study from the Executive PG Programm in Machine Learning by IIIT Bengaluru


## Contact
Created by [@k1anshul] - feel free to contact me!
