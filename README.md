# Diabete Prediction
College Project

Following are the points mentioned in the description:
1. Problem Statement
2. Dataset Information
3. EDA
4. Accuracy Comparison of Logistic Regression and Random Forest 

Problem Statement:

Diabetes is one of the most frequent diseases worldwide and the number of diabetic patients are growing over the years. The main cause of diabetes remains unknown, yet scientists believe that both genetic factors and environmental lifestyle play a major role in diabetes.

A few years ago research was done on a tribe in America which is called the Pima tribe (also known as the Pima Indians). In this tribe, it was found that the ladies are prone to diabetes very early. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients were females at least 21 years old of Pima Indian heritage. Here, we are analyzing different aspects of Diabetes in the Pima Indians tribe by doing Exploratory Data Analysis and building a classification Model.

Dataset Information:

Below is the attribute information:

Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
Blood pressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skinfold thickness (mm)
Insulin: 2-Hour serum insulin (mu U/ml) test
BMI: Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: A function that scores likelihood of diabetes based on family history
Age: Age in years
Outcome: Class variable (0: the person is not diabetic or 1: the person is diabetic)

Key Points:
- The data comprises of 1000 records and 9 features in total of 9000 elements (size) in the data set
- All the features are of interger data type Except BMI and DiabetesPedigreeFunction which are floating type
- There are no null/missing values
- There are some cases where the  BP is very low and ranges b/w -20 to 20 
- Majority the range of BP falls under 40-130
- The BMI of the person having highest BMI is 42.9
- There are 449 women with glucose level above mean level 
- There is a +ve relation b/w glucose and Insulin i.e. as glucose level is associated with hgh insulin.
-  The majority of age group is b/w 25 -40 years and meadian age is 30 years. There are some sitting above the age of 65 years
- Skinthickness and insulin are highl correlated similar is the case with Age and Pregnancy which is a +ve corrlation and -ve relation is seen b/w Insulin and Pregnance
- Logistic Regrssion - Accuracy for train set is 76% and test is 75%. The TP value is 49 and TN is 63.
- Random Forest - Accuracy for train set is 82% and test is 79%. The TP value is 49 and TN is 63.
- Random forest model is better performer as it has higer accuracy


