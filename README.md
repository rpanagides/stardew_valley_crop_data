# Stardew Vally Crop Data Visualization Project
## Purpose
This project explores player data from Stardew Valley, a farming simulation game known for its open-ended gameplay and rich in-game economy. The purpose of this project is to practice data analysis and visualization techniques while uncovering interesting patterns and insights from the game world. The final product of the visualizations were produced on Tableau. 

For this assignment, I attempted to visualize the similarities and differences between
Stardew Valley crops by season. I wanted to know if crops of certain seasons had longer
growing times, more outliers, or more crops with multiple harvests. I was also interested in
looking at crops across seasons with similar growing times. Ultimately visualizing this kind of
data could impact which crops a player may choose to plant in the game. With additional price
data, players can easily identify whether or not a crop with a long growing time is worth it
depending on the projected profit. Since my original dataset did not include price, I annotated
my graphs with specific price information for outliers, the crops with the shortest and longest
growing times per season and comparing crops from different seasons with the same growing
time.

The final product of the visualizations were produced on Tableau. 

## Data
This project focuses on Stardew Valley crops and their growing times across different seasons. I was particularly interested in exploring whether certain seasons tend to have longer growing times, more variability (outliers), or a higher number of crops with multiple harvests. I also compared crops across seasons with similar growing times to see how they aligned.

Since the original dataset did not include price information, I manually annotated my visualizations with additional data to highlight key comparisons—such as crops with the shortest and longest growing times per season, seasonal outliers, and crops from different seasons that share the same growth length. Including price data makes it possible to evaluate whether longer growing times are worth the investment when factoring in potential profit, which could ultimately influence planting strategies for players.

## Static Visualization of My Work
<img src = "stardew_vally_one.png" width = "600">
<img src = "stardew_valley_two.png" width = "600">
<img src = "stardew_valley_three.png" width = "600">

## Interpretation
I chose to display this data in three different graph styles: a horizontal bar chart, a
scatterplot, and a proportional area chart. While I used pretty much the same variables for each
visualization, different insights can be gleaned depending on how these variables are displayed.
For example, the bar chart shows the growing times of crops by season in ascending order. This
display makes it easy to see the distribution of growing times is similar between seasons. It also
makes it easy to compare crops with the shortest and longest growing times per season. I have
included price information for these minimums and maximums to show the relationship between
growing time and price. Similarly, the scatter plot displays the distribution of growing times
between seasons as well. I chose not to sort the crop names by growing time so the viewer can
see the variance of growing times between seasons. In this visual, I also chose to include
another variable, “multiple harvests”, which identifies crops that can be continually harvested
throughout the season. One may assume that crops with longer growing times may also largely
have multiple harvests but that is clearly not the case. I chose to use color differently in the first
two visualizations to highlight different aspects of the same data. In The bar chart, I used
chunking to highlight the different seasons while in the scatter plot, I used color to emphasize a
different variable rather than chunk the data by season. Lastly, I used a proportional area chart
with the same variables to emphasize which crops have the same growing times across
seasons. This type of visualization also shows the proportion of crops with each growing time. I
also used annotations to highlight all crops that take 12 days to produce an item and included
price data for each crop for comparison. Viewers can easily see that there are crops that take 12
days to grow in each season (fairy rose, cauliflower, and melon) and the highest priced one is
the fairy rose.

Each of these choices of visualization has its pros and cons. The bar chart is better at
displaying sorted data while the scatterplot is better at showing distributions. While the bar chart
and the scatter plot are good at displaying different information, the largest criticism I have is
with the proportional area chart. While the information that can be gathered from the
proportional area chart is interesting, it appears to be inaccurate. I am unsure if this is a product
of tableau or the way the data was structured but it is clear that the overall proportion of crops
with a 13 day growing time should be smaller than the overall proportion of crops with a 10 day
growing time. Additionally, there are squares that do not have any labels at all which distorts the
accuracy of the proportions. Lastly, some of the squares do not have the correct labels. For
example, there is a square in the 4 growing days category that just says “Summer” when it
should say “Summer Rhubarb 4”. I was unsure how to fix this glitch in tableau so it remains to
read as so.

I think the most important next steps that would enhance each of these visualizations is
to incorporate more data about price to really answer the question: What crop will be most
profitable for each season? I could not find a dataset with that information but I would be curious
to see the relationships and trends between growing times, multiple harvests, price of the seeds
and selling price. If I included price as a variable, I think the visualization that would most fluidly
display this data would be the barchart. Ultimately, the best way to display this information would
involve some data manipulation. To answer my question more completely, I would calculate the
maximum number of crops per 10 plants over the course of the season (this would take growing
time and multiple harvests into account). Then I would multiply this number by the average cost
of the crop and subtract the cost to purchase the seeds to determine which crop would be most
profitable per season.


