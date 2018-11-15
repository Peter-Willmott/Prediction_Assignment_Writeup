# Prediction_Assignment_Writeup
Coursera Machine Learning Assignment

This document is just the basic readme, the actual assignment writeup can either be viewed using the PDF document in the repo or using the gh-pages html to view the html online.

The link to the html is found here:

https://peter-willmott.github.io/Prediction_Assignment_Writeup/

Thank you for giving my project a look!



### Background

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting Exercise Dataset).

### Data

The training data for this project are available here:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available here:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

The data for this project come from this source: http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har. If you use the document you create for this class for any purpose please cite them as they have been very generous in allowing their data to be used for this kind of assignment.

### Executive Summary

Executive Summary
This project aims to use data from accelerometers, placed on the arm, forearm, belt, and dumbell, to quantify and predict ‘how well’ a particular activity is performed. In this case 10 repetitions of the Unilateral Dumbell Biceps Curl. 6 male participants (20 - 28 years) lifted a dumbell (1.25kg) in 5 different fashions:

Class A: Exactly according to specification
Class B: Throwing the elbows to the front
Class C: Lifting the dumbell only halfway
Class D: Lowering the dumbell only halfway
Class E: Throwing the hips to the front
The data set is credited to Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. Qualitative Activity Recognition of Weight Lifting Excercises.

The final model was able to predict the manner in which they did excercise to an accuracy of 99.3% (Based on a Validation Data set) and an out of bag (OOB) error of 0.72%. The best model was Random Forest (RF), which produced greater accuracy than both Gradient Boosting Machine (GBM) and Linear discriminant analysis (LDA). Cross validation was used to estimate models accuracy.
