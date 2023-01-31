| [home page](https://mahnoorayub.github.io/Mahnoor-Portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Government Debt Visualization

General government debt-to-GDP ratio measures the gross debt of the general government as a percentage of GDP. It is a key indicator for the sustainability of government finance. Debt is calculated as the sum of the following liability categories (as applicable): currency and deposits; debt securities, loans; insurance, pensions and standardised guarantee schemes, and other accounts payable. Changes in government debt over time primarily reflect the impact of past government deficits.

The following chart shows the government debt to GDP ratio of countries in 2020. The two countries highlighted are the ones that have the highest Debt to GDP ratio. All other countries are in grey and the OECD average is highlighted in black colour. 
 

<iframe src="https://data.oecd.org/chart/6Y4R" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6Y4R" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>

# Government Debt Grid of charts

The following chart visualizes the GDP debt ratio across a number of countries and years. 
Since we have a lot of different countries to explore across a number of different years, we chose to work with a line chart, but then turn it into a grid of line charts. 
I have made the graph look a bit like sparklines with some formatting.

<div class="flourish-embed flourish-chart" data-src="visualisation/12584737"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

# Government Debt to GDP Ratio of European Countries

The following graph uses a subset of the data to visualize the comparison of GDP Debt ratio for the European Countries in 2020. 

I have used a projection map in Flourish for this visualization. 

<div class="flourish-embed flourish-map" data-src="visualisation/12597604"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


The projection map was a good choice of chart for this data as it is comparing a value between different countries that I have grouped into different bins useing a colour scheme that shows countries with different levels of GDP Debt ratio. Countries with the higher ratio are in shades of red and countries with the lower ratio are in shades of blue. 

The bar chart in the first part allows us to compare the data across countries for a given year. The limitation for this chart was that only data for a given year can be seen but not a comparison over time. It can also inlove a lot of eye travel to compare the bars for each country if the pop ups were not avalailable. The second grid of charts was useful for showing multiple countries over multiple years while taking into account the missing data. However while this chart is great for comparing data over time it is hard to compare the countries with one another. 

I had initially tried to use the projections map for displaying the whole dataset as shown below, but I saw a number of limitations with flourish. Firstly the map is showing only data for one year, I wanted to add a slider control through which you can change the years and the projection map changes accordingly. After some research I found that it is possible to do that in Flourish, however you need to have your data in a specific format with each year in a separate coloumn. I decided to stick to just the year 2020, but for a more advanced visualization the data formatting can be changed and the slider control can be added to see the data for all years. This can allow for the data to be compared across the years and across the countries
The second reason why I chose the subset of European countries was that our dataset had missing values for a lot of the countries so a large chunk of my projections map was greyed out. Also most of the information in the dataset is for European countries and in the whole world map it can be hard to see the colour difference in the smaller European countries for instance one of the highest GDP Debt ratio is for Greece but it was hard to see that in the visualization below. Therefor I decided that I will make a visualization for an audience that wants to compare the GDP Debt ratio between the European countries in the year 2020. 

<div class="flourish-embed flourish-map" data-src="visualisation/12585656"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
