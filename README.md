# What-am-i-doing-right-now-?

Human Activity Recognition Using Python

A modern smartphone comes equipped with variety of sensors from motion detectors to optical calibrators. The data collected by these sensors is valuable for better aligning the applications on the phone with user’s lifestyle. In this project, we have focused on using data collected from motion sensors to build a model which identifies type of activity being performed with minimal computation involved. The end goal is to create a model which can classify the activity being performed with high accuracy without sacrificing the limited computational resources available on a single phone.

The data used is provided by Human Activity Recognition research project, which built this database from the recordings of 30 subjects performing activities of daily living (ADL) while carrying a waistmounted smartphone with embedded inertial sensors.This data was collected for 30 volunteers whose age was between 19-48 years. Each record in the data represents information about features like acceleration along x,y,z axes, velocity along a,y,z axes, 561 attributes derived from these basic measurements, identifier variable for the user & the activity being performed. There are 6 categories of activities being performed: 

1. 'standing' 
2. 'sitting' 
3. 'laying' 
4. 'walk' 
5. 'walkdown' 
6. 'walkup'  

In this dataset, a single column(‘subject’) is used to identify a user and the last column(‘activity’) was used to identify the activity being performed when the measurements were taken. All other attributes are available in the same column-oriented data format. This is important to know, because, the values in the dataset have been normalized. 

## Technologies/Libraries used:
* Panda
* Numpy
* Seaborn
* Matplotlib
* Scikit-learn

## Models implemented:
* t-SNE
* KNeighbors Classifier
* Logistic Regression(Multi-Class)
* Support Vector Classifier(Multi-Class)
* Random Forest Classifier(Feature Importances)
* Principle Component Analysis(Feature Selection)
