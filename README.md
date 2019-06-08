#Analysis of baseball players performance in Tableau

**Link to the first version of the story (before feedback):**

[https://public.tableau.com/profile/mostafa.elkhouly#!/vizhome/Project8-firstversion-firstsubmission/Performanceofbaseballplayers](https://public.tableau.com/profile/mostafa.elkhouly#!/vizhome/Project8-firstversion-firstsubmission/Performanceofbaseballplayers)

**Link to the final version of the story (after feedback)****:**

[https://public.tableau.com/profile/mostafa.elkhouly#!/vizhome/Project8-finalversion-secondsubmission/Performanceofbaseballplayers](https://public.tableau.com/profile/mostafa.elkhouly#!/vizhome/Project8-finalversion-secondsubmission/Performanceofbaseballplayers)

**Overview on the data set:**

A data set containing 1,157 baseball players including their handedness (right or left handed), height (in inches), weight (in pounds), batting average, and home runs. Notes: Create a visualization that shows differences among the performance of the baseball players.

**Summary:**

This data visualization is about analyzing the effects of handedness, height and BMI on the performance of 1,157 baseball players by measuring by their batting average and home runs. The plot show that there is a big variation in the performance of the players with a lot of outliers that go as high as 7 times the median of the data like in the left-handed home runs box plot, this affects the average (mean) of the data drastically. In the meantime, it is quite clear that there are positive and negative correlations between the performance with the BMI and height of the players, with the strongest being the negative correlation between the height and the batting average.

**Design:**

In this section, I&#39;ll explain any design choices I made including changes to the visualization after collecting feedback.

- Initial design decisions
  - I choose to show the distribution of the data to show the strength and weakness of the analysis, for example some BMI ranges are not represented and the obese range has only one player which can affect the analysis
  - After that I choose a combination of box plots to show the variance and outliers in the data as not to depend only on the mean in the future plots
  - In the last 2 story points, I plotted the effects of the independent variables (handedness, BMI and height) on the performance of the players. I choose the plot type to be a bar plot or scatter plot based on the type of variable discrete or continuous.
  - In general, I tried to combine the plots that are related to each other in the same dashboard as to have the information in the same page while comparing them
- Page 1:
  - Used different bar plots to represent the distribution of the players in the dataset over 3 factors; handedness, BMI and height
  - Based on the feedback I added an alias for the handedness to make it more clear
  - Based on the feedback I reordered the BMI plot x-axis to represent the correct order
  - Based on the feedback I changed the y-axis labels to be more descriptive
  - Based on the feedback I updated the tooltips to be more descriptive
- Page 2:
  - Used different box plots to show the distribution for average batting for all players and separate plots to show the distribution over the handedness and BMI
  - Based on the feedback I updated the column name of Avg to average batting to make it more clear what it is representing
- Page 3:
  - Used different box plots to show the distribution for home runs for all players and separate plots to show the distribution over the handedness and BMI
  - Based on the feedback I updated the column name of HR to Home runs to make it more clear what it is representing
- Page 4:
  - Used bar plots to show the effects of handedness on the performance in regards to batting averages and home runs
  - Bar plots were more descriptive than scatter plots for these discrete variables
- Page 5:
  - Used scatter plots to show the effects of BMI and height on the performance in regards of batting averages and home runs
  - Scatter plots were more descriptive than bar plots for these continues variables
  - I added a linear regression line for each plot to show the trend between the performance and the variables
  - Based on the feedback I added the missing legend to identify the color scheme for the plots
  - Based on the feedback I added a dynamic filter to the scatter plots that filters both plots simultaneously by handedness, I also update the title of the legend to be more descriptive

**Feedback:**

In this section, I&#39;ll include all feedback you received from others on your visualization from the first sketch to the final visualization.

- Feedback on the visualizations:
  - Tooltips need to be more descriptive in the first story point
  - The y-axis labels of the data set distributions in the first page of the story is not descriptive
  - The handedness x-axis labels in all plots is not clear what B, L and R mean
  - The BMI x-axis labels don&#39;t represent correct order of the BMI ranges
  - It is unclear what the abbreviations of Batting average (Avg) and home runs (HR) represent without reading the summary
  - The performance scatter plots in the last page of the story are missing the legend so it is not clear which color represents which factor
  - The plots need to be more interactive
- Feedback on understanding the visualizations:
  - The trend between the height and BMI was clear in the scatter plot of the last page
  - The height of the baseball players&#39; negative correlation with the batting average was the main takeaway from the visualization
  - The questions regarding unclear information is stated in the above section