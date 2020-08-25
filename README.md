# Tanzanian Water Pump Analysis
## Taylor Stanley
### Flatiron School Module 3 Project

#### Introduction
A look into the Tanzanian Water Pump data set provided by DrivenData and collected by Taarifa 
(https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/) to create a predictive classification
model to determine the functionality of each water pump.  The three target classes were: Functional, 
Functional - Needs Repair, and Non Functional.

#### Approach
The first approach to developing this model involved a lot of data cleaning as the data contains 7 continuous features
and 30 categorical features.  This meant a lot of feature dropping, converting, or binning followed by the creation of 
a dummy feature for each category in a partiular feature. Some of the continuous features needed to be converted to 
binary categorical ones as well, while others were able to benefit from some interpolation engineering.

#### Summary
The final model developed achieved an accuracy score of 76%.  There proved much difficulty in seperating Functional - Needs
Repair from Functional as one could imagine.  And for the purposes of the business case associated with this project,
identifying which pumps needed repair before they broke was critical.

#### Sample Data Visualizations

#### Payment Types vs Functionality

![png](README_files\output_99_1.png)

![png](README_files\output_98_1.png)

#### Paid or Free Pump Management vs Functionality

![png](README_files\output_83_0.png)

#### Confusion Matrix &  Classification Report

![png](README_files\output_18_1.png)

![png](README_files\output_29_0.png)


