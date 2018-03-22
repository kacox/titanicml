### investigatedataset
# Repository for Titanic: Machine Learning from Disaster

View project page here: https://kacox.github.io/titanicml/

## Overview
This project is an analysis of and deployment of a machine learning algorithm on the Titanic Dataset from Kaggle.com.

**Part 1: Investigate a Dataset**  
The dataset ("titanic_data.csv") contains information for 891 passengers with 12 variables. The goal of this investigation was to determine if any variables correlate with passenger survival.

_Tools/technologies:_ Python, NumPy, Pandas, Seaborn

**Part 2: Machine Learning Addendum**  
For this part of the project, a machine learning algorithm is developed and deployed to predict which passengers survived the sinking of the Titanic. Part 1 (finding which passenger characteristics correlate with survival) serves as a basis for feature selection in this addendum.

Two sets of data are used: "train.csv" and "test.csv". "train.csv" has 891 data points and 12 variables while "test.csv" has 418 data points and 11 variables.

_Tools/technologies:_ Python, NumPy, Pandas, scikit-learn 

**Information on dataset**   
PassengerId: unique identifier for passenger  
Survived: Survival; 0 = No, 1 = Yes  
Pclass: Ticket class, a proxy for socio-economic status (SES); 1 = 1st (Upper), 2 = 2nd (Middle), 3 = 3rd (Lower)  
Name: Name of passenger  
Sex: Sex of passenger  
Age: Age in years  
Sibsp: # of siblings / spouses aboard the Titanic  
Parch: # of parents / children aboard the Titanic  
Ticket: Ticket number  
Fare: Passenger fare  
Cabin: Cabin number  
Embarked: Port of Embarkation; C = Cherbourg, Q = Queenstown, S = Southampton  

_Variable Notes_  
age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...  
Sibling = brother, sister, stepbrother, stepsister  
Spouse = husband, wife (mistresses and fiancés were ignored)  

parch: The dataset defines family relations in this way...  
Parent = mother, father  
Child = daughter, son, stepdaughter, stepson  
Some children travelled only with a nanny, therefore parch=0 for them.  


## Files
**index.html** - Main file of finished project (HTML file)  
**Titanic_investigate.html** - Part 1 report (HTML file)  
**Titanic_ML.html** - Part 2 report (HTML file)  
**Titanic.ipynb** - Investigation code for Part 1 (iPython notebook)  
**Titanic_ML.ipynb** - Investigation code for Part 2 (iPython notebook)  
**titanic_data.csv** - Data source for Part I (CSV)  
**train.csv** - Training data for Part II (CSV)  
**test.csv** - Test data for Part II (CSV)  
**submission.csv** - Predictions from Part II (CSV)  
**README.md** - Information on data set and variables (Markdown file)  
**resource_list.txt** - References used in analysis (Plain text file)
