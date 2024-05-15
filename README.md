# Loan Status Prediction Using SVM Classifier :

# Overview
This project leverages a Support Vector Machine (SVM) classifier to predict the status of loan applications. The main goal is to classify whether a loan application will be approved or rejected based on applicant and loan-specific features. SVM is chosen for its effectiveness in handling classification tasks, particularly with high-dimensional data.

# Support Vector Machine (SVM) Theory :
Basics of SVM
SVM is a supervised learning algorithm used for classification and regression tasks. The primary objective of an SVM classifier is to find the optimal hyperplane that best separates the data points of different classes in the feature space. The hyperplane is chosen to maximize the margin, which is the distance between the hyperplane and the nearest data points from each class (support vectors).

# Key Concepts
Hyperplane: A decision boundary that separates different classes. In two-dimensional space, it is a line, while in higher dimensions, it becomes a plane or hyperplane.
Margin: The gap between the hyperplane and the nearest data points from each class. SVM aims to maximize this margin to ensure robust classification.
Support Vectors: The data points that are closest to the hyperplane and influence its position and orientation. These points are critical in defining the optimal hyperplane.
Kernel Trick: When data is not linearly separable in the original feature space, SVM can use kernel functions to transform the data into a higher-dimensional space where it becomes linearly separable. Common kernels include linear, polynomial, radial basis function (RBF), and sigmoid.



Model Training and Evaluation
* Data Preprocessing: Before training, data must be preprocessed. This involves handling missing values, encoding categorical variables, and normalizing numerical features to ensure they are on a comparable scale.
* Training: The preprocessed data is split into training and test sets. The SVM model is trained on the training set using an appropriate kernel and hyperparameters.
* Evaluation: The trained model is evaluated on the test set using metrics such as accuracy, precision, recall, and F1-score to assess its performance.
  
# Application in Loan Status Prediction
In this project, the SVM classifier is trained on a dataset containing features related to loan applicants, such as income, loan amount, credit history, and others. The target variable is the loan status (approved or rejected). By learning the patterns in the training data, the SVM model aims to accurately predict the loan status for new applicants.
