# NASA_stars_classification


This is a classification project based on the NASA star classification dataset from Kaggle.<br> 
Temperature = Temperature(K)<br>
L = Relative Luminosity<br>
R = Relative Radius<br>
A_M = Absolute Magnitude<br>
Color = Color<br>
Spectral_Class = SMASS Spec.<br>
Type – Type; One-Hot from 0 to 5<br>
The aim of the project is to correctly identify the type each star belongs to, based on its features. In order to do this, I started with some data visualization and analysis; checking to see if there are any null values or duplicate values and generating graphs, bar plots, boxplots and so on in order to see the relationships and correlation between features. 
After some data cleaning, I decided to use sklearn’s RandomForestClassifier and LogisticRegression for classification.<br> 
Libraries used:pandas, matplotlib, seaborn, sklearn.
