# matplotlib-challenge


NOTE: Statistical Observations made based on Pymaceuticals analysis are located at the top of the Pymaceuticals.ipynb notebook.

Pymaceuticals: This code performs an analysis on a cancer study conducted on mice.  It reads in a file of mouse metadata, and a file of study data
to perform the following analyses:


    - Generates a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.  The
        table is generated firtst, using groupby, merge and rename functionality in pandas, and again in a single line using the pandas aggregate function.


    - Generates a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment
        regimen throughout the course of the study


    - Generates a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female vs. male mice in the study.


    - Calculates the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculates
        the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.


    - Generates a box and whisker plot of the final tumor volume for each of the four treatment regimens of interest and highlights any potential outliers in the plot
        by changing their color and style.


    - Generates a line plot of tumor volume vs. time point for a single mouse in the Capomulin study.


    - Generates a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.


    - Calculates the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment, plot the linear
        regression model on top of the previous scatter plot.


    -  Observations and inferences made based on the data are included as markdowns at the top of notebook.


