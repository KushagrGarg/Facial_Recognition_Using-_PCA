# **Facial Recognition Using PCA**

## Objective:

Face Recognition using Principal Component Analysis - PCA using 6 photos for training and 4 images for testing for 40 individual persons.

## Process:

1. Prepare a face training dataset
2. Compute the average face vector
3. Subtract the average face vector from original images
4. Calculate the covariance matrix
5. Calculate the eigenvalues
6. Compute a suitable value for K
7. Create features weight for training
8. Read the testing face image
9. Calculate the feature vector of the testing face
10. Compute the Euclidean distance between the test feature vector and all the training feature vector
11. Find the face class with minimum distance
12. Thus find Testing Accuracy.

## Results and Analysis:

![](Accuracy%20Curve.png)

Computed Value for k = 80

Maximum Accuracy = 94%
