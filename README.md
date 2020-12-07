## Identifying Bone X-rays

## Executive Summary

In many areas of the world, radiologists interpret radiographs visually to determine whether there are defects in bone structures. The supervised machine learning models developed in this capstone estimates the probability of an X-ray image showing a musculoskeletal abnormality, or not.

The dataset used for this study was made available by Stanford University, and can be found in the link: (https://stanfordmlgroup.github.io/competitions/mura/).

The dataset is organized in multiple folders already divided into training and validation groups. These folders contain image for seven body parts located in the upper extremities: elbow, humerus, wrist, hand, finger, shoulder and forearm.

Each upper extremity folder is further subdivided into patient information, which is further subdivided into two study folders. Negative and positive X-ray folders. The negative X-rays feature bones without abnormalities, while the positive X-rays show some abnormality.e.g.fractures.



The approach developed to estimate the probability of an X-ray image identifying abnormalities involved dividing the problem into three parts:

* Image preprocessing, 
* Feature extraction and 
* Classification of images using machine learning models.



The machine learning algorithm used in this project are : Logistic Regression, KNN, Random Forest Classifier and SVM.
The performance evaluation of the abnormality detection for the dataset was performed by using three statistical parameters. These parameters are: recall, precision and F1-score.

Amongst the four models assesed for the prediction; the Random forest classifier gave the best F1-Score of 0.67 for the abnormal class, while the best upper extremity body part predicted was the finger body part.
 


Links to the report, code, presentation and machine learning model can be seen in the link below.

[BoneX-Rays PDF Reports](https://github.com/dreamtx01/BoneXRays/tree/master/Documents)

[Code](https://github.com/dreamtx01/BoneXRays/tree/master/Code)

[Slide Presentation](https://github.com/dreamtx01/BoneXRays/blob/master/Documents/Capstone2_Identifying%20XRays_SlideDeck%20(2).pdf)

[Machine Learning Model_Code](https://github.com/dreamtx01/BoneXRays/blob/master/Code/Capstone2_Machine_Learning_ver4.ipynb)

[Final Report](https://github.com/dreamtx01/BoneXRays/blob/master/Documents/Capstone2%20_Final%20Report.pdf)
