Following files are included in the project

1. Rmd file: Quality_Analysis_of_Vinho_Verde_Wines_V2.Rmd
2. hyperlink: Quality_Analysis_of_Vinho_Verde_Wines_V2.html

NOTE: A list of Web sites, books, forums, blog posts and github repositories that were referred for this project are included in the reference section at the end of the Rmd and the html file.

----------------------------------------------------------------------------------

Corrections performed in the 3rd submission:

- I have excluded plots/section which I think do not correlate well with quality and alcohol. Some the plots sections I removed are as below:

- Scatter Plot for Red wine (Density vs. Residual Sugar)
- Scatter Plot for White wine (Sugar to Acid Ratio vs. Total Sulphur Dioxide)
- Scatter Plot for Red wine (Density vs. Combined Acidity)
- Scatter Plot for White wine (Residual Sugar vs. Combined Acidity)
- Scatter Plot for Red wine (Residual Sugar vs. Combined Acidity)
- Scatter Plot for White wine (Sulphates vs. Chlorides)
- Scatter Plot for Red wine (Sulphates vs. Chlorides
- Correlation between Total and Free SO2)


- Although, I met the specifications for project readibility, I have added appropriate saces before and after '=' sign.

- Axes limitation/scaling and jitter were used on plots where required in order to better represent and analyze the data.

- I have reduced the number of variables going into the ggpairs plot and also used short descriptive aliases for ease of viewing. I also removed the axes grid from the correlation boxes.

- Added the position = 'dodge' feature to the histograms for Quality with tast and Quality wih taste due to pH for both wine types.

- A regression line is now shown over the scatter plot of alcohol and pH to further emphasize the relation between the features.

- Alcohol and Quality with Taste for wine charts were converted from scatter to box plots and facet wrap per taste bucket was applied for ease of analysis.

- In the Bivariate section, correlation coefficient calculation or regression lines were added appropriately to emphasize the relation between two features.

- Final Plot 2 and 3 in the 'Plot and Summary' sections were improved to include both wine types and correlation/summary tables accompanying plot 3 for in depth analysis.

-----------------------------------------------------------------------------------

Corrections performed in the 2nd submission:

- Code character per line limited to 80 characters with the help of show margin feature in RStudio. Indentation/formatting done to accomadate each layer of ggplot on a seperate line where it was poosible.

- A combination of hex color coding on the url: http://colorbrewer2.org/ and colors used in Plot 3 was used to better represent quality ratings on scatter plots in the multi-variate section.

- Axes limitation/scaling and jitter were used on plots where required in order to better represent and analyze the data.

- Url: http://www.mathsisfun.com/data/skewness.html was used to understand the skewness in distributions and the concept was applied to the interpretation of skewed plots in the report.

- Although, I met the specifications for the plots summary section, I modified Plot 2 to include box plots for alcohol vs. qualiy of white wine samples.

-  Struggles sub-section was added to Reflection section to mention some of the problems/difficulies experienced during the report writing and coding in R.





