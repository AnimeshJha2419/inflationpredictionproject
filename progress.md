# Final project progress report
### ISTA421/INFO521

-------

Project: [Inflation forecasting model]
Names:
- [Animesh Kumar Jha]
- [Sarthak Chauhan]    
- [Abhiraj Rana] 
-------


## Instructions

You report should be a short summary of your project progress. This report is relevant to to us, your instructors, and probably to the rest of the class.

Please use this report as a chance to organize your thoughts about what you are trying to do with your project, and to get feedback on your ideas, and the approaches that you have tried so far.

## Submission

Please commit this file to your GitHub repo (progress.md) AND to D2L.


-------

### GitHub repo usage
Currently we have updated our proposal for the project to our github repo. We have commited twice to the repo and have updated our proposal once, to better suit the structure provided by our instructor.
Although we haven't uploaded any code for our final project, however we have uploaded the dataset for our final project that would be utilized during our prediction analysis.


### Summarize your data
This dataset, which covers the US macroeconomic variables from May 2002 to May 2022 in month-by-month detail, can be used to analyze how various macroeconomic factors interact with one another.
data was gathered and sourced from US government sources including FRED, CENSUS, OECD, and Conference Board.
collected demographic information from the OECD, consumer confidence index from the Conference Board, and economic data from the FRED official website, including income, GDP, various indexes, mortgage, etc. 
'Median Household Income in the US' column has many missing values and we would like to convert them into null values for using this feature.
A potential issue we might face is that the amount of data present in the dataset isd quite low and hence we might have to add data from other sources in order to have a better predictive accuracy.



### Describe your initial analysis strategy
We began with preprocessing our data by tuning parameters and removing the data inconsistencies within the dataset, to select the best accuracy, Residual Sum of Squares, R-Squared, Residual Standard Error, and bias-varience trade-off. 
Initally we want to apply few algorithms and select the best subset of features that would provide best accuracy


### What you have tried so far?
We split the dataset into 30% training and 70% testing data. we are implementing forward selection while applying the random forest algorithm to select the best subset that we can find. We are also currently applying the forward selection algorithm with vector regression and quantile regression forest to make sure we use the best features for all the algorithms.


### What worked and what did not
The forward selection has provide us with a few features that seem to be the most important in predicting with high accuracy. Though, the dataset is small in size and might not be providing the most accurate output. The feature 'Median Household Income in the US' has many missing and hence it might affect our analysis.


### What you plan to do next...
_Please define explicit goals for each of the remaining weeks (before the presentation is due)_

- Week 1: Find more data for the dataset and apply the data preprocessing step on it again. 
- Week 2: Apply each of the algorithms and find the best prediction by comparing accuracy, Residual Sum of Squares, R-Squared, Residual Standard Error, and bias-varience trade-off.
- Week 3: Apply final analysis and provide the best algorithm for prediction. Creating the documentation and powerpoint. 

### Author contributions
_Describe the contributions of each of the members to the current version of the project_


Student 1: [Animesh Kumar Jha]
- [X] Development of question / hypothesis;
- [X] Data research: search for relevant data to contribute to question;
- [ ] Literature review;
- [X] Analysis strategy;
- [X] Analysis code;
- [ ] Code review;
- [X] Work planning and organization;
- [X] Improving teamwork and collaboration;
- [ ] Testing code and procedures;
- [X] Writing report.
- [ ] Additional comments:

Student 2: [Sarthak Chauhan]
- [X] Development of question / hypothesis;
- [X] Data research: search for relevant data to contribute to question;
- [ ] Literature review;
- [X] Analysis strategy;
- [X] Analysis code;
- [X] Code review;
- [ ] Work planning and organization;
- [X] Improving teamwork and collaboration;
- [X] Testing code and procedures;
- [ ] Writing report.
- [ ] Additional comments:

Student 3: [Abhiraj Rana]
- [X] Development of question / hypothesis;
- [X] Data research: search for relevant data to contribute to question;
- [X] Literature review;
- [X] Analysis strategy;
- [X] Analysis code;
- [ ] Code review;
- [X] Work planning and organization;
- [ ] Improving teamwork and collaboration;
- [ ] Testing code and procedures;
- [X] Writing report.
- [ ] Additional comments:
