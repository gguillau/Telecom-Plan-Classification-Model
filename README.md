Identify the right plan for each subscriber based on their behavior, using the historical data available from Telecom Company Plans. 
### Background
This project is part of the Data Scientist training program from Practicum by Yandex. More info in link below:

https://practicum.yandex.com/data-scientist

## Objective
 Build machine learning model with highest accuracy. Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra. Develop a model that will pick the right plan with the highest possible accuracy. In this project, the threshold for accuracy is 0.75. Check the accuracy using the test dataset.


## Data Description
Data about subscribers who have already switched to the new plans (from the project for the Statistical Data Analysis course). Every observation in the dataset contains monthly behavior information about one user. The information given is as follows:

* сalls — number of calls,
* minutes — total call duration in minutes,
* messages — number of text messages,
* mb_used — Internet traffic used in MB,
* is_ultra — plan for the current month (Ultra - 1, Smart - 0).


## Models Evaluated
* Decision Tree Classifier
* Random Forest Classifier
* Logistic Regression
