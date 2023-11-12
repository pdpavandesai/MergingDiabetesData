# Classification of diabetes through symptoms & clinical features using machine learning and recommending the remedies based on the result

This repository has 2 kinds of datasets i.e., Symptomatic feature set("By Ishan Dutta") and clinical feature set("ByGabriel" and "ByMustafa").

We do exploratory data analysis on each dataset where the duplicate records are removed, outliers are identified and treated.

Post EDA we find co-relation between the features and target variable and finalise the features for training.

Our target variable is Diabetes which defines 0 & 1, where 0 being "negative for diabetes" & 1 being "positive for diabetes"

#### For symptomatic feature set we selected ['Polyuria,'Polydipsia','SuddenWeightLoss','PartialParesis','Polyphagia','Irritability','VisualBlurring'] and for clinical feature set we selected ['Age','HighBP','HighChol','BMI']

Based on the result from symptomatic feature set if the patient is likely to have diabetes we recommend the patient(user) to process few clinical tests for accurate prediction of diabetes. This clinical tests include finding their BMI, BP, Cholestrol level, blood-sugar level, Hb1AC level.

#### The classification(likelihood) of diabetes from symptomatic feature is derived by training a model based on "Decision Tree classifier" which had an accuracy of 92.06%. And we predict diabetes from clinical test features by training a model based on "Multi-layer Perceptron classifier" (an ANN: Artifician Neural Network) with an accuracy of 87.38%.

As per the result derived from the above models we classify the type of diabetes & recommend the remedies to the patient(user) based on their age, BMI, blood-sugar level, BP level, cholestrol, & Hb1Ac levels.
