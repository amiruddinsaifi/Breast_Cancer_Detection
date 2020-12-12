# Breast-Cancer-Detection-App
 Breast Cancer Detection App Using Machine Learning XGBoost Classifier
 
![](static/images/Indian%20AI%20Hospital.jpg)


Breast cancer is a dangerous disease for women. If it does not identify in the early-stage then the result will be the death of the patient. It is a common cancer in women worldwide. Worldwide near about 12% of women affected by breast cancer and the number is still increasing.

The doctors do not identify each and every breast cancer patient. That’s the reason Machine Learning Engineer / Data Scientist comes into the picture because they have knowledge of maths and computational power.

# Goal of the ML project

I have extracted features of breast cancer patient cells and normal person cells. As a Machine learning engineer / Data Scientist has to create an ML model to classify malignant and benign tumor. To complete this ML project we are using the supervised machine learning classifier algorithm.

# Datasets

I did load  breast cancer data using a scikit-learn load_brast_cancer class.

## Description of dataset


.. _breast_cancer_dataset:
 
Breast cancer wisconsin (diagnostic) dataset
--------------------------------------------
 
**Data Set Characteristics:**
    * :Number of Instances: 569
    * :Number of Attributes: 30 numeric, predictive attributes and the class
    * :Attribute Information:
      * - radius (mean of distances from center to points on the perimeter)
      * - texture (standard deviation of gray-scale values)
      * - perimeter
      * - area
      * - smoothness (local variation in radius lengths)
      * - compactness (perimeter^2 / area - 1.0)
      * - concavity (severity of concave portions of the contour)
      * - concave points (number of concave portions of the contour)
      * - symmetry 
      * - fractal dimension ("coastline approximation" - 1
 
        The mean, standard error, and "worst" or largest (mean of the three
        largest values) of these features were computed for each image,
        resulting in 30 features.  For instance, field 3 is Mean Radius, field
        13 is Radius SE, field 23 is Worst Radius.
 
        - class:
                - WDBC-Malignant
                - WDBC-Benign
 
    :Summary Statistics:
    ===================================== ====== ======
                                           Min    Max
    ===================================== ====== ======
    radius (mean):                        6.981  28.11
    texture (mean):                       9.71   39.28
    perimeter (mean):                     43.79  188.5
    area (mean):                          143.5  2501.0
    smoothness (mean):                    0.053  0.163
    compactness (mean):                   0.019  0.345
    concavity (mean):                     0.0    0.427
    concave points (mean):                0.0    0.201
    symmetry (mean):                      0.106  0.304
    fractal dimension (mean):             0.05   0.097
    radius (standard error):              0.112  2.873
    texture (standard error):             0.36   4.885
    perimeter (standard error):           0.757  21.98
    area (standard error):                6.802  542.2
    smoothness (standard error):          0.002  0.031
    compactness (standard error):         0.002  0.135
    concavity (standard error):           0.0    0.396
    concave points (standard error):      0.0    0.053
    symmetry (standard error):            0.008  0.079
    fractal dimension (standard error):   0.001  0.03
    radius (worst):                       7.93   36.04
    texture (worst):                      12.02  49.54
    perimeter (worst):                    50.41  251.2
    area (worst):                         185.2  4254.0
    smoothness (worst):                   0.071  0.223
    compactness (worst):                  0.027  1.058
    concavity (worst):                    0.0    1.252
    concave points (worst):               0.0    0.291
    symmetry (worst):                     0.156  0.664
    fractal dimension (worst):            0.055  0.208
    ===================================== ====== ======
 
    :Missing Attribute Values: None
    :Class Distribution: 212 - Malignant, 357 - Benign
    :Creator:  Dr. William H. Wolberg, W. Nick Street, Olvi L. Mangasarian
    :Donor: Nick Street
    :Date: November, 1995
    
   # Breast Cancer Detection Machine Learning Model Building
   
   * Support Vector Classifier
   * Logistic Regression
   * K – Nearest Neighbor Classifier
   * Naive Bayes Classifier
   * Decision Tree Classifier
   * Random Forest Classifier
   * Adaboost Classifier
   * XGBoost Classifier
   * XGBoost Parameter Tuning Randomized Search
   
   
   # Conclusion
  To get more accurecy i train many supervised algorithm classifier. After training all algorithms, I found that Logistic Regression, Random Forest and XGBoost classifiers are given high accuracy than remain but we have chosen XGBoost.Becouse XGboose gives me 98+% accurecy and it is 2% but it's a best model to predict the tumer.
