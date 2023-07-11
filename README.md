# Melanoma detection using Convolutional Neural Network (CNN)
> Melanoma is type of skin cancer, develop primarily in the cells (called melanocytes) that produce melanin pigment. Melanoma however can also be developed in eyes, but rarely inside the body.One of the common known reasons for melanoma is prolonged exposure to high amount of UV-radiations, but there are lot more underlying reasons as well ranging from genetic predisposition, epigenetics and many more under investigation. This type of cancer accounts for 75% skin cancer driven deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
A CNN model is to be built using number of images of Melanoma based cancers (learning data) that can help in designing an algorithm helpful in accurate primary diagnosis of different types of Melanoma (testing data). These type of applications are gaining increased traction from scientific and medical community as it can be of huge help in reducing the manual ambiguity in reading the images and can serve as an empirical tool for primary diagnosis. Images are sourced from International Skin Imaging Collaboration (ISIC). 

**The data set contains the images classified under the following disease categories:**
  1. Actinic keratosis
  2. Basal cell carcinoma
  3. Dermatofibroma
  4. Melanoma
  5. Nevus
  6. Pigmented benign keratosis
  7. Seborrheic keratosis
  8. Squamous cell carcinoma
  9. Vascular lesion

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed by the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

**Project Pipeline**: 
  1. Data Reading and understanding
  2. Data Set Creation - Train and Test, with images resized to 180 X 180
  3. Dataset visualization
  4. Model Building and training
  5. Choosing the appropriate data augmentation
  6. Model training on augmented data
  7. Handling class imbalances
  8. Model training on rectified class imbalance data

## Conclusions
- The training accuracy and the validation accuracy are pretty much close which is a sign of good fit.
- Also the losses are quite close & similar jump can be observed between epochs 30-40, for accuracy & loss function, which is also a good sign & generalizes the algorithm better.
- The Validation accuracy comes up to be 86% which is also quite good.

## Libraries Used
- tensorflow
- keras
- pathlib
- matplotlib
- numpy
- pandas
- seaborn
- os
- PIL
- glob


## Contact
Created by 
- Sayan Roy [sayanroy07@gmail.com]
- Vivek Sharma [biotechno16@gmail.com]
