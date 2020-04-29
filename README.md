# Breast-Cancer-Prediciton
UCI MAMMOGRAPHIC MASS DATASET

Predict whether a mammogram mass is benign or malignant.

Data Contains variables as given below:

1-BI-RADS assessment: 1 to 5 (ordinal)
2-Age: patient's age in years (integer)
3-Shape: mass shape: round=1 oval=2 lobular=3 irregular=4 (nominal)
4-Margin: mass margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal)
5-Density: mass density high=1 iso=2 low=3 fat-containing=4 (ordinal)
6-Severity: benign=0 or malignant=1 (binominal)

Outcomes:

Cross-Validation Scores

Decision Tree - 79.32%

Random Forest - 80.59%

Support Vector Machine (Different Kernels)
Linear=81.41%
Poly=80.47%
Gaussain Kernel (rbf)=82.62%
Sigmoid Kernel=76.51%

#Hence we will go for Gaussian Radial Basis Kernel


K-Nearest Neighbors
n=14, 80.60%

Naive-Bayes - 72.16%

Logistic Regression - 82.52%

Neural Netork - 73.73%


K


