# Seattle Collisions Data Analysis
# Problem description:

In this repository, machine learning algorithms have been developed to predict accident severity using Seattle collisions data. 
The accident severity varies based on a wide range of factors, including weather conditions, light conditions, speeding, etc. Analysis of collisions data enables us to determine the severity of road accidents under different conditions. Therefore, restrict regulations or warning systems can be designed to reduce road traffic injuries and fatalities under high-risk circumstances.  

# Data description:

City of Seattle has released an open source dataset containing all types of collision since 2014 to present. This dataset is updated weekly.

The dataset contains 194673 rows, each of them reperents a collision sample. Also, it contains 38 columns:
  - 37 features (independent variables), and 
  - "SEVERITYCODE" as the dependent variable which is going to be predicted based on the provided features.
  
 In this dataset, the accident severity ("SEVERITYCODE") is divided to 5 categories:
  - 0: Unknown
  - 1: Property Damage Only Collision
  - 2: Injury Collision	
  - 2b: Serious Injury Collision	
  - 3: Fatality Collision
  
 # Data pre-processing:
 
 The following actions have been performed to preprocess the data before feeding it to the models:
  - removing NULL or NaN values
  - performing standardization (if it is needed) to bring the features on the same scale
  - converting categorical variables to numerical variables
  - feature selection, removing non-relevant columns to the prediction task, avoiding multicollinearity 
 
 # Methodology:
 
 To predict accident severity using Saettle collisions data, following machine learning algorithms have been employed to classify the acident severity as one of 5 existing categories:
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Naive Bayes
  - Random Forest
  - Gradient Boosting
  - Support Vecotor Machine (SVM)
  - Logistic Regression
  
 # Results
 
 # Conclusion

 
 
  
 
