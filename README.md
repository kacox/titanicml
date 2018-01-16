### investigatedataset
# Repository for Investigate a Dataset

View project report here: https://kacox.github.io/investigatedataset/

## Overview
This project is an analysis of the Titanic Dataset from Kaggle.com using Jupyter Notebook, Python, Pandas, NumPy, and Seaborn. The dataset contains information for 891 passengers with 12 variables. The goal of this investigation was to determine if any variables correlate with passenger survival.

**Information on dataset**   
_Data Dictionary_  
survival: Survival; 0 = No, 1 = Yes  
pclass: Ticket class, a proxy for socio-economic status (SES); 1 = 1st (Upper), 2 = 2nd (Middle), 3 = 3rd (Lower)  
sex: Sex of passenger  
Age: Age in years  
sibsp: # of siblings / spouses aboard the Titanic  
parch: # of parents / children aboard the Titanic  
ticket: Ticket number  
fare: Passenger fare  
cabin: Cabin number  
embarked: Port of Embarkation; C = Cherbourg, Q = Queenstown, S = Southampton  

_Variable Notes_  
age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...  
Sibling = brother, sister, stepbrother, stepsister  
Spouse = husband, wife (mistresses and fiancés were ignored)  

parch: The dataset defines family relations in this way...  
Parent = mother, father  
Child = daughter, son, stepdaughter, stepson  
Some children travelled only with a nanny, therefore parch=0 for them.  

**Question guiding investigation:** Which passenger characteristics correlate with survival?

## Files
**index.html** - Main file of finished project (HTML file)  
**Titanic.ipynb** - Investigation code (iPython notebook)  
**titanic_data.csv** - Data source for analysis (CSV)  
**README.md** - Information on data set and variales (Markdown file)  
**resource_list.txt** - References used in analysis (Plain text file)
