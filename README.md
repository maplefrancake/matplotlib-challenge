# matplotlib-challenge

## Analysis

In this analysis, we review the volume of tumors in 248 mice treated with one of 10 different drugs over time. In this study, we combined two datasets gathered- one being the descriptive data of each mouse, and the other being the volume of the tumor at a specified period of time in days after treatment began. We removed the data for one mouse (Mouse ID = g989) because it had duplicated rows on its ID and Timepoint, but varying volumes gathered. Since we could not verify which collections were correct, we opted to remove this mouse from the data as a potential error.

In reviewing the summary statistics, Capomulin and Ramicane appear to be the most effective, as their mean and median tumor sizes over all data points are significantly lower than those of other treatment plans. Though keep in mind that this is over all timepoints, and both of these treatments had the largest number of data points logged, as displayed in the bar chart below. Disclaimer aside, the boxplots below appear to show that the spread of tumor sizes are consistent across the four treatments reviewed (Ceftamin , Infubinol, Capomulin, and Ramicane). Ceftamin and Infubinol would be the next two treatments with the smallest mean/median tumor volumes after Ramicane and Capomulin, respectively.

In the final analysis, I compared the average weight for each mouse to their average tumor volume to see how well the weight of a mouse correlated to its tumor size. In this analysis, I found that the correlation coefficient was .84, which points to weight being a significant factor in determining how well Capomulin affects the tumor size of mice throughout its treatment.

