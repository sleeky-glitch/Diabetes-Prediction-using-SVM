# Diabetes-Prediction-using-SVM

## Contents
  
  data.csv : Data file contaning values.
  diabetes_svm.ipynb : Jupiter notebook containing code.
  
## Libraries used
  1. Pandas
  2. Numpy
  3. sklearn 

## About Project
Diabetes predicition is done using an SVM based on the following patient parameters 
    
    pregnancies
    glucose
    bpressure
    skinfold
    insulin
    bmi
    pedigree
    age

These parameters are fed into an SVM after splitting into training and testing sets , to select the best kernel for our svm we perform hyper parameter optimization using training data.the result finds that polynomial kernel is best for our SVM with accuracy of 78.21%. 
Once Kernel is finalized we train the SVM using training data set and finally give prediction using testing data. The accuracy is then checked and we get an accuracy of 74.8% with our testing data. We also check our data set with zero values and find out that the data has accuracy of 64.57% showing that data set is unbalanced, finally we calculate precision values. precision of patient having diabetes is 0.76 with recall and F1 values as 0.42 and 0.54 respectively.
