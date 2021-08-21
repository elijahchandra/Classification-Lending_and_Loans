This exercise accomplishes the following tasks:

1. Resampling 
   
   Using the imbalanced learn library, it resamples the LendingClub data and build and evaluate logistic regression classifiers using the resampled data.
    
    a. Spliting the data into Training and Testing sets.
   
    b. Scaling the training and testing data using the StandardScaler from sklearn.preprocessing.
    
    c. Runs a Simple Logistic Regression:
       i.   Fits the logistic regression classifier.
       ii.  Calculates the balanced accuracy score.
       iii. Displays the confusion matrix.
       iv.  Prints the imbalanced classification report.
    
    d. Oversampling the data using the Naive Random Oversampler and SMOTE algorithms.
    
    e. Undersampling the data using the Cluster Centroids algorithm.
    
    f. Over- and undersampling using a combination SMOTEENN algorithm.
    
    g. From each of the above, the following steps were also taken:
       i.   Training a logistic regression classifier from sklearn.linear_model using the resampled data.
       ii.  Calculating the balanced accuracy score from sklearn.metrics.
       iii. Displing the confusion matrix from sklearn.metrics.
       iv.  Printing the imbalanced classification report from imblearn.metrics.
       
2.  Ensemble Learning
    
    This section trains and compares two different ensemble classifiers to predict loan risk and evaluate the given models through the Balanced Random Forest Classifier and the Easy Ensemble Classifier.
     
     a. Spliting the data into Training and Testing sets.
     
     b. Scaling the training and testing data using the StandardScaler from sklearn.preprocessing. 
     
     c. The following steps were made for each model:
        i.   Training the model using the quarterly data.
        ii.  Calculating the balanced accuracy score from sklearn.metrics.
        iii. Displays the confusion matrix from sklearn.metrics.
        iv.  Generates a classification report using the imbalanced_classification_report from imbalanced learn.
