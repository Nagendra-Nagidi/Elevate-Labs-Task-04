# Elevate-Labs-Task-04
In the above Taskfolder you can find all the necessary files regarding Task 4. In the Jupyter file 'task4_solutions.ipynb', I have implemented Logistic Regression on Breast Cancer Dataset and created classification model for classifying breast tumors as malignant or benign. I have mainly used pandas,matplotlib to complete data preprocessing and visulisation and mainly dependent on the scikit learn library in python for creating the Logistic Regression model in the following manner:

#### Data Preparation
Loaded the Wisconsin Breast Cancer Diagnostic dataset \
Removed an unnecessary null column (Unnamed: 32) \
Encoded categorical diagnosis labels (M=Malignant, B=Benign) to numerical values

#### Data Preprocessing
Separated features from target variable (diagnosis) \
Split data into training (70%) and testing (30%) sets \
Scaled features using Min-Max normalization (range: 0-1)

#### Model Training
Implemented L2-regularized logistic regression using sklearn package from python. \
Used LBFGS solver with 1000 maximum iterations. \
Trained model on scaled training data.

#### Model Evaluation
Generated confusion matrix to visualize performance. \
Calculated key metrics: Precision, Recall, F1-Score. \
Created ROC curve (AUC = 0.99) showing true vs false positive rates. \
Generated Precision-Recall curve for class imbalance analysis. \
Reported overall accuracy 96.49%.

#### Threshold Optimization
Adjusted classification threshold to prioritize cancer detection \
Identified optimal threshold (0.35) to maximize recall (>95%) \
Achieved recall of 100% (critical for medical diagnosis)


