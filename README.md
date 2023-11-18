# Deep_Learning_Covid
The purpose of this project is to predict the number of daily COVID-19 – related deaths in Israel 
This project was conducted under a deep learning course in Reichman University by Roy Madpis and Michael Kobaivanov

The purpose of this assignment is to predict the number of daily COVID-19 – related deaths in Israel and other statistics

To complete this assignment, we combined  data sources into a single data frame with daily details on the numbers of deaths and columns like:
- new patients
- aggregate numbers of hospitalized patients (perhaps, distinguishing between server and light cases)
- tests
- people in quarantine
- 
The objectives were predicting the future values of the numbers of the values like:
- Deaths
- Positive patients
- Hospitalized patients (total and separately for different conditions + the number of ventilated machines used).
- Covid tests

### Questions we answer in the document:
a. For each of the cases above predict the future daily number of cases.
Demonstrate few out of sample predictions and estimate accuracy of your algorithms on test set. How accuracy drops as you would look further into the future?

b. Next, assume that you are responsible for resource allocation and management of the pandemic. To do your job properly, you need to predict daily averages of the quantities over one week starting 3 days from the time when the data is still available.
In other words, if today is January 3, 2022, you should compute a single number representing the mean daily number of deaths over the 7 days starting from January 6. For each of the 3 last weeks in December 2020 and for each of the quantities above report

- the numbers you predict.
- the actual numbers observed.
- Relative error.
