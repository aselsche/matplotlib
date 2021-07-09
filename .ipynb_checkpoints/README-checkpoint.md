**Matplotlib Challenge**

As a senior data analyst at the company, I was given access to the complete data from our most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. 

Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

My tasks were to generate tables and figures needed for the technical report of the study as well as prepare a top-level summary of the study results.


**Summary:**

First of all, to confirm the total number of total mice, I looked to see of there were any duplicate mice by Mouse ID Number that showed up for Mouse ID and Timepoint, which revealed there are only 248 mice.

Using both, the summary statistical method usining groupby and the aggregate method, a summary statistics table was prepared. It showcases the mean, median, variance, standard deviation, and SEM of the tumor volume.

Bar and Pie chart types were used to visualize the data on total number of unique mice tested on each drug regimen using pandas and pyplot. From the selected treatments Capomulin (230 mice) and Ramicane (228) were the most used; Propriva being the least used drug treatment (148). The Pie chart was used to present data on the distribution of female (49.6%) versus male (50.4%) mice. 

Using upper adn lower bounds, outliers were studied per each drug regimen. the only drug regiment that had potential outlier was Infubinol which was 36.32.

The correlation between mouse weight (g) and average tumor volume (mm) is 0.95 which shows a strong positive correlation; when the mouse weight increases the average tumor volume also increases. In addition, a regression analysis was carried out to show how much the average tumor volume (dependent variable) will change when weight of mice change(independent variables). The R-squared value is 0.90 which measures the closeness of the data to the fitted regression line. 90%  indicates that there are smaller differences between the observed data, and the fitted value. 

Using a line plot, were were able to analyze how the tumor volumne changed with the time (using the timepoint) when mouse was treated with Capomulin. It showed the tumor sized decreased with higher timepoint.

Using the scatter plot, we looked at the relationship between  average tumor volume and mouse weight for the Capomulin regimen, which showed again a positive correlation between the tumor volume and weight.

A box plot showed final tumor volume of each mouse across four regimens of interest. From the 4 selected treatments Capomulin and Ramicane showed promising signs of reducing the size of tumors more effectively.