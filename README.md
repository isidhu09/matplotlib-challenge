# matplotlib-challenge

Tasks Completed:
* Prepared and cleaned the data
* Generated summary statistics
* Created bar charts and pie charts
* Calculated quartiles, find outliers, and created a box plot
* Created a line plot and a scatter plot
* Calculated correlation and regression

Preparing and Cleaning the Data
* Identified number of unique mice IDs in the data
* Removed mouse ID with duplicate time points
* Created a clean dataframe for use in remaining tasks

Generated Summary Statistics - Created two summary statistics DataFrames:
* Used the `groupby` method to generate the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen
* Second table, used the `agg` method to produce the same summary statistics table by using a single line of code

Created Bar Charts and a Pie Charts - Generated two bar plots
* Both plots are identical and showed the total number of timepoints for all mice tested for each drug regimen throughout the course of the study
* Created the first bar plot by using Pandas's DataFrame.plot() method
* Created the second bar plot by using Matplotlib's pyplot methods

Generated two pie plots 
* Both plots are be identical and show the distribution of female or male mice in the study
* Created the first pie plot by using both Pandas's DataFrame.plot()
* Create the second pie plot by using Matplotlib's pyplot methods

Calculated Quartiles, Find Outliers, and Create a Box Plot
* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin
* Calculated the quartiles and IQR to determine if there are any potential outliers across all four treatment regimens

Using Matplotlib
* Generated a box plot of the final tumor volume for all four treatment regimens
* Highlighted any potential outliers in the plot by changing their color and style

Created a Line Plot and a Scatter Plot
* Selected a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse
* Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen

Calculated Correlation and Regression
* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment
* Ploted the linear regression model on top of the previous scatter plot

