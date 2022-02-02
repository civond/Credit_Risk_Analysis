# Credit_Risk_Analysis

<h2>Overview</h2>
In this challenge, I was able to apply machine learning in predicting credit risk using scikit-learn. Specifically, I used resampling, SMOTEENN, and ensemble classififiers such as balanced random forest and easy ensemble adaboost.
<h2>Results</h2>
Summary of the results of each machine learning models used:
  <ul>
      <li>Naive Oversampling:
        <br/>Accuracy Score - 66.3%, 
           <br/>Precision for bad credit - 0.01, Recall for bad credit - 0.71
         <br/>Precision for good credit - 1.00 Recall for good credit - 0.61<br/><br/>
    </li>
      <li>SMOTE Oversampling:
        <br/>Accuracy Score - 64.2%%, 
           <br/>Precision for bad credit - 0.01, Recall for bad credit - 0.60
         <br/>Precision for good credit - 1.00, Recall for good credit - 0.68<br/><br/>
    </li>
    <li>Undersampling:
        <br/>Accuracy Score - 54.3%, 
           <br/>Precision for bad credit - 0.01, Recall for bad credit - 0.68
         <br/>Precision for good credit - 1.00, Recall for good credit - 0.40<br/><br/>
    </li>
    <li>Combination Sampling:
        <br/>Accuracy Score - 65.5%, 
           <br/>Precision for bad credit - 0.01, Recall for bad credit - 0.75
         <br/>Precision for good credit - 1.00, Recall for good credit - 0.56<br/><br/>
    </li>
    <li>Balanced Random Forest:
        <br/>Accuracy Score - 88.0%, 
           <br/>Precision for bad credit - 0.03, Recall for bad credit - 0.70
         <br/>Precision for good credit - 1.00, Recall for good credit - 0.88<br/><br/>
    </li>
    <li>Easy Ensemble AdaBoost Classifier:
        <br/>Accuracy Score - 94.2%, 
           <br/>Precision for bad credit - 0.09, Recall for bad credit - 0.92
         <br/>Precision for good credit - 1.00, Recall for good credit - 0.94<br/>
    </li>
  </ul>
<h2>Summary</h2>
Of all of the models used, I recommend the Easy Ensemble AdaBoost Classifier! Although it is more precise when predicitng bad credit than the other models, another important thing to note is that it's more sensitive. Sensitivity in this case is valued because we wish to limit the number of bad credit loans.
<br/><br/>
With that being said, this model is not good enough for use in the real world. The sensitivity towards bad credit should must be higher in order to pass. 
