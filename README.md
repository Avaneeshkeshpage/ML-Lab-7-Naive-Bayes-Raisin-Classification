# Lab 7: Naive Bayes Classification

Implementation of the Gaussian Naive Bayes algorithm to classify raisins as Kecimen or Besni using the Raisin dataset.

## Student
Avaneesh Keshpage | Section A | Batch A4 | Roll No 64
B.Tech AIML, Ramdeobaba University

## Dataset
Raisin_Dataset.xlsx: 900 samples, 7 numeric features (Area, MajorAxisLength, MinorAxisLength, Eccentricity, ConvexArea, Extent, Perimeter), 2 balanced classes.

## What the notebook does
- Exploratory data analysis: bar plot, pie chart, histograms, box plots, KDE plots, correlation matrix, scatter plots
- Label encoding and 80/20 train-test split
- Gaussian Naive Bayes training and prediction
- Evaluation: accuracy, precision, recall, F1-score, confusion matrix
- var_smoothing hyperparameter tuning and prediction on a new sample

## Results
Test accuracy 82.78%, training accuracy 82.22%, best accuracy 83.33% at var_smoothing = 1e-5.

## Requirements
Python 3, pandas, numpy, matplotlib, seaborn, scikit-learn, openpyxl
