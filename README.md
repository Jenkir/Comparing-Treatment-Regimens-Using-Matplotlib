# Matplotlib-Assignment

For this assignment, the premise is that I've joined Pymaceuticals Inc., a burgeoning pharmaceutical company that specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
As a senior data analyst at the company, I've been given access to data from a recent animal study in which 249 mice identified with SCC tumor growth were treated through different drug regimens. Over 45 days, tumor development was observed and measured. The purpose of the study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. The executive team requested that I generate the tables and figures needed for the technical report of the study as well as a top-level summary of the results.

The major steps were as follows:


1. I checked the data for any mouse ID with duplicate time points and removed any data associated with that ID. I then used the cleaned data for the remaining steps.

2. Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

3. Generated a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen. 

4. Generated a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

5. Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin; calculated the quartiles and IQR and quantitatively determined if were any outliers across all four treatment regimens.

6. Using Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlighted potential outliers in the plot by changing their color and style.

![image](https://user-images.githubusercontent.com/75215001/127552132-3d95cf7f-4ab9-448d-bb8f-eaddc8a78d3a.png)


7. Selected a mouse that was treated with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.

8. Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

9. Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plotted the linear regression model on top of the previous scatter plot.



