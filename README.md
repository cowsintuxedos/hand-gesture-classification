# hand-gesture-classification
CS165a Programming Assignment 2, Andrew Lai 9519687

# Histogram of Oriented Gradients (HOG) Metrics
[Jupyter Notebook Link](HOG.ipynb)
### Support Vector Machine Classifier
Accuracy: 0.65570719603  
Confusion Matrix:
```
[[59  1  0  0  0  0  0  0  0  2  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [14 14  0  8  0  0  2  0  0 15  0  2  2  0  1  0  0  0  0  3  0  0  1  0   0  0]  
 [ 0  2 12  6  3  1  0  2  1  1  0 21  3  0  1  0  0  0  0  2  6  0  0  0   1  0]  
 [ 4  9  7 17  3  1  2  0  0  8  0  0  5  0  1  0  0  0  0  0  3  0  1  1   0  0]  
 [ 0  0  0  3 42  5  0  0  0  3  0  0  1  0  0  1  0  0  1  1  2  0  3  0   0  0]  
 [ 0  0  0  0  2 47  0  0  0  0  0  0  0  0  0  0  2  1  1  0  6  0  2  0   0  1]  
 [ 3  1  0  0  1  0 45  0  0  0  0  0  0  0  0  0  0  0 12  0  0  0  0  0   0  0]  
 [ 1  0  0  3  0  0  0 42  0  0  0  0  0  0  4  0  0  0  0  2  4  0  1  2   3  0]  
 [ 0  0  0  0  0  0  0  1 57  0  0  3  0  0  0  0  0  0  0  0  1  0  0  0   0  0]  
 [ 1  2  0  0  0  0  0  0  0 57  0  0  2  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 1  0  0  0  0  0  0  0  0  1 55  0  0  0  0  0  0  0  0  0  5  0  0  0   0  0]  
 [ 6  0  0  0  0  0  0  0  1  0  0 55  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  1  7 14  0  2  0  5  1  0 28  0  0  1  0  0  0  1  0  0  1  0   1  0]  
 [ 2  1  0  0  1 26  1  3  0  0  0  0  2 13  0  3  0  0  1  6  2  0  1  0   0  0]  
 [ 0  3  2  3  0  0  0  4  0  0  0  6  1  0 27  0  0  0  0  0 15  0  1  0   0  0]  
 [ 0  0  0  0  1  1  0  4  0  1  0  0  2  0  0 52  0  0  0  0  0  0  1  0   0  0]  
 [ 0  0  1  2  0  1  1  7  2  0  0  0  0  0  0  1 47  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  9  0  1  1  0  0  0  0  6  0  7  3 28  0  4  2  0  0  0   0  1]  
 [ 0  0  0  0  1  0  0  2  0  0  0  0  0  0  0  1  0  0 58  0  0  0  0  0   0  0]  
 [ 1  0  0  0  0  2  1  5  0  0  0  0  0  0  0  6  0  0  0 47  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  1  0  0  0  0  0  2  0  0  0  0  0 59  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  3  0  0  0  0  0  0  0  0  0  0  0  3 56  0  0   0  0]  
 [ 0  0  0  1  3  5  0  1  0  4  0  0  0  1  1  1  0  0  9  0  2  0 29  0   4  1]  
 [ 8  3  0  7  0  2  0  1  0 24  0  0  0  0  2  0  0  0  0  0  5  0  4  6   0  0]  
 [ 6  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  56  0]  
 [ 1  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  4  1  0  0   7 49]]  
```
ROC Curve:  
![HOG Support Vector Machine](https://i.imgur.com/uX4cvq1.png)


### Gaussian Naive Bayes Classifier
Accuracy: 0.844913151365  
Confusion Matrix:
```
[[58  4  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 3 41  2 10  0  0  2  0  0  2  0  0  0  0  1  0  0  0  0  0  0  0  0  0   1  0]  
 [ 0  2 43  4  1  0  0  0  1  3  0  2  0  0  3  0  0  0  0  0  2  0  0  1   0  0]  
 [ 0  8  4 31  1  0  5  0  0  4  0  0  3  0  0  0  0  0  0  1  0  0  3  2   0  0]  
 [ 0  2  0  0 45  2  0  0  0  0  0  0  2  1  2  0  0  1  0  1  1  0  1  4   0  0]  
 [ 0  1  0  0  1 57  0  0  0  0  0  0  1  1  0  0  0  0  0  0  0  0  1  0   0  0]  
 [ 2  0  0  0  0  0 60  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  1  0  0  0  1  0 50  0  0  0  0  0  0  0  5  0  3  0  0  1  0  1  0   0  0]  
 [ 0  0  0  0  0  0  0  0 61  0  0  0  0  0  0  0  0  1  0  0  0  0  0  0   0  0]  
 [ 0  1  0  1  0  0  0  0  0 54  0  0  2  0  1  0  0  0  0  0  0  0  2  1   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0 58  0  0  0  2  0  0  0  0  0  2  0  0  0   0  0]  
 [ 3  0  0  0  0  0  0  0  0  0  0 58  0  0  0  0  0  0  0  0  1  0  0  0   0  0]  
 [ 0  2  0  0  3  4  1  1  0  1  1  0 46  0  2  0  0  0  0  0  0  0  0  1   0  0]  
 [ 0  0  0  5  1  9  3  0  0  0  0  0  4 34  0  0  0  0  0  6  0  0  0  0   0  0]  
 [ 0  3  0  3  0  0  0  0  0  0  0  0  0  0 54  0  0  0  0  0  2  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 61  0  1  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  1  0  0  0  0  0  0  0  1 60  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  1  0  0  0  0  0  0  0  1  0  0  3 57  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0   0  0]  
 [ 0  0  1  1  0  0  1  0  0  0  0  0  0  0  1  2  0  1  0 55  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0   0  0]  
 [ 0  3  0  5  1  0  0  0  0  0  0  0  1  0  0  0  0  0  0  0  0  0 52  0   0  0]  
 [ 4 14  0  4  0  0  0  0  0  2  0  0  0  0  8  0  0  0  0  0  1  0  0 29   0  0]  
 [ 4  4  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  53  1]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  3  0  0   0 59]]  
```
ROC Curve:  
![HOG Naive Bayes Classifier](https://i.imgur.com/Sillntq.png)


### K-Nearest Neighbors Classifier using 3 Neighbors
Accuracy: 0.980148883375  
Confusion Matrix:
```
[[62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0 60  0  0  0  0  0  0  0  0  0  0  0  2  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  3  3 54  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  1  1   0  0]  
 [ 0  0  0  0 61  1  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  1 60  0  0  0  0  0  0  0  1  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  1  0  0  0  0 61  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  1  0  0  0  0  0 60  0  0  0  0  0  0  0  1  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  1  0  0  0  0  0  0 61  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  2  0  0  0  0  0  0  0 60  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  1  0  2  0  0  0  0  0  0  1 58  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  1  0  0  0  0  0  0  0  0  0 61  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  1  0  0  0  0  0  0  0  0  0  0  0  0 61  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  1  0  0  0  0  0  0  0  0  0  0  0 61  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0   0  0]  
 [ 0  1  0  1  2  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 58   0  0]  
 [ 0  0  0  0  0  0  0  1  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  61  0]  
 [ 0  0  0  0  0  0  0  0  1  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0 61]]  
```
ROC Curve:  
![HOG K-Nearest Neighbors](https://i.imgur.com/Tqdff8c.png) 

### 5-Fold Cross Validation for SVM:
The average score for 5-Fold Cross Validation for the SVM classifier was 0.57, with a standard deviation of .09


# Deep Learning Metrics
[Jupyter Notebook Link](DeepFeatures.ipynb)
### Support Vector Machine Classifier
Accuracy: 0.97952853598  
Confusion Matrix:
```
[[59  3  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0 30  0  0  0 32  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  62  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0 62]]  
```
ROC Curve:  
![Deep Learning SVM](https://i.imgur.com/STcobvX.png)


### Gaussian Naive Bayes Classifier
Accuracy: 0.954094292804  
Confusion Matrix:
```
[[59  0  0  0  0  0  0  0  0  0  3  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0 57  0  2  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  3   0  0]  
 [ 0  1 59  2  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 1  3  0 56  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  2   0  0]  
 [ 0  0  0  0 61  1  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  1 31  0  0  0  0 30  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  1  0  0 58  0  0  0  0  0  0  0  1  0  0  2  0  0  0  0  0  0   0  0]  
 [ 0  0  0  1  0  0  0 60  0  0  0  0  0  0  0  1  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  1  0  0  0  0  0  0  0 58  0  0  1  2  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 59  0  0  0  3   0  0]  
 [ 0  0  0  1  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 61  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0   0  0]  
 [ 0  1  0  2  0  0  0  0  0  0  0  0  0  0  0  0  0  1  0  0  0  0 57  1   0  0]  
 [ 0  0  0  1  0  0  0  0  0  0  0  0  0  0  0  0  0  1  0  0  0  0  1 59   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  1  0  0  61  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  1  0  1  0  0  0  0  0  0  0  0  0   0 60]]  
```
ROC Curve:  
![Deep Learning NBC](https://i.imgur.com/6LJ0vzT.png)


### K-Nearest Neighbors Classifier using 3 Neighbors
Accuracy: 0.978908188586  
Confusion Matrix:
```
[[59  0  0  0  0  0  0  0  0  0  3  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0 61  1  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0 32  0  0  0  0 30  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62  0   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0 62   0  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  62  0]  
 [ 0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  0   0 62]]  
```
ROC Curve:  
![Deep Learning K-Nearest Neighbors](https://i.imgur.com/22FD0Z2.png)


# Analysis
The Deep Convolutional Neural Network outperformed the HOG classifier by a large margin, in terms of accuracy; from the corresponding confusion matrices, the deep learning classifiers produced far fewer false positives as compared to the HOG classifiers, though the K-Nearest Neighbors HOG Classifier was relatively accurate.

