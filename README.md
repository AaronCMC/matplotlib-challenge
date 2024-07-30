# matplotlib-challenge

## Background
249 mice identified with SCC tumors received treatment with a range of drug regimines, for the purposes of comparing the performance of Pymaceutical's drug of interest, Capomulin, against other treatment regimenes.

## Analysis Summary
### Prepare the Data
* Cleaned dataframe by removing mouse ID data with duplicate time points, resulting in an updated number of unique mice IDs of 248.
![mice_study](images/mice_study.png)
### Generate Summary Statistics
* Generated a summary dataframe indexed by drug regimen with columns of the following tumor volume statistics: mean, median, variance, standard deviation, and SEM.
### Create Bar Charts and Pie Charts
* Illustrated total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study via bar chart.
* Illustrated distribution of unique mice gender in the study via pie chart.
### Calculate Quartiles, Find Outliers, and Create a Box Plot
* Illustrated distribution of final tumor volume for all mice in each of the four of the most promising treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin) via adjacent boxplots generated at scale. 
* Highlighted potential outliers in final tumor volume for each of the promising treatment regimens.
### Create a Line Plot and a Scatter Plot
* Selected a random single mouse treated with Capolmulin and generated a line plot of tumor volume versus timepoint, to illustrate the tumor development of a random mouse treated with Capolmulin over regular timepoints.
* Generated a scatter plot of mouse weight versus average tumor volume for the entire Capomulin treatment regimen, to illustrate any relationship between mouse weight and average tumor volume for mice treated with Capolmulin.
### Calculate Correlation and Regression
* Calculated correlatiion between mouse weight and average tumor volume for mice treated with Capolmulin. A correlation coefficient of 0.84 suggests a strong postive correlation between the two variables.
* Calculated linear regression for mouse weight and average tumor volume for mice treated with Capolmulin, to model the relationship of how average tumor volume changes when weight of mice treated with Capolmulin are varied.

## Observations
*
*
*