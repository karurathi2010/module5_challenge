# module5_challenge
# Pymaceuticals Inc.
---

### Analysis
Two data sets were given for this analysis,
1-Mouse_metadata
2-Study-results

Both these data sets combined into a single data frame and performed several analysis and visualizations to  compare the performance of Capomulin, against the other treatment regimens.
In this study, 249 mice who were identified with SCC tumors,but we had duplicate rows in the combined dataframe.
So as the first step all the duplicates were removed from the dataframe and made a clean dataframe for the further analysis.

### Summary Statistics:

Here some statistical operations were performed and found the mean, median, variance, standard deviation, and SEM of the tumor volume,then assembled these results in a single dataframe.


### Bar and Pie charts:

Here generated a bar plot showing the total number of rows 'Timepoints' for each drug regimen.From this graph we can see that Capomulin has the highest time points.

Then generated a pie plot showing the distribution of female versus male mice,and it showed that 51% of the data is male mice.

### Quartiles, Outliers and Boxplots:
Selected 4 regimens Capomulin, Ramicane, Infubinol, and Ceftamin for the rest of the analysis then calculated the final tumor volume of each mouse across this four of the treatment regimens.

Using this data calculated the IQR to determine if there are any potential outliers.

Generated a box plot that shows the distrubution of the tumor volume for each treatment group,

### Line and Scatter Plots:
Inorder to get more clarification about the Capomulin regimen, we selected a single mouse and generate a line plot of tumor volume vs. time point treated with Capomulin.

Then generated a scatter plot of mouse weight vs. the average observed tumor volume for the entire Capomulin regimen.

### Correlation and Regression:
Using the previous scatter plot calculated the correlation coefficient and a linear regression model for mouse weight and average observed tumor volume for the entire Capomulin regimen.

### Conclusins:

1) From the  Boxplots, compared to other regimens the Capomulin shows a left_skewness that is the smaller tumor volumes are more spreded out than the larger tumour volumes.

2) By considering single mouse with Capomulin, the  Line plot clearly shows that as the Timepoint increases the Tumorvolume is decreasing.So the performance of Capomulin is      very positive compared to other regimens.

3) After  all calculatins we got the correlation value as 0.84 ,means there is a strong linear correlation between the weight and tumor volumes.
