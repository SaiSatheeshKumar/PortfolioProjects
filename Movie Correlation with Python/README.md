In this project, we try to identify which variables effect the Gross Revenue of a movie using correlation.

Data source: Kaggle

Libraries used: Pandas, Numpy, Matplotlib, Seaborn

	1. Read the data from the CSV file
  
	2. Look for any missing data and drop rows with missing data
    
    3. Modify the data type of Budget, Gross, Votes, Run time from Float to Integer
    
	4. Extract the year from 'Released' column and store it in a new column called 'Year Correct'

    5. Budget vs gross revenue
  
    Check if Budget of the movie has an influence on the Gross Revenue
  
	  a. Create a scatter plot to understand the correlation graphically
	  b. Create a correlation matrix to find out the extent of correlation
	  c. Visualize the correlation matrix using a heat map for easier interpretation
  
    Budget and Gross revenue exhibit positive correlation of 0.74. Hence, we can conclude that movies
    with higher budget tend to collect higher Gross Revenue
  
	6. Producing Company vs gross revenue
  
    Check if Producing company of the movie has an influence on the Gross Revenue
    
	  a. Convert the Producing company column into numerical codes using pandas cat codes
	  b. Create a correlation matrix to find out the extent of correlation
	  c. Visualize the correlation matrix using a heat map for easier interpretation
 
    Producing company and Gross revenue have a correlation factor of 0.15 (no correlation). 
    Hence, we can conclude that Producing Company does not have any effect on the Gross revenue of the movie


