# Breast-Cancer-Detection-ML
Breast Cancer is a leading type of cancer in women accounting for 25% of all cases. In 2018 it resulted in 2 million new cases and 627,000 deaths.

## Background Information
The dataset is created by William H.Wolberg physician at the University of Wisconsin Hospital. The features are computed through a digitized image of Fine Needle Aspirate of a breast mass. They describe the characteristic of cell nuclei which help in describing whether the cancer is benign or malignant.

## Business Goal
Early diagnosis plays an important role in increasing the survival rate of women. The idea here is to building a model to predict whether a cancer is benign or malignant. 

## Data Description
Data Source : Kaggle
Data Source Link : https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

The Dataset used for the analysis includes the following columns:
1. ID number 
2. Diagnosis (M = malignant, B = benign) 
3-32. Ten real-valued features are computed for each cell nucleus: 
- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values) 
- perimeter 
- area 
- smoothness (local variation in radius lengths) 
- compactness (perimeter^2 / area - 1.0) 
- concavity (severity of concave portions of the contour) 
- concave points (number of concave portions of the contour) 
- symmetry 
- fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

## Conclusion
The ML model for the problem statement was created using python with the help of the dataset, and the ML model created with Random Forest models performed better than other Classification Model. Thus, for the given problem, the models created by Random Forest provided higher accuracy of 98%.
