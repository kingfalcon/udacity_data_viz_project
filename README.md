SUMMARY

For my visualization, I've opted to analyze a data set containing five features (handedness, height, weight, batting average, and home runs) for 1157 baseball players from history. This visualization seeks to illustrate two things: (1) the positive relationship between batting average and home runs, and (2) that this relationship persists regardless of whether the batter is right-handed, left-handed, or a switch-hitter.  



DESIGN

For my initial design, I had planned to include three side-by-side histograms showing the number of batters by type of handedness (e.g., right, left, both/switch). However, after digging into Dimple.JS, I learned that it does not seem to support histograms. Therefore, I instead created a scatterplot that shows the positive relationship between batting average and number of home runs. The reason why I opted for this visualization is that I discovered, during my exploratory data analysis, that batting average and home runs have the highest linear correlation in my data set (other than height and weight). I selected a scatterplot because it's an appropriate chart type for conveying relationships between two continuous variables. In my initial designs, I also colored the dots based on whether the batter was right-handed, left-handed, or a switch-hitter. I made this addition to help the viewer easily see how the distributions vary for different types of handedness. Based on the feedback I received, I decided to make some changes to my design. First, I increased the number of significant digits on the x-axis to make it easier to interpret. Second, I changed the legend on the handedness to make them easier to understand. Additionally, I added descriptive titles to make it clear what the visualization represents.



RESOURCES

stackoverflow.com
elitedatascience.com
towardsdatascience.com
seaborn.pydata.org
dimplejs.org
