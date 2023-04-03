# Predict Diabetes

# About Dataset

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney
Diseases. The objective of the dataset is to diagnostically predict whether a patient has diabetes,
based on certain diagnostic measurements included in the dataset. Several constraints were placed
on the selection of these instances from a larger database. In particular, all patients here are females
at least 21 years old of Pima Indian heritage.2
From the data set in the (.csv) File We can find several variables, some of them are independent
(several medical predictor variables) and only one target dependent variable (Outcome).

#Libraries

   - pandas
   - matplotlib
   - seaborn
   - sci-learn

# Algorithms

    - Logistic Regression
    - Random Forest
    - SVC
    
    Best accuracy - 81%
    
    Hypertuning Parameters

    Best Accuracy after hypertuning - 82%
    
    
In this notebook we carried out in-depth data exploration, making the best use of data visualization. We also cleaned the data, replacing null values with more probable ones, without losing any training instances. Later, after finding a promising model, we optimized it. To achieve even better performance, we finally oversampled the minority class, and selected the best features.

The results are not the best possible, and this is due to the small amount of data available. By having more training instances available most likely our model could have had much better results.
