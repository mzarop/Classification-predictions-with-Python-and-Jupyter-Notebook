# heart-disease classification predictions.
#Predicting heart disease using machine learning
#This notebook looks into using various Python-based machine learning and data science liblaries in an attempt to built a machine #learning model capable of predicting whether or not someone has heart disease based on their medical attibutes.

#We're going to take the following approach:

#Problem Definition
#Data
#Evaluation
#Features
#Modelling
#Experimentation
#1. Problem Definition
#In a statement,

#Given clinical parameters about a patient , can we predict whether or not they have heart-diseases?

#2. Data
#The original data came from the Cleavland data from the UCI Machine learning #Repository.https://archive.ics.uci.edu/ml/datasets/Heart+Disease

#There is also a version of it available in Kaggel https://www.kaggle.com/ronitf/heart-disease-uci

#3. Evaluation
#If we can reach 95% accuracy whether or not a patient has heart disease during the proof of concept, we ll pursue the project.

#4. Features
#This is were you'll get different information about each of the features in the data.

#Create a data dictionary

#ageage in years sex(1 = male; 0 = female) cpchest pain type trestbpsresting blood pressure (in mm Hg on admission to the hospital) #cholserum cholestoral in mg/dl fbs(fasting blood sugar > 120 mg/dl) (1 = true; 0 = false) restecgresting electrocardiographic results #thalachmaximum heart rate achieved exangexercise induced angina (1 = yes; 0 = no) oldpeakST depression induced by exercise relative to #rest slopethe slope of the peak exercise ST segment canumber of major vessels (0-3) colored by flourosopy thal3 = normal; 6 = fixed #defect; 7 = reversable defect target1 or 0
