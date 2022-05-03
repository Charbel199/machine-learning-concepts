# Classification Metrics

There are many relevant classification metrics to evaluate machine learning model.
Here are the most relevant ones:

## Accuracy
Accuracy measures how often the classifier predicts correctly.
<br>
<br>
![accuracy](https://latex.codecogs.com/gif.latex?Accuracy%20%3D%20%5Cfrac%7BTP%20&plus;%20TN%7D%7B%5Ctext%7BSample%20Size%7D%7D)

## Precision
Precision explains how many of the correctly predicted cases actually turned out to be positive. It is useful when False Positives are a higher concern than False Negatives.
<br>
<br>
![precision](https://latex.codecogs.com/gif.latex?%5Clarge%20Precision%20%3D%20%5Cfrac%7BTP%7D%7BTP%20&plus;%20FP%7D)

## Recall
Recall explains how many of the actual positive cases we were able to predict correctly with our model. It is useful when False Negatives are of higher concern than False Positives.
<br>
<br>
![recall](https://latex.codecogs.com/gif.latex?%5Clarge%20Recall%20%3D%20%5Cfrac%7BTP%7D%7BTP%20&plus;%20FN%7D)

## F1 Score
The F1 score gives a combined idea about Precision and Recall metrics. It is maximum when Precision is equal to Recall.
It also punishes extreme values and is mostly effective in the following scenarios:
* When FP and FN are equally unwanted
* When adding more data does not affect the results
* When true negatives are high
<br>
<br>
![f1score](https://latex.codecogs.com/gif.latex?%5Clarge%20Recall%20%3D%202%20%5Ctimes%20%5Cfrac%7B%5Ctext%7BPrecision%7D%20%5Ctimes%20%5Ctext%7BRecall%7D%20%7D%7B%5Ctext%7BPrecision%7D%20&plus;%20%5Ctext%7BRecall%7D%7D)
